# Assignment: Critique by Design

## Original Data Visualization
### Pittsburgh Budget Priorities
<img src="Pittsburgh Budget Priorities.png" width="600"/>

I chose this visualization because I am always looking for better ways to visualize budget data. I currently work in municipal finance and budgeting, and I designed many of the charts for our municipal budget narrative. I have always just done the charts in Excel, and though our municipal budget is publicly available, there is not a broad audience for my charts. Part of my intent in taking this class is specifically to be able to visualize budget data more effectively. I work in a small community, but I wanted to see what data visualizations would be like for a city. 

Pittsburgh uses priority-based budgeting software, which I imagine is what produced the visualization for their priority-based budget chart. It is not a bad visualization, and it is miles better than most budgeting charts I have come across. However, though the information was there, it still didn't grab my attention like I was hoping it would. I want to make municipal budgets engaging, and so I decided to see if I could make this chart a little more engaging. 

## Critique

I love that Pittsburgh is using priority-based budgeting (PBB), and I think the bar chart is an appropriate visualization here, but it doesn't feel intuitive or aesthetically pleasing. I think PBB itself is an engaging topic, but I'm not getting that from the visualization here. I think it does well in ranking the priorities and not providing too much information on the visualization itself, but the lines are too thin and the colors are confusing and distracting. I have to stare at it for a minute to figure out what it's trying to tell me. It does a good job of making sure the lines are the correct length for the correct sum of money, and it contains most of the relevant data and is informative. However, the labels on the y-axis are not intuitive, and though it has a link for definitions, the link doesn't work. Additionally, each bar actually represents a sum of programs, and I think there could be a really interesting way to visualize that that is not being done here. The title also does not provide much information beyond being informative. I would add a more informative title, maybe a brief subtitle for the y-axis labels, change the actual bars, change the color scheme to be more cohesive, and find a way to incorporate the number of programs that make up each category. 

I think the primary audience for this tool is likely people who are already interested in the City of Pittsburgh's budget, such as interested residents but also other people who work in municipal finance who are interested in what Pittsburgh is doing. However, I think Pittsburgh is also looking to capture a broader population of residents to get them interested in the budget and priority-based budgeting. For people already interested, I think the visualization is effective enough. It is certainly better than most other budget visualizations I have seen. It contains the relevant information, even if it is not engaging. However, to capture a wider audience, as I believe Pittsburgh is trying to do, the visualization itself is not effective because it is not more engaging. 

Going through this critique method helped me realize that although the original data visualization was not bad, I was looking for something more out of it and wanted to see what it could do. It also helped me realize that this chart only shows one dimension of the data, the funding allocation. While the funding is important, the interactive chart on Pittsburgh's budget page also showed the number of programs for each category when you hovered over one of the bars. However, they noted that programs could be in more than one category, which made the data more unclear and confusing. Therefore, I wanted to dig into the data and find out what was going on with the programs in terms of funding. The overall dollar amount is important, but it is also essential to know how many programs fall into that category that are receiving funding. 

## Redesign Sketches
<img src="Pittsburgh Budget Redesign Sketch.jpg" width="600"/>

I like the use of symbols, so I redesigned the visualization keeping the bar graph but using symbols for each bar to give a visual idea of the number of programs associated with each category. Being able to distinguish the exact number of programs was less important to me than giving a sense of just how many more programs are associated with one category over another. I also sketched rough sketches of a treemap and a bubble chart, trying to show the dimensions of the budget better, but in the end I did not show them for feedback. 

## Feedback

I spoke with two individuals who gave me a lot of excellent feedback. Importantly, they had some knowledge of budgeting and municipal finance but had not worked in it before, so I needed to understand what level of context was necessary to show in the visualization. 

### Student, early 30's

This person suggested that this chart is talking about how Pittsburgh has invested their money into different capacities that they incorporate into their budget every year. However, they quickly reframed it as the amount of money in training people in different programs and their priorities, as it seemed unlikely that Pittsburgh would be investing more into critical communities than infrastructure. 

They also suggested that the audience could be local stakeholders, like nonprofits and businesses, but it is probably not the local citizen. 

They said it does not make sense that they are programs and suggested changing some of the labels to indicate that they are programs. Additionally, they suggested changed titles and grouping some of the categories together to suggest themes.

### Adult, early 60's

This person suggested that this chart iss demonstrating the number of programs and budget priorities for Pittsburgh. They interpreted that more effort is being devoted to some categories, but they didn't know what the total was in terms of percentage for each category. Coming from a financial background, they were used to seeing a chart like this demonstrating percentage of totals. They were also confused about the definitions of some of the categories, such as Critical Communities. They didn't know whether the scale is the number of programs or the dollar amount, and they had questions about whether the programs were funded equally and which programs were more expensive. 

They suggested that it could be part of a public presentation to constituents to say this what we’re emphasizing in our budget priorities, but in general it is more for a budget and planning committee, or a city or county council. 

They suggested showing correlation between the number of programs funded and the total dollar amount. 

### Takeaways

Talking with these two people helped crystallize that the relationship between the programs and the funding in each category was not clear. They seemed to see them as distinct, with no relation to each other. Therefore, I realized another chart type showing correlation was probably needed. This led me to a scatterplot for the final redesign. 


## Final Redesign
<div class="flourish-embed flourish-scatter" data-src="visualisation/12678393"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

My original issue with the original visualization was that it was not engaging enough to the viewer, but the more deeply I dug, the more I realized that it was not showing an important relationship between its two variables at all, but instead presenting them as entirely discrete. Using Flourish and Tableau, I did try several different iterations of the cleaned data before settling on the final scatterplot. 

In the end, though not the ideal form of budget visualization I anticipated at the beginning of the process, the scatterplot helped illustrate what had become the main difficulty, which was showing the correlation between the number of programs and the amount of funding allocated. 

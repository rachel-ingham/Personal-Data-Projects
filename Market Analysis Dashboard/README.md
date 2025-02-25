# Personal Project - Market Analysis Dashboard

### The Prompt
The founders of the New Canadian Chocolate Company have asked for market research before launching their premier chocolate line. They are interested in finding the top competitors to watch, what is popular in the industry, and where to source cocoa beans.

### The Data
The original dataset contained over 2000 datapoints on chocolate companies around the world, the year their chocolate was reviewed, the country of bean origin, the cocoa percent, and the rating recevied. I chose to focus my analysis on the Canadian market specifically, which narrowed the dataset to 183 datapoints. 

![image](https://github.com/user-attachments/assets/aa995aac-74cb-4bd9-89f1-906fea985fdc)

### The Process
In approaching this market analysis, I began by focusing on the makeup of the chocolate bars. I wanted to determine if there was a popular cocoa percent, and whether this changed from year to year as consumer tastes changed. I decided to summarize each year using the maximum and minimum cocoa percents, and also consider the average cocoa percentage across all of the data. 
![image](https://github.com/user-attachments/assets/b49b75de-6248-4e15-a215-c70360a96311)

I was also interested to know whether chocolate bars with blended beans were popular or did well in the flavor ratings. Since some of the country of bean origin data was listed as "blend" it was possible to compare the average ratings in a column chart. I highlighted the Cocoa Blend column in a different color so it would stand out from the average ratings of bars with beans from a single country.

![image](https://github.com/user-attachments/assets/d853077d-a3bd-4f93-82ad-d42991aba013)

In order to explore New Candian Chocolate Company's competitors in the market, I wanted to focus on where beans are currently being sourced and what other companies tend to have bars with high ratings. By grouping data by country of origin and counting the number of ratings, I created a treemap to highlight the top 5 countries where beans are sourced. 
![image](https://github.com/user-attachments/assets/a2ef1bfd-d9bd-4d44-babf-e50f0cf87e9f)

And finally, I created a table of maximum flavor ratings for each company, differentiated by each year. This table would allow the New Canadian Chocolate Company to quickly see that Soma chocolate receives the highest rating on at least on of their entries pretty consistently. I decided to filter the final version of the table for just the companies who had received the top flavor ratings of 3.5 and above, so the frontrunners in recent years would be obvious.

![image](https://github.com/user-attachments/assets/db9af8f6-83a6-4e3b-af52-9d64e822f5ae)

### Results
Most canadian companies source their beans from South America, primarily Peru, Dominican Republic and Venezuela. By sourcing from these same countries, the New Canadian Chocolate Company can utilize established vendors and offer competitive quotes to cocoa farms. Notably, pure cocoa bars do achieve high ratings but it is possible to score well in taste with a blend of cocoa beans. The company should focus on creating a blended bar to set themselves apart from the rest of the market, or experiment with a chocolate that uses only beans from Venezuela to score well in taste. When deciding on the cocoa percent in new products, the company should not stray too far from the 70% cocoa mark, as this is a popular percentage that does well in the ratings from year to year. Top competitors in terms of chocolate ratings include Qantu chocolate and Soma chocolate. Further research into these companies, their strategies, and marketing should be done to identify new market niches that can be explored. 

I created a Tableau dashboard to easily display the results of my market analysis. The dashboard allows the founders of the New Canadian Choclate company to filter the results by year to differentiate newer trends from older ones.

![image](https://github.com/user-attachments/assets/b9b77000-4a52-424b-a26c-81d4d228b215)

### Project Link
https://public.tableau.com/views/CocoaDataDashboard_17368825969740/CanadianCocoaMarket?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


# Sports-Analytics: NBA Salary and Player Stats Data 

This project aims to leverage business intelligence techniques to conduct a comprehensive analysis of NBA player statistics, team performance metrics, and social media engagement during the 2016-2017 season. I aim to extract valuable insights that can empower General Managers (GMs) of NBA teams in making strategic decisions for their team.


# Introduction
The objective of this project was to create a complete dashboard for NBA team managers and executive teams. These dashboards will provide insights into player performance, salary justification, fan engagement, team performance and other key metrics. The dashboard aimed to help with decision-making processes and strategic planning within the organization for better success of the team.

We began by identifying key stakeholders and understanding their requirements. This can involve conducting interviews with team management and analyzing existing data sources. Based on the requirements, we have designed a set of 9 reports covering various aspects of NBA data. These dashboards include visualizations for player performance, team salary evaluation, fan engagement, and team performance analysis. We decided to use Power BI for dashboard development due to its flexibility, ease of use, and creative visualization capabilities. Power BI allowed us to create interactive and visually appealing dashboards that met the project requirements. We collected relevant data from various sources including player statistics, team performance data, salary information, and fan engagement metrics. This data was cleaned, transformed, and filtered for analysis in Power BI. Using Power BI Desktop, we created individual visuals for each dashboard based on the predefined KPIs and drill-down requirements. We leveraged Power BI's features to enable interactivity, drill-down functionality, and customization. Once the dashboards were finalized, we published them to the Power BI Service where team management and other stakeholders could access them. The implemented dashboards provided team management with valuable insights into player performance, salary justification, fan engagement, and other key metrics.

# Dashboard #1 Player Salary vs Age 

The objective of this dashboard is to provide a comprehensive overview of NBA player salary caps for the year 2017-2018, along with detailed player draft numbers linked to the player. The dashboard provides users data of team spending, player salaries, and the distribution of player ages within position. This report is found under “Player Salary”.

Here are the key deliverables of the dashboard:

●	The dashboard displays a summary of each NBA player’s total salary cap for the year 2017. This allows users to quickly compare spending across players and identify high-earned and low-earned players.

●	The linked dataset provides detailed information about each player and their corresponding salaries for the year 2017-2018. Users can explore this data to understand which players contribute to the league in that season. We can identify any particularly high-earning players while reviewing their performance from the player and team performance dashboards in this project.

●	The slicer report allows users to select a specific age range for NBA players. This functionality enables users to filter player data based on age.

●	The dashboard is interactive, allowing users to drill down into specific teams or players for more detailed information. For example, clicking on a player name will reveal player salaries, or selecting a specific age range will dynamically update the displayed player data.
 
How to use: 

You can see an overview of players' salaries in a complex pie chart. You can begin to filter by adjusting age to your requirement and select a player of your choice to learn more about him. As you type the age, you can see the table drill down on players in that age group. You can select any player and learn what number they were drafted in the NBA and how much they are getting paid. You can understand why high drafted numbers get paid more as they are more skilled. You can select these players from the pie chart and also learn about their details that way. You can also see how age past 35 impacts a player's earnings by a lot as a player starts to perform badly.

# Dashboard #2 ELO rating

ELO rating can indirectly influence player salary decisions and team salary cap management in several ways. Teams with higher ELO ratings are often considered more valuable assets to their managers due to their consistent performance and contribution to winning games. As a result, teams may offer higher salaries to players with higher ELO ratings. ELO ratings serve as a metric to evaluate player performance relative to their peers and the league as a whole. Players with consistently high ELO ratings are likely to have higher market value, leading to higher salary demands during contract negotiations. Teams may need to make strategic decisions to balance the roster and stay within the salary cap limits while maximizing performance. Teams may prioritize investment in players with high ELO ratings, viewing them as valuable assets that can significantly impact team performance and success. This investment may involve offering higher salaries or longer-term contracts to retain top talent and maintain a competitive edge.

This Dashboard helps understand the ELO rating in an enhanced way where it compares it to all teams in standing. It also helps to break down each conference as you might not be competing against in your conference but a team manager from the opposite conference can evaluate your player based on this rating and help them get a better contract. This dashboard can help break down the numbers and gain better insight on how the overall league is doing in terms of ELO rating. Top 5 teams are desired locations for any free agent player to enter the market as they know they can win the championship with the highest ELO rating team. ELO ratings provide a valuable tool for teams to assess player performance, determine market value, and make strategic decisions regarding player salaries and team salary cap management. By leveraging ELO ratings effectively, teams can optimize their roster composition, maximize player contributions, and maintain financial flexibility within the constraints of the salary cap. This report is found under “ELO Rating”. 

How to use: 

The report is designed to be intuitive and user-friendly, allowing users to quickly understand the current state of NBA ELO ratings. You can click on East or West and drill down conference data by looking at teams in each conference. You can also filter each team by simply clicking on the team’s name on a graph and pinpoint exactly where they lie on a graph to compare with other teams. The team you have clicked will be shown on a table with the values you are looking for and understand their ELO rating.

# Dashboard #3 Rookies Performance

The objective of this dashboard is to provide a comprehensive analysis on rookie NBA players' performance based on various statistical metrics such as games played, points per game, minutes played, field goal percentage (FG%), player efficiency etc. The dashboard compares the performance of rookie players and identifies standout performers based on these metrics. The dashboard presents a summary of each rookie NBA player's performance statistics. This summary provides users with a quick snapshot of each player's performance across key metrics. Users can filter the player data using the linked dataset, allowing them to focus on specific players. This helps GMs to make strategic decisions to offer them good pay for the next season. This can also help them decide to trade the players for the right player. We can use this report to make a Rookie of the year (ROTY) decision and help the league find the best rookie of their class. This report is found under “Rookie Data”. 

How to use:

Users can click on players from the table to drill down to their stats on a right table under Player Stats. Users can also use sliders on scatter charts to zoom in and out of the chart and filter players based on their points per game (PPG) and FG%. Higher the PPG, higher their minutes played in a game. The size of each point on the chart is based on how much time the player is playing the game which helps you visualize top performers. You can also use an efficiency slicer to narrow the search by desired %. All players have their respective stats showcase in a table format which can be customized from the main dataset (CSV file) attached to this dashboard. One can add or remove the category of their choice.


# Dashboard #4 Social Media and Engagement Report

Report #1 

Engagement Metrics and Key Influencers
This dashboard shows a quick, high-level overview for social media metrics for players in the NBA. It uses the data retrieved from the 2017 season, which includes three aggregate social media metrics, Twitter Favourites, Twitter Retweets, and Wikipedia Pageviews. It is designed to display the influence of various statistics on NBA players' salaries and then to compare those statistics to engagement metrics by position, team, and player.

Starting at the top, there are display cards showing the aggregated data for each of the three different social media metrics used. The primary goal for these cards is to provide a quick snapshot of the total values of each metric, and to change dynamically when drilling down to show per team or per person as well.

From there, the section named ‘Key Influencers’ contains a number of statistics that are analyzed against salary, in millions, to see if there are any correlations between them. It includes statistics like the previously mentioned social media metrics, but also performance-based metrics and game statistics to gauge the effectiveness of the social media metrics over the others. Each stat is then shown if a particular stat can be correlated with an increase in salary, and if so, displays the average salary increase. The further the grey bubble, the greater the associated influence on salary. Clicking on any of the bubbles pulls open a chart dependent on the stat being analyzed that visualizes the respective statistic.

Moving to the right, the ‘Engagement Metrics Average by Position, Team, and Player’ bar chart breaks down the averages of each social media metric by player position (Point Guard, Small Forward, Centre, Power Forward, and Shooting Guard). Its goal is to allow comparisons between the engagement metrics across different positions to see which positions have more engagement. Additionally, this chart has drill-down functionality, meaning each position is clickable and will give a more detailed breakdown by team, and then clickable again to breakdown by individual player. This enables an in-depth analysis of which teams and players are getting the most social media impressions, which could be considered valuable for gauging popularity or public interest. It can also highlight some disproportionate levels of engagement between positions, teams, and players themselves. This allows a useful way for marketing, talent scouts, owners, and coaches to understand the impact each of these statistics has on public engagement and if a particular player is under or overvalued.

Report #2  

Engagement Metrics vs. Endorsements and Salary
This dashboard has two similarly styled charts that draw a comparison between NBA players with endorsement deals, their financial earnings, and their social media presence. It offers more insights into the relationship between a player’s market value and their popularity among fans.

The first chart on the left side displays the NBA players that had endorsement deals during this timeframe. It is a straightforward bar chart that signifies the amount for each endorsement in millions on the Y-axis, the players on the X-axis, and then the totals of all the aggregated social media engagement as a line. This comparison is useful for understanding how a player’s off-court impressions translate to financial value through brand partnerships. This chart allows a quick gauge on how engagement and endorsement earnings suggest that a player's fan popularity is successfully capitalized upon. It can then identify patterns in a particular player’s branding success, or if certain players are worth more than their current value.

On the right-hand side, the second chart is laid out in the same design as the first but focuses on salaries instead. It uses the same players as the endorsement chart to give a better comparison between the two. Using this chart, users can identify any correlations between a player’s actual earnings from basketball and their fan engagement metrics. In this way, a player with a high salary with a similar level of engagement can indicate their value is well represented, or that they achieve an adequate level of engagement for their price. Conversely, it can also spot any mismatched levels of engagement vs. their salary.

Looking at both charts together, if both salary and endorsements align with the engagement for a player, it can confirm a relationship between their monetary value and fan impressions. The dashboard serves as a strategic tool for owners, coaches, and marketing professionals to gauge and utilize a player's marketability, ensuring their financial agreements reflect their standing from a purely fan engagement perspective.



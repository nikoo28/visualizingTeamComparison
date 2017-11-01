# A Statistical Analysis of Cricket One-Day Internationals

Cricket is an extremely popular game since last five centuries and played in countries all over the world. There are several attributes which decide the outcome of a game; the team winning the toss, field conditions, the pitch and most importantly the performance of individual players. A game of cricket mainly has three aspects - batting, bowling and fielding. It is essential for a team to score a high number of runs in the given number of balls.
If we could somehow visualize the performance of players then the insights could help in assessing a game better. For instance, players can try to become technically better by observing their own performance, a team can plan a strategy in advance before facing it’s opponent and thirdly the organizing committee can even decide which players to choose for the next game.
The system serves two types of audience
 - A sports journalist who wants to analyze a team’s performance
 - A fan who wishers to discover the trends of his/her favorite team or player.

Keeping them in mind we decided upon two design principles
 - The user should be able to select what he wants to see
 - Make the system interactive enough which forces the user to explore hidden insights from the data.

# System Overview
![System Overview Image](https://preview.ibb.co/coDh5w/44776333.png)
System Overview showing the performance of Indian team for a total score of 300 or more. Views contain a scatter- plot for each inning, a stacked bar chart for each player, a bar graph showing the win/loss margin and a stacked area graph showing the top 10 players performance

# Interaction with the system
The system consists of four modules and we provide the user with two drop-down menus, that list the names of the various cricket playing nations. These drop downs provide an effective way of filtering the results based on a team and the opposition it has played against. Changing these values make an impact over the overall figures. The blue color represents that the innings resulted in a win, while a red means that the innings resulted in a loss. By default, ‘India’ is selected. In this state, the user is presented with four critical metrics

### Installation

The system requires Apache Server and can be run on any operting system. The data is to be present in the folder /allData in the following CSV format

| playerName | runs | year | home | against |
| ------ | ------ | ----- | ------ | ------ |

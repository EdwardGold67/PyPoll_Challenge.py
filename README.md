# PyPoll_Challenge.py

week 3 for Coloumbia's DS bootcamp
---
## Overview of Election Audit
The purpose of the analysis was to determine which candidate won the election based on their vote percentage and total number of votes. In addtion, I calculated which county gave the most support to the winning candidate. To perform this analysis I used python via the Visual Studio Code platform. 

---
## Election Audit Results
### Election Outcomes 
The first step in my audit after importing the csv and os was to link the election results csv to python by assigning a variable to load a file from a path. Following that step I assigned a variable to save the file to a path. Reading and writing data, I performed calculations on the vote count and used conditional statements and loops to calculate the results. The following bullet points contain the election audit results
* Total votes in election: 369,711
* The three candidates were Charles Casper Stockham, Diana DeGette and Raymon Anthony Doane
  * Charles Capser Stockham recieved 85,213 votes (23% of the total votes)
  * Diana DeGette recieved 272,892 votes (73.8% of the total votes)
  * Raymon Anthony DoaneL recieved 11,606 votes (3.1% of the total votes)
* The three county's that voted were Jefferson county, Denver county and Arapahoe county
  * Jefferson county had 38,855 voters and made up 10.5% of the total vote count
  * Denver county had 306,055 voters and made up 82.8% of the total vote count
  * Arapahoe county had 24,801 voters and made up 6.7% of the total vote count

Colorado's three counties tallied up to 369,711 votes. Denver was the largest county with 306,055 votes making up 82.8% of the total vote count and Dianna DeeGette  won the election by recieving 272,892 votes whihc was 73.% of the total votes. The election results can also be seen in the text file election_analyis.txt, as seen in the screen shot below.
![election analysis results.png(https://user-images.githubusercontent.com/48603147/140675141-ec1a35f4-f63f-4851-990e-ea2d7cc43c24.png)



In the

After counting up the total votes for each candidate I calculated their vote percentage by dividing their total votes by the total number of votes. My code can be seen in the following screenshot. 
![county vote count.png](https://user-images.githubusercontent.com/48603147/140671470-563ff65e-97c6-48ff-b182-4acaea1b693c.png)

### Outcomes Based on Goals
In the second step of the analysis, I narrowed down the focus on plays, a sub category of theater. This time I compared how the outcomes were impacted based on the monetary goals for which the kickstarter’s were set at. To group projects based on their goals, I created dollar-amount ranges so that the data can be read more clearly. Using the Countifs function,…,I calculated the sum of successful, failed and canceled projects based on what range their goals were in. Following that step I summed up the total projects, within their ranges, using the sum function and divided by the number of successful, failed and canceled projects. From this I calculated the percentages of each outcome to make the data easier to understand and manipulate. As you can see from the line graph below, I put the dollar-amount ranges on the x-axis and the outcome percentages on the y-axis. 
![Outcomes_vs_Goals.png](https://user-images.githubusercontent.com/48603147/138618042-3912440b-ffe0-48aa-ac2d-ae55b38eb0f4.png)

### Challenges
One of the challenges I encountered was dealing with unexpected results. I thought that there would be a number of canceled plays present in the second analysis however there were none present in the data and it caught me off guard. I thought I made an error so I went to the raw data and filtered out outcomes by canceled. This helped me confirm that the steps I took in the analysis were correct.

---
## Results
### Theater Outcomes by Launch Date
After analyzing the line chart I created for Theater Outcomes by Launch Date, I concluded that theater Kickstarters were being launched at a higher rate during the spring and beginning of summer time with May having the largest number of projects with successful outcomes. This is probably due to warmer weather and people being more inclined to go out. A second observation I had is that canceled theater projects were not greatly affected by the time of year. This could be because canceling a project could be a result of multiple factors.
### Outcome based on Goals 
I have concluded from the line chart that generally goals with lower dollar amounts have higher success rates. While this was not the case for goals between the ranges of $35000 to $44999, the number of projects in that range was small and not really substantial.

### Dataset limitations
One limitation in the data set I noticed was that there were a number of outliers present with projects that had very unrealistic monetary goals. With some project goals exceeding a million dollars and others asking for one dollar, the data could have been distorted from these questionable projects. I think a new table that be created for futher analysis could be using a Box Plot of successfully funded plays in the US.

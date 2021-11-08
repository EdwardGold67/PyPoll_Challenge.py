# PyPoll_Challenge.py

week 3 for Coloumbia's DS bootcamp
---
## Overview of Election Audit
A Colorado Board of Elections requested for an election audit of a recent local congressional election. The goal of the analysis was to determine which candidate won the election based on their vote percentage and total number of votes. In addition, I calculated  the total number of votes that came from each county and determined which county was the largest contributer. To perform this analysis I used python via the Visual Studio Code platform. 

---
## Election Audit Results
### Election Outcomes 
The first step in my audit after importing the csv and os was to link the election results csv to python by assigning a variable to load a file from a path. Following that step I assigned a variable to save the file to a path. Reading and writing data, I performed calculations on the vote count and used conditional statements and loops to calculate the results. The following bullet points contain the election audit results:
* Total votes in election: 369,711
* The three candidates were Charles Casper Stockham, Diana DeGette and Raymon Anthony Doane
  * Charles Capser Stockham recieved 85,213 votes (23% of the total votes)
  * Diana DeGette recieved 272,892 votes (73.8% of the total votes)
  * Raymon Anthony Doane recieved 11,606 votes (3.1% of the total votes)
* The three county's that voted were Jefferson county, Denver county and Arapahoe county
  * Jefferson county had 38,855 voters and made up 10.5% of the total vote count
  * Denver county had 306,055 voters and made up 82.8% of the total vote count
  * Arapahoe county had 24,801 voters and made up 6.7% of the total vote count

Colorado's three counties tallied up to 369,711 votes. Denver was the largest county with 306,055 votes making up 82.8% of the total vote count and Dianna DeeGette  won the election by recieving 272,892 votes which was 73.8% of the total votes. The election results can also be seen in the text file election_analyis.txt, as seen in the screen shot below.
![election analysis results.png](https://user-images.githubusercontent.com/48603147/140675066-96bce950-826e-4073-b7a0-6d4920e6ee19.png)


---
## Election Audit Summary
### Statement to election commission
The script I created can be used for any election audit with a couple modifications. When referencing the csv file one would have to change the path to the correct file and make sure that the referenced file has the same column and row formating. If one wanted to reference a new file you could change the code - file_to_load = os.path.join("resources", "file")- and replace file with the new one. One would need to make sure that the new file is properly stored in the the same folder. 

If there is additional data in the referenced file or if data is stored in a different format, changes would have to be made to the python script when reading header rows and adding up total votes. If for example an extra column of data with demographics on age or race is included and moves the candidate name to a different row, when referencing the candidate name we would need to make sure that the script is changed to match the adjustment. As seen in the screem shot of the script,

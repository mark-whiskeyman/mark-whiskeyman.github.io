# Enhancement_3 Databases
## Last Days Of the FyreBrund
### Capstone Project for CS-499
### Southern New Hampshire University
### August 11, 2020

## A. Briefly describe the artifact. What is it? When was it created?
The artifact I selected to enhance is my pet side project “Last Days of the FyreBrund” when the player plays an adventurous space captain lugging cargo all over the “verse”. The  Project was created about 5 years ago and I have been slowly incorporating what I have been learning in programming over this time.
Originally the artifact drew all its input from CSV or comma separated value files stored on disk. Adding a database can allow for importing different files, ensuring DMCA abilities to prevent piracy, globally tracked high scores, cloud saves and much more. 
## B. Justify the inclusion of the artifact in your ePortfolio. 
### Why did you select this item? 
This is a project I am passionate about yet challenging enough to provide a good view of my skill sets. When you love your work, you never work a day in your life. Since I love working on coding and specifically my projects, I am apt to find more energy to apply to this artifact. In addition to being passionate about the work I am doing, the technical skill required is above that of a novice. 
### What specific components of the artifact showcase your skills and abilities in databases? 
This iteration of artifact enhancement adds database functionality to the project. This involves connecting to a Mongo Database, adding data to the database from a csv file, checking for exceptions, then using aggregation, regex,  and find methods from the Mongo Java Driver to deliver user specified results to the screen.
To showcase my skillsets, the user is given the ability to select the data they wish to view, which in this case information pertaining to starships. Once the user selects the data, several processes may occur such as data aggregation, find methods, or regular expressions. The user is unaware of how the data is retrieved, and has a simplified user interface for ease of use. 
Aggregation, in aggregation the data is selected in the data pipeline, then piped to the driver which then displays it. Aggregation is a powerful tool that can be used to count items in a database, group items together, get sums of numbers, get the minimum value, get the maximum value, get the number of distinct items in the collection, and so forth (MongoDB, 2008). 
Find Methods. MongoDB supports a find function which is part of a CRUD or Create, Read, Update, Delete, package. Find is the read operation. Find allows data to be read from the database where specific conditions occur, such as greater than x, or less than y. Find does not necessarily return the values in a specified order (MongoDB, 2008). 
Regular Expressions or regex for short, enables searching that includes near matches. An example of how this is useful would be as follows: imagine a user is thinking of their favorite cartoon dog but does not know the whole name, they are searching a data base with cartoon names and know the name contains “oop”. Using a regular expression, they get the results: “Alley Oop”, “Betty Boop” and “Snoopy”. By knowing some of the data and using a regular expression the user was able to find the data they needed. 
In addition, to working with data, the program checks for exceptions using try-catch blocks. For instance, if the mongo server is shut down during gameplay, the user may still try to make an action involving the database. If the user does such an action, and the server is not running, Java will crash the program using a “MongoTimeoutException”, unless the exception is caught. Program crashes are frustrating for the user, adding exception handling is designed to handle things when the road gets bumpy to ensure a superior user experience. 
### How was the artifact improved?
The artifact was improved by the addition of a database. The user can now search the library of ships to see which enemies they might encounter, as well as which ships are purchasable to them. Although this is only a demonstration for what a database can do, it increases the amount of options in creating and playing the game. 
## C. Did you meet the course objectives you planned to meet with this enhancement in Module One? 
Course Outcomes: CS-499-04 use well founded and innovative techniques in software and database implementation.
I achieved the outcomes and objectives I had planned to meet. The use of the Mongo APIs was key in implementing the database design, as well as being able to handle errors and exceptions to prevent undesired program behavior. 
### Do you have any updates to your outcome-coverage plans?
I am +5 days from where I expected to be according to my timeline, but everything will be turned in on time in order to meet the deadline. All outcomes have been implemented according to plan. 
## D. Reflect on the process of enhancing and/or modifying the artifact. What did you learn as you were creating it and improving it? 
I learned that even with timeframes that I thought were ample, unexpected setbacks can occur. It is important to schedule in time for delays and the unexpected, but to also balance the workflow so that momentum keeps going. The key to success is organization and proper time management. A good strategy from experience is to schedule tasks for 70% of your working time, this allows time for the unexpected such as emergency emails, meetings, and fires that need to be put out. It also allows time to schedule the next day’s tasks and to get organized for what lies ahead. Coming into a day with a plan of action drastically reduces decision fatigue and increases productivity (Rao, 2018) (Pignatiello, Martin, & Hickman, 2020). 
### What challenges did you face?
There were, of course, the usual external challenges, comprising as Douglas Adams would put as “life, the universe, and everything” (1979). The programming challenges, however, were slightly less intense than previously anticipated. Since the Mongo driver has bult in APIs, the challenges were mostly in the syntax of the languages, finding and handling exceptions, and changing the default settings for a shorter timeout length. 
One of the major hindrances was switching to a newer Mongo driver  which messed up a bunch of API calls I had made, as the new mongo Driver had been restructured with different features and names. This entailed rewriting many lines of code. Luckily, my project is small, so it was a relatively quick fix. If this had been an enterprise level project it might have taken weeks or months to upgrade. This shows the care that must be taken when upgrading dependencies.
One exception I found was that if the Mongo Server was not running, an attempt to connect tot eh server was made,  then a Timeout exception would occur. It was only by accident that I found this exception and was thus able to handle it properly. I was then able to do more through testing to ensure coverage. 





## References
Adams, D. (1979). The Hitchhiker's Guide to the Galaxy. 

MongoDB. (2008). Aggregation. Retrieved from mongodb: https://docs.mongodb.com/manual/aggregation/

MongoDB. (2008). MongoDB CRUD Operations. Retrieved from mongodb: https://docs.mongodb.com/manual/crud/

Pignatiello, G. A., Martin, R. J., & Hickman, R. L. (2020). Decision fatigue: A conceptual analysis. Journal of Health Psychology, 123-135.

Rao, S. (2018, 02 03). Why Planning Your Day The Night Before Drastically Increases Your Productivity. Retrieved from mission.org: https://medium.com/the-mission/why-planning-your-day-the-night-before-drastically-increases-your-productivity-a5b5d39ff2bb#:~:text=With%20each%20decision%20we%20make,your%20deepest%20most%20meaningful%20work.



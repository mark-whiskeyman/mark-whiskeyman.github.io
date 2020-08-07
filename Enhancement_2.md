# Enhancement_2 Algorithms and Data Structures
## Last Days Of the FyreBrund
### Capstone Project for CS-499
### Southern New Hampshire University
### August 6th, 2020

## A. Briefly describe the artifact. What is it? When was it created?
	The artifact I selected to enhance is my pet side project “Last Days of the FyreBrund” when the player plays an adventurous space captain lugging cargo all over the “verse”. The  Project was created about 5 years ago and I have been slowly incorporating what I have been learning in programming over this time .
	The aspect I have incorporated is adding enemy encounters. The primary algorithm was an enemy decision-making algorithm, which uses nested if…else structure and Boolean operators to make a choice. 
## B. Justify the inclusion of the artifact in your ePortfolio.
### Why did you select this item?
	This is a project I am passionate about yet challenging enough to provide a good view of my skill sets. When you love your work, you never work a day in your life. Since I love working on coding and specifically my projects, I am apt to find more energy to apply to this artifact. In addition to being passionate about the work I am doing, the technical skill required is above that of a novice. 
### What specific components of the artifact showcase your skills and abilities in algorithms and data structure?
	This artifact contains many algorithms and extensive use of data structures. The main algorithm uses several nested ifs to figure out which of the three options an enemy should take. In the artifact update there are many other decisions to be made based on the data created. A simple algorithm included is if an encounter happens and the encounter is an enemy or friend.
### How was the artifact improved?
	Until this point players could not encounter enemies. A game without a challenge or a conflict will soon leave a player bored and disinterested. By adding in some action, the game is moved to a state that is almost ready to play. 
	The improvement also showcases my ability to solve problems using data structures and algorithms by incorporating more or each into production. I was able to improve code quality in the weapons area by simplifying the weapons design and weapon function calls by separating the weapon classifications. 
## C. Did you meet the course objectives you planned to meet with this enhancement in Module One? 
Planned course outcomes:
[CS-499-03] Solving problems with algorithms.
	I have accomplished CS-499-03 by my extensive usage of algorithms. I considered using if statements with multiple conditions such as 
IF X AND Y THEN: 
but to simplify the program nested if statements were chosen. Even though I am using Java the rules of the Zen of python tells us that “flat is better than nested” (Peters, 2004). Sometimes that is the case, but sometimes it is not. Nesting can be acceptable so long as nesting does not exceed 2 or rarely 3 levels. any nesting beyond two levels might consider a refactor. 
[CS-499-04] Use well founded and innovative techniques
	Here I have refactored code in my weapons design to implement better functionality. instead of running a long script such as makePurchase(Boolean isGun) with an internal decision structure, I have refactored the code into something like makeGunPurchase() and makeMissilePurchase() that use external calls to specific methods with shorter more readable code. 
### Do you have any updates to your outcome-coverage plans?
Everything is going according to plan. Soon I will begin work on the databases portion.
## D. Reflect on the process of enhancing and/or modifying the artifact. What did you learn as you were creating it and improving it? 
	What this iteration of artifact modification taught me is that the more types of bugs I encounter the better I become at fixing bugs. Consider something easy as a comparative. IF X == Y THEN DO SOMETHING. Using the comparative signs >,<,>=,<=, == are symbols built into many programming languages. The problem becomes when comparing objects. In Java a string is an object, so using a comparative operator does not work. The trick is that you must use a String objects .isEqual(String) method to compare the results. 
	The more I encounter this problem the faster I find it. During the last module, this issue cropped up and I did not find it for about an hour. This week I found the same issue in 10 minutes. This is also an issue that I will have to note is one of my weaknesses and look for it while I am coding. 
What challenges did you face?
	As expected, this assignment was slightly harder than the previous one, so it took longer to complete. Besides the above challenge of figuring out how to correctly compare objects in java, this modification had more components to it so more things could go wrong. Another challenge is knowing when the code is “good enough”. The driving desire it to add as much to the code as possible, but the goal of programming is to make it good enough to meet specifications. Sometimes it proves challenging to stop oneself from over doing it. 



### References
Peters, T. (2004). The Zen of Python. Retrieved from python.org: https://www.python.org/dev/peps/pep-0020/



# Enhancement_1 Software Design/ Engineering
## Last Days Of the FyreBrund
### Capstone Project for CS-499
### Southern New Hampshire University
### July 31, 2020

## A. Briefly describe the artifact. What is it? When was it created?
  The artifact I selected to enhance is my pet side project “Last Days of the FyreBrund” when the player plays an adventurous space captain lugging cargo all over the “verse”. The  Project was created about 5 years ago and I have been slowly incorporating what I have been learning in programming over this time.
	The specific aspect of the program I have enhanced is the ability to buy and sell cargo. 
## B. Justify the inclusion of the artifact in your ePortfolio. 
### Why did you select this item? 
  This is a project I am passionate about yet challenging enough to provide a good view of my skill sets. When you love your work, you never work a day in your life. Since I love working on coding and specifically my projects, I am apt to find more energy to apply to this artifact. In addition to being passionate about the work I am doing, the technical skill required is above that of a novice. 
### What specific components of the artifact showcase your skills and abilities in software development? 
  Specifically, incrementally building, functional decomposition, building on known good code, and Object-Oriented Design. With Object oriented design I am using an “is-a”, “has-a” relationship to ensure clean coding technique. 
The thought process here for Object Oriented Design is such:
I started with a player
A player has a bank account
A player has a ship 
A ship has weapons 
In my mind I use concreate ideas to program abstract elements.
The program also shows growth as a programmer, as my early classes used ideas that were ”creative” but ultimately backfired. 
### How was the artifact improved?
  So far, the artifact has been improved by allowing the player to buy and sell goods. Now that might seem like a remarkably simple implementation, but many factors must work together for the process to coalesce. Consider all the things we need for a player to make a purchase 
  player -> bank -> starship -> space -> planet ->merchant -> goods to sell. 
  These are just the types of objects. Once we have the goods to sell we have to figure out how to implement a quantity for the goods, such as do we add an attribute to the merchandise with getters and setters? Or do we rely on the merchant to keep track of the quantity on hand using a key value pair with products as keys and inventory quantities as values? There are other options too but these were the ones I considered. 
	Thus, even though there is a powerful base of classes that work together and have most of the pieces and the concept itself is easy to conceptualize, the reality is that there was still a considerable amount to figure out to ultimately solve the puzzle. Then as each piece of the puzzle is added in it must be tested to ensure for quality and correct results. In fact, to add the seemingly simple options of buying and selling cargo to the player required about 18 to 20 hours including writing the pseudocode, testing, debugging, and coding. 
## C. Did you meet the course objectives you planned to meet with this enhancement in Module One? 
I had planned to meet CS-499-01, CS-499-04, CS-499-05 Which is collaboration, using well founded solutions, and security mindset. 
CS-499-01 – Well documented and tested code to ensure the next programmer has an easy time working with my code. 
CS-499-04 – Methods are generally broken down into smallest possible parts with an attempt to keep a method at about one page in length. Due to extensive coding the method length sometimes exceeds one page. It may be technically possible to refactor code, but time limitations prohibit significant refactoring. 
CS-499-05 – There are only a handful of public options. Variables are set to private and utilize getters and setters if necessary. User input is severely limited and checked for proper type before processing. 
### Do you have any updates to your outcome-coverage plans?
Everything is going according to plan. I have however discovered a bug in my bank account class where for some reason it appears two separate accounts are being held. Each account works correctly but there is a disjoin. It seems like a simple variable misalignment. Although this is not within the scope of my original plan, I will work on solving this as time permits. Since other functions in the game rely on API calls to the banking class, I must be extremely careful that I do not change the public functions arguments or return values, only the internal operations. If I change anything, the user of my software must not be aware that anything has changed, their software must continue working as it has been. 
UPDATE 7-13-2020 I gutted and updated my Banking class. I added another class “Account” and now my bank has a series of accounts. This is useful because now I can add accounts as I desire. I can also use the accounts class for other things such as a high score (if desired) or keeping track of hit points in battles. I kept some of the bank’s same public APIs but only the ones currently in use in my code. This meant that most of my code did not have to be changed. Although this was not in project scope, I was able to update and improve code without incurring too much technical debt. 
## D. Reflect on the process of enhancing and/or modifying the artifact. 
### What did you learn as you were creating it and improving it? 
  I learned that time flies when I code what I love. I can spend 8 hours coding and it does not even feel like any time has passed. I learned that you can also find bugs in code you previously thought was good code. I found a few minor bugs and fixed them as I went and, found one major super-duper headache level bug within my banking class, that will take a little time to fix. 
	UPDATE 07-13-2020. The banking bug has been resolved. 
### What challenges did you face?
There were many challenges. Like, for instance how do you take the keys from a HashMap and insert them into an ArrayList. I spent a while messing with sets and iterators until I did some research and found:
ArrayList<String> playersGoodsTypes = new ArrayList<>(playersGoods.keySet());
One line of code instead of 20. 
	Or what if I need to sort an ArrayList of Objects by a trait of one of the objects?
Collections.sort(mdse, (o1,o2)-> o1.getName().compareTo(o2.getName()));
One line of code using a lambda expression. 
These were the easy challenges. There were other challenges that were quite puzzling. The most curious challenge was why when I counted a HashMap of Objects I received about 100 objects with a value of 1 each. The answer is that Each object was a new object. When I loaded cargo into the Ship’s cargo, I had created a new Merchandise Object for each unit of Cargo. Each object has its own unique identifier, or it references a unique memory address. So, unlike a string or an int or a double the object comparisons were not equivalent, so the HashMap thought each Object was a unique Object even if it had the same “name”. 


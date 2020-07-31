# mark-whiskeyman.github.io

## Hello! My name is Mark Whiskeyman!
Whatever I put my mind to I achieve. 
There is no obstacle I will not overcome.
What do you want me to achieve for your company? 

## About me:

In 2015 i decided to change my career by going back to school!
Right now I am an Assistant Manager 
Soon I will develop software. 
Later I will lead a software development team. 

# ePortfolio
## Project: Last Days of the FyreBrund
This is a project I've been working on in my spare time 
This is a text based menu space trading game 
The current iteration is build using Java and can be found here:
[git clone](https://recursivefunction@bitbucket.org/recursivefunction/fyrebrund.git)

### Code Review July 2020: 
### Last Days of the Fyebrund
[Screencapture CodeReview](https://drive.google.com/file/d/1OrZgqBEq__totvvLUANpjs12Zg_7lT2x/view?usp=sharing)

This is an example of a code review I've done For a game I'm working on.

### ENHANCEMENT_0 Orginal State.: 
### Last Days of the Fyebrund
The player can Do the Following 

|   **BANK**  |**SHIPYARD**|**WPNDepot**|**Navigate**|
|-------------|------------|------------|------------|
| Make Loans  | Buy Ships  | Buy Wpns   | *Select*   |
| Repay Loans | Sell Ships | Sell Wpns  |  Location  |
| Spend Money |            |            | *Change*   |
| Earn Money  |            |            |  Location  |

We still need to add The Ability to

[] Buy And Sell Cargo 

[] Have Enemy Encounters

[] Interact with A database

### ENHANCEMENT_1 Software design/Engineering.:
### Last Days of the Fyebrund
[FULL TEXT HERE](mark-whiskeyman.github.io/Enhancement_1.md)
  The first enhancement Added was for the user to buy and sell cargo. Although this seems simple there are many Software Engineering prinicples at use here. 
  
  Specifically, ideas such as 
  
  -Functional decomposition
  
  -Incrementally building
  
  -Building on known good code and 
  
  -Object-Oriented Design. 
  
  With Object oriented design I am using an “is-a”, “has-a” relationship to ensure clean coding technique. 
The thought process here for Object Oriented Design is such:

I started with a player

A player has a bank account

A player has a ship 

A ship has weapons...

After Enhancement 1 were are now here 

|   **BANK**  |**SHIPYARD**|**WPNDepot**|**Navigate**|**Cargo** |
|-------------|------------|------------|------------|----------|
| Make Loans  | Buy Ships  | Buy Wpns   | *Select*   |Buy Cargo |
| Repay Loans | Sell Ships | Sell Wpns  |  Location  |Sell Cargo|
| Spend Money |            |            | *Change*   |          |
| Earn Money  |            |            |  Location  |          |

We still need to add The Ability to

[] Have Enemy Encounters

[] Interact with A database



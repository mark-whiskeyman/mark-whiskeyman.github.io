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

# ePortfolio - Latest Updates are at the top 
## Project: Last Days of the FyreBrund
This is a project I've been working on in my spare time 
This is a text based menu space trading game 
The current iteration is build using Java and can be found here:
[git clone](https://recursivefunction@bitbucket.org/recursivefunction/fyrebrund.git)

### ENHANCEMENT_2 Algorithms and Data Structures.:
### Last Days of the Fyebrund
See the [FULL TEXT HERE](mark-whiskeyman.github.io/Enhancement_2.md)

The Second Enhancement deals with Algorithms and Data Structures.

In this addition to the artifact I have added enemy and friendly encounters.

This required major use of alogirthms including the use of IF...ELSE, SWITCH,
Random number generation, selection from arrays and lists, aggregating data,
guard conditions, TRY...CATCH, etc. 

Here's a simplified version:

1. Detemine current player level 
2. Select a ship from the ship file within one level of player
3. Determine if ship is enemy or friendly 
4. If enemy 
4.  -A Add weapons to the enemy based on level of enemy ship
4.  -B Decide turn order 
4.  -C Allow play to choose action on their turn
4.    --C.1 Fire Weapons
4.    --C.2 Launch Missiles 
4.    --C.3 Attempt bribe
4.    --C.4 Attempt retreat
4.  -D Enemy chooses action based on outcome probabilty of battle
4.    --D.1 If outcome favorable fire weapons 
4.    --D.2 if outcome less favorible fire missile
4.    --D.3 if outcome bad attempt retreat
4.  -E Exit battle if player or enemy is dead, retreating, bribed otherwise repeat at 4.B
5. If Friendly 
5. -A Display message of peace 
6. Exit Encounter 
  

After Enhancement 2 we are are now here 

|   **BANK**  |**SHIPYARD**|**WPNDepot**|**Navigate**|**Cargo** |**Encounters**
|-------------|------------|------------|------------|----------|-------------------|
| Make Loans  | Buy Ships  | Buy Wpns   | *Select*   |Buy Cargo | Encounter enemies |
| Repay Loans | Sell Ships | Sell Wpns  |  Location  |Sell Cargo|  -Fire on enemy   |
| Spend Money |            |            | *Change*   |          |  -Launch Missiles |
| Earn Money  |            |            |  Location  |          |  -Bribe enemy     |
|             |            |            |            |          |  -Attempt Retreat |
|             |            |            |            |          | Enemies can       |
|             |            |            |            |          |  -Fire weapons    |
|             |            |            |            |          |  -Attempt Retreat |
|             |            |            |            |          |Encounter friends  |


We still need to add The Ability to

[] Interact with A database


### ENHANCEMENT_1 Software design/Engineering.:
### Last Days of the Fyebrund
See the [FULL TEXT HERE](mark-whiskeyman.github.io/Enhancement_1.md)
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

After Enhancement 1 we are now here 

|   **BANK**  |**SHIPYARD**|**WPNDepot**|**Navigate**|**Cargo** |
|-------------|------------|------------|------------|----------|
| Make Loans  | Buy Ships  | Buy Wpns   | *Select*   |Buy Cargo |
| Repay Loans | Sell Ships | Sell Wpns  |  Location  |Sell Cargo|
| Spend Money |            |            | *Change*   |          |
| Earn Money  |            |            |  Location  |          |

We still need to add The Ability to

[] Have Enemy Encounters

[] Interact with A database

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


### Code Review July 2020: 
### Last Days of the Fyebrund
[Screencapture CodeReview](https://drive.google.com/file/d/1OrZgqBEq__totvvLUANpjs12Zg_7lT2x/view?usp=sharing)

This is an example of a code review I've done For a game I'm working on.



# Color Band Design Document

## Game Identity / Mantra: 
Very Colorful, Match Game, that you work against the time to collect the magical stars, that will help you to unlock, new and wonderful worlds. 

## Design Pillars:
- Accomplishment: the feeling you get when you beat the clock and get stars to unlock the next level
- Strategy: figuring out the best moves to make to get the largest color combo and setting yourself up for the next move.  
- Fast paced: trying to get the most points before time runs out. 

## Genre/Story/Mechanics Summary:
Game Play all the blocks feel the screen, once the blocks have falling the player will swipe rows or columns to create single color line, once the play creates the line it will collapse and new blocks will fill the empty space.

### Features: 

#### POSSIBLE POWER UPS:
- Block swap: So you can switch blocks for stars or to get more colors in the combination. one time use.
- Color Flood: Change the whole board to the same color. 
- Score Doubler: Doubles the score for your combo
- Colorizer: Turns grey blocks to color.
- Time Power Up: Use leftover time from when you beat the level to fill up a “Time bonus” bar and when it’s full you can use it as a power up to add time to your game clock in the level of your choice. 

#### PROGRESSION:
- Introduce the Grey Blocks, these can still move with rows and columns but can’t be part of the color chain. When you start to introduce the grey blocks, it is a set number of blocks but in the higher levels, as the time counts down, more grey blocks are added.
- Time gets shorter, the higher the level the player is the less time they have to collect points. 
- Stars, stars will appear in each level based on the score the player gets. So once a player reaches a certain score, the first star will appear when the player reaches the second and third marks the second and third stars will appear. 
- Using Stars, When the player selects a world to play it they are giving 10 levels to complete in the world, in the levels they can collect 3 stars per level, once the player collects these they can use them to unlock higher worlds. 

## Interface: 
- Player input would be touching the screen to swipe left right up or down to move columns and rows
- Player would also tap the screen to commit a color chain 

### Art Style: 
Include references to lots of images and games that have a similar aesthetic to what you're trying to achieve. 

- Tetris, 
- Rubix Cube, 
- BeJeweled, 
- Match 3 Type Games.

### Music/Sound: 
Include links to music and sound design similar to What you're trying to achieve. You can also list the emotional responses that the sound should invoke in the player.

- Angry Birds
- Happy Go Lucky
- Up Beat

## Development Roadmap / Launch Criteria: 
Platform: Google Play/Web. 	        Audience: 12 - 99 /Male & Female / Simple Games.

### Milestone 1:
	Demo App and Alpha Art complete - 11/31/2019

### Milestone 2:
	Alpha Integration App (in unity sim) - 12/15/2019

### Milestone 3:
	Side Load and test App (Android and Apple) - 12/31/2019

### Milestone 4:
	Publish to Store - 1/1/2020

### Milestone 5:
	Marketing - 1/1-29/2020

### Launch Day: 1/29/2020

## Minimum Viable Test: 
Platform: Google Play/Web. 	        Audience: 12 - 99 /Male & Female / Simple Games.

### Milestone 1 Test:
1. Load game on my Android phone (give model) Dev: PH-1 V10
2. Find 2 blue with a blue 1 square away
3. Slide 1 blue to match to 3 blues
4. View 'Nice Animation'
5. Approval M1 Game release:
	Dev Signoff:
	QA Signoff:
	Shapetrix Signoff: 


	
## Sudo Code: 

Gameboard Code Sections:
ArrayLayout.cs - Define gameboard grid array
NodePieces.cs - Helper library for dealing with all the node pieces
Point.cs - Helper library for dealing with node point functional calculations in grid
MovePieces.cs - Gameboard user actions and UI event updates
KilledPiece.cs - Dealing with removed matches recycling
Match3.cs - Gameboard main codeblock and scene UI events

### NOTES:
Need to change MovePieces to MoveBand
Need good explanation of MoveBand UX
Need to add ScoreMove.cs that handles scores
Need good explanation of scoring and time
Add menu’s, navigation and other screens

### Design Modifications:
Match3.cs line 264: Add MoveBand
MoveBand is taking The FlipPieces game action and using the function implementation event to move all the Pieces in the Band
FlipPieces has ‘out-of-bounds’ as holes… in the Bands world… the end is the beginning of the other side… this is going to take quite abit of changing in the checking loops… but the same action (I think) is wanted when matchs are removed

	
	

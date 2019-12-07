# Color Band Design Document

## Game Identity / Mantra: 
Very Colorful, Match Game, that you work against the time to collect the magical stars, that will help you to unlock, new and wonderful worlds. 

## Design Pillars:
- Accomplishment: the feeling you get when you beat the clock and get stars to unlock the next level
- Strategy: figuring out the best moves to make to get the largest color combo and setting yourself up for the next move.  
- Fast paced: trying to get the most points before time runs out. 

## Genre/Mechanics Summary:

### Genre

Game Play all the blocks feel the screen, once the blocks have falling the player will swipe rows or columns to create single color line, once the play creates the line it will collapse and new blocks will fill the empty space.

### Mechanics:

#### Clock:
- The clock is used to tell the player how much time they have to collect all the stars in the level. once the time is done the level     will end.
#### Scoring:
- Scoring is based on the collection of blocks collected in a chain.
- If player matches 3 of the same color blocks in a chain, he or she is rewarded with set value of points those points are added to the score.
- if player matches 7 or more then he or she is rewared with bouns points for completeing a more advance chain. 

#### Stars:
- Player needs three stars to complete the level. Stars are revealed to the player based on score. Example: first star would be revealed   at 200 points, next star at 600 points, and last star at 1200 points. 
- Player will collect 3 stars to unlock the next level, and once all the levels are completed in current world the total star count will   unlock the next world.
#### Worlds:
- Worlds are unlocked with progression by completeing the levels.

#### Levels:
- Levels are where the player will collect points and stars to unlock worlds. Players will not move on to the next level until they       collect 2 or more stars from the current level.

### Features: 

#### POWER UPS:
- Block Swap: So you can switch blocks for stars or to get more colors in the combination.
- Color Flood: Change the whole board to the same color. 
- Score Doubler: Doubles the score for your combo.
- Colorizer: Turns grey blocks to color.
- Extra Time: adds 10 seconds to the clock.

#### USING POWER UPS:

Each power up is based on a color match. so the power up would start empty then fill up as the player collects matches. Not based on     the amount of blocks in the chain. The power ups and the state of completion will also carry through to the next levels, and worlds.     the power ups will be displayed in the Game UI Menu at the bottom of the screen. The power up icons start as as power symbol then when they are filled the icon will switch to the corresponding power up graphic. When that happens the player can tap the icon to use the power up in the current level.  


  *need to make these variables public so we can play aroud with how many matches to make them fill up
  
  - Block Swap = Blue = 20 Matches to Fill
  - Color Flood = Orange = 30 Matches to Fill
  - Score Doubler = Pink = 10 Matches to Fill
  - Colorizer = Green = 15 Matches to Fill
  - Extra Time = Purple = 15 Matches to Fill
  
  
#### PROGRESSION:
*need to make the time variable and the grey block variable public so we can play around with with how long the level is and the amound and spread time of the grey blocks.

- Worlds 1-3 - Time Shortens
  - World 1: Levels - Set Time 2:00 mins
  - World 2: Levels - Set Time 1:45 mins
  - World 3: Levels - Set Time 1:30 mins
  
- Worlds 4-6 - Interduce Grey Blocks by Increasing the Amount of Them
  - World 4: Levels - Set Block Number: 10
  - World 5: Levels - Set Block Number: 15
  - World 6: Levels - Set Block Number: 20
  
- Worlds 7-9 - Grey Blocks Spread With Time
  - World 7: Levels - Set Start Spread Time 1:30 mins
  - World 8: Levels - Set Start Spread Time 1:45 mins
  - World 9: Levels - Set Start Spread Time 2:00 mins
  
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

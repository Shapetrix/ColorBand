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
- The clock is used to tell the player how much time they have to collect all the stars in the level. once the time is done the level will end.
#### Scoring:
- Scoring is based on the collection of blocks collected in a chain.
- If player matches 3 of the same color blocks in a chain, he or she is rewarded with set value of points those points are added to the score.
- if player matches 7 or more then he or she is rewared with bouns points for completeing a more advance chain. 

#### Stars:

#### Worlds:
- Worlds are unlocked with progression or bought thro in-game currency "Stars"

#### Levels:
- Levels are where the player will collect points and stars to unlock worlds, or buy new worlds with the stairs they earned.

### Features: 

#### POSSIBLE POWER UPS:
- Block Swap: So you can switch blocks for stars or to get more colors in the combination.
- Color Flood: Change the whole board to the same color. 
- Score Doubler: Doubles the score for your combo.
- Colorizer: Turns grey blocks to color.
- Extra Time: adds 10 seconds to the clock.
- Star Bouns: Add one star to help the player complete their star count for the level, or it could be a bonus star that is added to       their over all star count.

#### USING POWER UPS:

Each power up is based on a color match. so the power up would start empty then fill up as the player collects matches. Not based on     the amount of blocks in the chain. The power ups and the state of completion will also carry through to the next levels, and worlds.     the power ups will be displayed in the Game UI Menu at the bottom of the screen. Player will tap the power icon to use them in the       current level. and the power icon will show as "empty" transpartent so it looks deactivated, and then the fill process starts over       again.

  - Block Swap = Blue = 20 Matches to Fill
  - Color Flood = Orange = 30 Matches to Fill
  - Score Doubler = Pink = 10 Matches to Fill
  - Colorizer = Green = 15 Matches to Fill
  - Extra Time = Purple = 15 Matches to Fill
  - Star Bonus = Yellow = 25 Matches to Fill
  
  
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



# Development Roadmap / Launch Criteria: 
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
	 - Dev Signoff:
	 - QA Signoff:
	 - Shapetrix Signoff: 
	
## Sudo Code: 

Gameboard Code Sections:
- ArrayLayout.cs - Define gameboard grid array
- NodePieces.cs - Helper library for dealing with all the node pieces
- Point.cs - Helper library for dealing with node point functional calculations in grid
- MovePieces.cs - Gameboard user actions and UI event updates
- KilledPiece.cs - Dealing with removed matches recycling
- Match3.cs - Gameboard main codeblock and scene UI events

### NOTES:
- Need to change MovePieces to MoveBand
- Need good explanation of MoveBand UX
- Need to add ScoreMove.cs that handles scores
- Need good explanation of scoring and time
- Add menu’s, navigation and other screens

### Design Modifications:
#### Match3.cs line 264: Add MoveBand
MoveBand is taking The FlipPieces game action and using the function implementation event to move all the Pieces in the Band
FlipPieces has ‘out-of-bounds’ as holes… in the Bands world… the end is the beginning of the other side… this is going to take quite abit of changing in the checking loops… but the same action (I think) is wanted when matchs are removed

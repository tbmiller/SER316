# ReadMe for a Game

``` git log --oneline --all --graph --decorate ```
* ab7cd7b (hotfix, documentation) Fix randomInt to properly include max value in range
| * 1f23d1c (feature3) done
| * 3631e47 had to fix
| * c070288 got it done
| * f1097b6 started hint
|/  
| * e367776 (feature2) Implement max attempts logic and game over condition
| * 45aa640 Add maxAttempts constant and game over state
| * 5f95961 (dev) Add encouraging message for players
|/  
| * f48cf81 (feature1) Add version comment documenting quit feature
| * 9df380f Improve user feedback messages for guesses
| * f8dfe81 Add play-again loop functionality
| * 3bbc201 Add ability to quit game with negative number input
|/  
* 45767c4 (HEAD -> main) Initial Number guessing game

## Branches

### Main - 1 commit

This is where the initial game was committed

### Feature1 - 4 commits
Adds features for quit game and play again, improved guess feedback, updated Version to game from main branch

### Dev - 1 commit
Adds good luck message

### Feature2 - 2 commits
Adds max attempts and final game over with accompanying logic and 6 additional tests
Note: Feature2 final commit includes Dev commit as well, does not include Feature1 commits

### Feature3 - 4 commits
Adds hint system that can be toggled on/off and had logic for remaining turns and proximity to target number. Also includes comprehensive testing of feature. Does not include Feature1 or Feature2 changes

### Hotfix - 1 commit
Fixes the bug in the random integer generation for the target number. Does not include any other features.

### Documentation


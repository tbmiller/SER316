# ReadMe for a Simple Guessing Game

``` 
git log --oneline --all --graph --decorate 
```

* ab7cd7b (hotfix, documentation) Fix randomInt to properly include max value in range
* 1f23d1c (feature3) done
* 3631e47 had to fix
* c070288 got it done
* f1097b6 started hint
*  
* e367776 (feature2) Implement max attempts logic and game over condition
* 45aa640 Add maxAttempts constant and game over state
* 5f95961 (dev) Add encouraging message for players
*  
* f48cf81 (feature1) Add version comment documenting quit feature
* 9df380f Improve user feedback messages for guesses
* f8dfe81 Add play-again loop functionality
* 3bbc201 Add ability to quit game with negative number input
*  
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
Poor commit messages

### Hotfix - 1 commit
Fixes the bug in the random integer generation for the target number. Does not include any other features.

### Documentation

Learning summary - I learned through MUCH trial and error how merge, rebase, cherry-pick, and squash can be powerfully used to leverage version control on a project. Merge allows the user to put two branches together while preserving their histories, while rebase brings two branches together and completely merges their histories, making a linear history. I used cherry-pick to pull one specific file from branch and squash allowed me to condense down multiple commits with poor messages into a single, packaged commit that fully addressed the scope of the feature with its commit message.
I had some experience with using git commands before, but this assignment truly strained that knowledge and pushed me to learn a lot more. I made quite a few mistakes, including accidentally deleting code during the rebase of feature2 onto dev to the point that I had to look at the git history on a different computer in order to recover the lost lines of code! (If there is an easier way of doing this locally, I hope to discover it soon). I feel much more comfortable with git after completing Task2.

My observations for each feature are listed in the Branch descriptions.

I would try to default to using the cherry-pick, merge, and squash strategies as much as possible because they had the most simple conflict resolution processes. Dealing with multiple streams of input into the merge file during the rebase caught me off guard and I made a big mistake that I had to walk back. However, I definitely understand the power and purpose of using rebase to bring features into a development stream once they are ready to become a part of the projects linear history and need no further tweaking, hopefully. I look forward to using all these tools this semester as this assignment has been one of the more immersive assignments that I have had in this program and was quite a lot of fun.


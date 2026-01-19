## Branch Structure

- **main**
    Has initial number guessing game. 

- **dev**
    Feature branches merged with dev after updated and tested.

- **feature1**
    Add ability to quit game with negative number input.
    Add play-again loop functionality.
    Improve user feedback messages for guesses.
    Add version comment documeting quit feature.

- **feature2**
    Add maxAttempty constand and game over state.
    Implement max attempts logic and game over condition.

- **feature3**
    Added hints and updated fixes to it.

- **hotfix**
    Fix randomInt to properly include max value in range.

- **documentation**
    Has README and documentation for branch sturcture and features.


## Learning Summary

- **Differences between merge, rebase, squash, and cherry-pick**
    Merge would combine branches when trying to get updated code from a branch to another. 
    Rebase would have commits on a new base to have a linear history.
    Squash would combine commits into one, to make it clearer.
    Cherry-pick would copy a commit to another branch with using the hash.

- **What I observed in the git history for feature1 vs feature2 vs feature3**
    feature1 shows merge commits we made.
    feature2 has a linear history, since we rebased.
    feature3 shows in dev with commits merged after squashing.

- **When I would use each strategy in real projects**
    I would use merge when working on a project with other team members and needed to merge my branch with a dev.
    I would use rebase to clean up my branch before merging.
    I would use squash to remove commits that are repeated or excessive.
    I would use cherry-pick when trying to add a fix without having to merge a branch.


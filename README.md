# git-test


 * [x] Create a few commits in  `master`.
 * [x] Create `develop` branch off `master`.
 * [x] Create a feature branch `feature/f1` off `develop`.
 * [x] Do a few commits on the feature branch `feature/f1`
 * [x] Submit a PR for the feature against develop branch.
 * [x] Approve the PR, SQUASH AND MERGE `feature/f1` into `develop`.
 * [x] Start a new feature branch `feature/f2`.
 * [x] Do a hotfix branch off master `hotfix/h1`.
 * [x] Make a couple of commits on the hotfix branch `hotfix/h1`.
 * [x] Submit a PR for hotfix branch `hotfix/h1` against `master`.
 * [x] Approve the PR, SQUASH AND MERGE `hotfix/h1` into `master`.
 * [ ] <strike>Create a PR to merge `master` into `develop`.</strike>
 * [ ] <strike>Approve the PR and merge (no squash; but also there is no squash needed)</strike>
 * [x] If there is a conflict, PR via GitHub won't work as expected. You have to merge `master` into `develop` on your own machine, resolve the conflict, push merge commit.
 * [x] Now is time for the big release, so we create a PR for `develop` into `master`. Because we have merged `master` into `develop`, there
       are no conflicts now. This PR is NOT SQUASHED, NOT REBASED. It is merged with a merge commit.
 * [x] `develop` and `master` are now the same.

There are 4 different merges. If you think one is arguing about squashing in all those situations then you are arguing with an imaginary opponent.

 1. `hotfix/h1 > master` - yes, please SQUASH your tiny little commits
 2. `feature/f1 > develop` - yes, please SQUASH your tiny little commits
 3. `master > develop` - no squash, merge commit with conflicts resolved
 4. `develop > master` - no squash, merge commit. No conflicts!
 

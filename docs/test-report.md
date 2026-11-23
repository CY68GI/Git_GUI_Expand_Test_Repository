# Git GUI Expand Main-Function Smoke Report

Tested against a temporary clone of this repository.

- Open repository, branch detection and Git status
- Tracked/untracked directory listing and repository statistics
- Add, list and remove a Git remote configuration
- Copy, move and rename files through Git
- Stage all files and create a commit
- Create, switch, rename and delete a local branch
- Create a stash including untracked files, list it and pop it
- Clear Git metadata in an isolated copy after confirming there were no remotes
- Verify working files survived metadata cleanup

The original test repository remains initialized on `main` with no remote configured.
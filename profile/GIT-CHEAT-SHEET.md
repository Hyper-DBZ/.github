# Git Cheat Sheet

## Getting Started

#### Clone a repository

```bash
git clone <repo_url>
```

#### Create a new repository

```bash
git init
```

## Making Changes

#### Check repository status

```bash
git status
```

#### Add files to staging

```bash
git add <file>
```

#### Commit changes

```bash
git commit -m "<message>"
```

#### Commit changes to a specific file

```bash
git commit -m "<message>" <file>
```

#### Commit and add a file in one step

```bash
git commit -am "<message>" <file>
```

#### Amend the last commit

```bash
git commit --amend
```

#### View commit history

```bash
git log
```

#### View commit history with one line per commit

```bash
git log --oneline
```

#### Restore a file to its last committed state

```bash
git restore <file>
```

## Branching & Merging

#### Create a new branch

```bash
git branch <branch_name>
```

#### Switch to a branch

```bash
git checkout <branch_name>
```

> or

```bash
git switch <branch_name>
```

#### Create and switch to a new branch

```bash
git checkout -b <branch_name>
```

> or

```bash
git switch -c <branch_name>
```

#### Merge a branch

```bash
git merge <branch_name>
```

## Working with Remote Repositories

#### Add a remote

```bash
git remote add <remote_name> <remote_url>
```

#### Fetch from a remote

```bash
git fetch <remote_name>
```

#### Push to a remote

```bash
git push <remote_name> <branch_name>
```

#### Push with upstream

```bash
git push --set-upstream <remote_name> <branch_name>
```

#### Pull from a remote

```bash
git pull <remote_name> <branch_name>
```

## Handling Changes

#### View changes

```bash
git diff
```

#### Stash changes

```bash
git stash
```

#### Apply stashed changes

```bash
git stash apply
```

#### Pop the top stash

```bash
git stash pop
```

#### Clear all stashes

```bash
git stash clear
```

#### Discard all changes

```bash
git reset --hard
```

## Resolving Conflicts

#### View conflicts

```bash
git status
```

> or

```bash
git diff
```

#### Abort a merge

```bash
git merge --abort
```

#### Commit after conflict resolution

```bash
git add <conflicted_file>
git commit
```

## Working with Tags

#### Create a tag

```bash
git tag <tag_name>
```

#### List all tags

```bash
git tag
```

#### Push a tag to a remote

```bash
git push <remote_name> <tag_name>
```

## Additional Commands

#### Delete a branch

```bash
git branch -d <branch_name>
```

#### Delete a remote branch

```bash
git push -d <remote_name> <branch_name>
```

#### Rebase

```bash
git rebase <branch_name>
```

#### Cherry-pick a commit

```bash
git cherry-pick <commit_id>
```

## Useful Options

#### Verbose mode:

Add `-v` or `--verbose` to most commands for more detailed output

## Git Configuration

#### Global Git config

```bash
git config --global <key> <value>
```

#### Local Git config

```bash
git config <key> <value>
```

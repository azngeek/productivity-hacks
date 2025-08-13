# Git Worktree

Create new worktree from existing branch

```
git worktree add <WORKTREE-PATH> <BRANCH>
# git worktree add ../bugfix feature/ticket-123
```

Create new branch and its worktree

```
git worktree add -b <BRANCH> <WORKTREE-PATH>
```

List current worktrees

```
git worktree list
```

Delete a worktree

```
git worktree remove <WORKTREE-PATH>
```

Clean up worktrees metadatas

```
git worktree prune
```

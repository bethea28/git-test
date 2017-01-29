# Mastering Git

## Discussion

Read: [Branches Part 1 (Ry's Git Guide)](http://rypress.com/tutorials/git/branches-1)

- What is the 'working directory' (in context of git)?
- What is the difference between a staged and committed snapshot?
- What are git 'development branches?'
- What is the HEAD?
- How do you create and merge a branch?
- How many different branches do you need?

## Branching Demo
- Creating a branch (`git checkout -b <branch-name`)
- Merging a branch  (`git merge <branch-name>`)

## Github Best Practices
- Commit often - think of commits as 'checkpoints' in old video games
- Write clear commit messages, and keep them consistent
- Always keep master completely clean, stable, and functional (aka 'production ready')
- Create a 'development' branch that serves as your main branch during developement
- Create new 'feature' branches for new features
- Merge feature branches into development branch and test before merging to master
- Merge development branch into master (never merge a feature branch directly to master)
- Always create Pull Requests (aka PRs) instead of just pushing straight to github
- Never merge your own PRs
- Only pull to master branch (?)

## Github Issues From The Command Line

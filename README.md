# Mastering Git

Mastering git and github is a critical part of any developer's success. Let's look at some best practices for mastering git/github workflow.

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
- Pushing a branch to github (`git push <remote-name> <branch-name>`)

## Github Workflow Best Practices
Read: [Introducing GitFlow](http://nvie.com/posts/a-successful-git-branching-model/)

(^^this article is an example of a GitHub workflow that some professional developers use - it's more complicated of a workflow than we'll need for this project, but it's still good to get an idea of professional workflows)

Commong GitHub best practices:

- Commit often - think of commits as 'checkpoints' in old video games
- Write clear commit messages, and keep them consistent
- Always keep master completely **stable** (aka 'production ready')
- Create new 'feature' branches for new features
- Always create Pull Requests (aka PRs) instead of just pushing straight to github
- Never merge your own PRs
- Only pull to master branch - never pull to a feature branch

## Managing Github Issues + PRs From The Command Line
- Install [Node GH](https://github.com/node-gh/gh)
- `gh help` List all available commands
- `gh help -a` List all available subcommands
- `gh is` List all issues
- `gh is '<issue text>'` Open an issue
- `gh is <number> --close` Close an issue
- `gh pr --submit <github-username> --branch '<branch to submit PR to>'` Open a pr
- `gh re` open github repo in browser

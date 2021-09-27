Getting git - git it?
===
This repo was developed by Bernie Green and used during a presentation to *CodeCademy - Hong Kong Chapter* over two separate sessions.
- Session 1: September 28, 2021
- Session 2: October 26, 2021
---
# Overview
- [Essential Questions](#essential-questions)
  - [git](#git)
  - [GitHub](#github)
  - [Markdown](#markdown)
- [Commands, definitions, and examples](#commands)
- [Resources](#resources)
  - [Markdown](#markdown)
  - [Version Control](#version-control)
  - [Other](#other)
- [Credit](#other)
---
## Essential Questions
### git
- What is git? ...a *version control* system which allows the practice of tracking and managing changes to software code [*__source__*](https://www.atlassian.com/git/tutorials/what-is-version-control)
- Why use git?
- How to use git?
- When to use git?

### GitHub
- What is GitHub? 
- Why use GitHub?
- How to use GitHub?
- When to use GitHub?

### Markdown
- What is Markdown? 
- Why use Markdown?
- How to use Markdown?
- When to use Markdown?

---
## Commands:
git *__- access to git commands__*
```bash
git
```
git clone url *__- clones repo repository from GitHub based on url__*
```bash
git clone https://github.com/bgreen280/git-demo.git
```
git status *__- shows current status (un/staged) of all files in repository__*
```bash
git status
```
git add filename1 filename2 ... filenameN *__- add one or more files to staging area__*
```bash
git add filename1 filename2 filename3 filename4
```
git commit *__- commit files to repository__*
```bash
git commit
```
git diff *__- shows differences between un/staged__*
```bash
git diff
```
git log *__- displays all commits__*
```bash
git log
```
git checkout HEAD filename *__- gets rid of changes in working directory__*
```bash
git checkout HEAD filename
```
git reset HEAD filename *__- unstages files in staging area__*
```bash
git reset HEAD filename
```
git reset commit_SHA *__- resets to a specific commit based on first 7 chars of SHA__*
```bash
git reset commit_SHA
```
git push *__- upload repo to GitHub__*
```bash
git push
```
#### Bonus Commands
touch filename.ext *__- creates a new file in current directory__*
```bash
touch new-file.txt
```
rm filename.ext *__- deletes file from current directory__*
```bash
git init
```
git init *__- initialize git repository on local device__*
```bash
git init
```
---
## Resources
### Markdown
1. [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
1. [Alt Markdown Cheatsheet](https://gist.github.com/bradtraversy/547a7bbf35ffba1561706e161a50b05a)
1. [Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown)
1. [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
### Version Control
1. [Working with GitHub in VS Code](https://code.visualstudio.com/docs/editor/github)
1. [What is version control?](https://www.atlassian.com/git/tutorials/what-is-version-control)
1. [Get Up and Running](https://www.youtube.com/playlist?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-) *YouTube Playlist*
1. [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
1. [git cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)
### Other
1. [How to write a good README](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
1. [Next Level GitHub Profile README](https://www.youtube.com/watch?v=ECuqb5Tv9qI&t) *CodeSTACKr YouTube Video*
---
##### Credit: [Codecademy: Full-Stack Engineer - Git and GitHub, Part 1](https://www.codecademy.com/learn/paths/full-stack-engineer-career-path)

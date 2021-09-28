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
- What is git? ...a *version control* system which allows the practice of tracking and managing changes to software code - [*__source__*](https://www.atlassian.com/git/tutorials/what-is-version-control).
- Why use git? ...it makes project management way easier...because development history is tracked and organized.
- How to use git? ...start with the below commands!
- When to use git? ... anytime you're developing a new coding project!

### GitHub
- What is GitHub? ...a provider of Internet hosting for software development and version control using Git - [*__source__*](https://www.wikiwand.com/en/GitHub).
- Why use GitHub? ...to collaborate with others and share your code with the world.
- How to use GitHub? Start with creating your first repo! 
- When to use GitHub? Whenever you have a project worthy of sharing online or requires remote collaboration.

### Markdown
- What is Markdown? ...a lightwieght markup language for creating formatted text using a plain-text editor - [*__source__*](https://www.wikiwand.com/en/Markdown).
- Why use Markdown? ...its easily read and formatted in any 'ole web browser
- How to use Markdown? Check out the resources below!
- When to use Markdown? You're first README! Or just as a notebook throughout the day or during class :)

---
## Commands:

```bash
# git
# access to git commands
git

# git clone url
# clones repo repository from GitHub based on url
git clone https://github.com/bgreen280/git-demo.git

# git status
# shows current status (un/staged) of all files in repository
git status

# git add filename1 ... filename3 ... filenameN
# add one or more files to staging area
git add filename1 filename2 filename3

# git commit -m "message"
# commit files to repository
git commit -m "created new files"

# git diff
# shows differences between un/staged
git diff

# git log
# displays all commits
git log

# git checkout HEAD filename
# deletes file changes in working directory
# use with caution, cannot be undone
git checkout HEAD filename

# git reset HEAD filename
# unstages files in staging area
# use with caution, cannot be undone
git reset HEAD filename

# git reset commit_SHA
# resets to a specific commit based on first 7 chars of SHA
# use with caution, cannot be undone
git reset commit_SHA

# git push
# upload repo to GitHub
git push
```

### Bonus Commands
```bash
# touch filename.ext 
# creates a new file in current directory
touch new-file.txt

# rm filename.ext 
# deletes file from current directory
rm new-file.txt

# git init 
# initialize git repository on local device
git init

# git command --help
# display docs for specific git command
git log --help # press 'q' to exit

# git show HEAD
# shows current commit's log output + committed file changes
git show HEAD
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
#### Credit: [Codecademy: Full-Stack Engineer - Git and GitHub, Part 1](https://www.codecademy.com/learn/paths/full-stack-engineer-career-path)

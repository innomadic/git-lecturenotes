# Source Code Control

* Manage source code

# Examples

* Git 
* Mercurial
* Subversion
* Bazaar
* Visual SourceSafe
* CVS

# Problems to be solved

1. Collaboration
2. Versioning
3. Backup
4. History

# Versioning

1. Create a release on Jan-1 21.1
2. After 1-Jan, we collect requirements for 21.2

main:
---21.1---x---y----b1---X---Y---21.2--z--a--c
    |              ^             |
21.1|---b1---21.1.2|             |
                           21.2  |---b2--

# Collaboration

main:
---21.1         |X        |Y-----21.2
    |           ^         ^
   x|--x1--x2--x3         |
   y|------y1---y2---y3---Y

# History

* See past changes
* Helps to identify bugs

# Git 

* Made by Linus Torvalds
* Most popular version control tool

# Terms

* Repository - like a folder, but with extra data like history, the branches, etc.
* Commit - a batch of changes that are stored together, usually with a common purpose

# Git Workflow

1. Stage your changes `git add`
2. Commit your staged changes `git commit -m "Fixes #45687"`
3. Optional:  push your changes to the server `git push`

# Other commands 

1. Check the status of repository `git status`
2. View the history `git log`
3. Start a new repository `git init`

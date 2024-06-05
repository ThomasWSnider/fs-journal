## Git
### What is Git?
* Control System
  + tracks content
  + used to store code
* Version Control
  + code in Git changes as more is added
  + multiple developers can be working in parallel
  + Git tracks the history of changes 
  + branches and merges
* Distributed Version Control
  + remote repo's stored on server
  + local repo's stored on individual computer
  +full code is with every developer

### Why Use Git?
* Coordination
  + projects usually involve multiple developers working in tandem
  + Git prevents code conflicts
* Changing Requirements
  + if requirements change, older versions of the code are not lost
* Branching
### Staging and Committing Code
#### Staging
Committing code = adding code to a **LOCAL** repository

You must stage a file in order for it to be committed

Command for staging a file = *git add [FILE NAME]*

For multiple files = *git add [FILE 1] [FILE 2] [FILE 3] [ETC]*

To add all files in folder = *git add .* (Make sure you are okay with all files in the project being committed before doing this)

#### Committing
To commit a file = *git commit -m [COMMIT MESSAGE]*
A commit message is a relevant message pertaining to the code changes done in a commit

### Status
Git status will tell info about what files are changed and which files are in the staging area

To see Git status = *git status*!SECTION

### Log 
Git log prints all previous commits up to now

Git log command = *git log*

Log show author, date, and message for each commit

### Branches
Git commits into master branch by default

* What is a Branch?
  + A branch is a pointer to the latest commit in the Git Repo.

* Why do I need multiple branches?
  + Multiple branches support multiple parallel developments

![Branches Chart](https://cdn-media-1.freecodecamp.org/images/sww3mboJ61C4kpLWlQYHnHWvrjX8p--VMui2)

After Commit 2, there were two separate developments happening, each inside its own branch

### Create a New Branch

Create new branch command = *git branch [BRANCH NAME]*

To switch to other branch = *git checkout [BRANCH NAME]*

List all branches in local repo = *git branch*

### Merging

To merge code from two branches
1. enter master branch
2. command = *git merge test*
There will be conflicts when a merge is performed
Learning to resolve these conflicts will come with experience

## Remote Git Repository
A developer will work in their local repo, but they will eventually push their code into a remote repo

Once code is in the remote repo, other devs will be able to see and modify it

![RepositoryChart](https://cdn-media-1.freecodecamp.org/images/O-6UdGYVsEjM-oJmtJ5KQpQnXIBOCZoB22X1)

### GitHub

To point local to remote repo = *git remote add origin [repo url]*

# Git Push
To push all code from local to remote = *git push -u origin master*  
This will push all code in local master to the remote master

# Git Pull
Used to pull latest changes from remote into local. Git pull is necessary because the remote repo code is being updated continuously

git pull = *git pull origin master*!SECTION

# Git Clone
Used to clone existing remote repo into computer

git clone = *git clone [repo url]*
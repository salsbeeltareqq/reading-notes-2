[Home](https://sayefdeen.github.io/reading-notes/home)

# Git Tutorial.

## 1. what is Git?

Git is an example of **version controll system** that make you controll your whole project and the changes you did on it easily, make you track your cahnges my commiting them in your GitHub account, you can push any changes, clone any repositories , and by repositories i mean a folder that contain all the project files, also it make your data had a less chance to get lose during your work.

## 2. WorkFlow on Git.

### 2.1 Local Repository Structure.

The local Git repository has three components:

    Working Directory: The actual files reside here.
    Index: The area used for staging
    Head: Points to the most recent commit

![WorkFlow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

### 2.2 Saving Changes 

All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

**Tracked:** Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

**Untracked:** Untracked files were not in the last snapshot and do not currently reside in the staging area.

After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.

### 2.3 The Life Cycle of File Status 


    After you edit a file, Git flags it as modified because of changes made after the previous commit.
    You stage the modified file.
    Then, you commit staged changes.

![Life Cycle](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)


*Table that contain some of git command line*

| Command     | Usage |
| ----------- | ----------- |
| git clone (repository Link)|  Clone the repository at your local machine |
| code .     | Open you default code editore with the files in the cloned repository |
| git status|  Gives you status of all your files (red im modified) |
| git add .|  add all your files to your repository (color will be green) |
| git add (file name)|  add (file name) to your repository (color will be green) |
| git commit -m "Massage"|  add a massage to before pushing |
| git push origin master |  push the the changes in you local to GitHub account |

**Note:** Make sure to use git command to type the word (git) before any command line.

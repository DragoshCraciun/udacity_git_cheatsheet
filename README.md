# Udacity-Git-Cheatsheet

This is a "cheat sheet" of all the Git commands used in the Udacity course:
[How to Use Git and GitHub](https://www.udacity.com/course/how-to-use-git-and-github--ud775).

<h3>Some Useful Console Commands</h3>

Command | Description | Options
------------ | ------------- | -------------
`cd <directory path>` | "change directory" -<br>changes the folder you are operating in. | `~` - to home directory<br>`../` - up one folder
`mkdir <folder name>` | "make directory" -<br>creates a new folder. |
`pwd` | "print working directory" -<br>displays the file path of the folder you are working in. |
`ls` | "list" -<br>lists files and folders in the folder you are working in | `-a` - list hidden files too
`touch <filename>` | creates a new file |

<h3>Setting Up Your Workspace</h3>

* Save [this file](https://raw.githubusercontent.com/git/git/master/contrib/completion/git-completion.bash) in your home directory with the name `git-completion.bash`.
* Save [this file](https://raw.githubusercontent.com/git/git/master/contrib/completion/git-prompt.sh) in your home directory with the name `git-prompt.sh`.
* Download `bash_profile_course` [here](https://www.udacity.com/api/nodes/3341718587/supplemental_media/bash-profile-course/download?_ga=1.37232743.672083044.1467344711).
If you already have a file in your home directory named `.bash_profile`, copy the content from `bash_profile_course` and paste it at the bottom of `.bash_profile`. Otherwise, move `bash_profile_course` to your home directory and rename it to `.bash_profile`.

<h5>Making Git configurations</h5>
Run the following Git configuration commands. The first one will need to be modified if you are using a text editor other than Sublime, or if Sublime is installed in another location for you. See this page for the correct command for a couple of other popular text editors. For any other editor, you'll need to enter the command you use to launch that editor from the terminal.

>`git config --global core.editor "atom --wait"`
>`git config --global push.default upstream`
>`git config --global merge.conflictstyle diff3`

<h2>Lesson 1 - Navigating a Commit History</h2>

Command | Description | Options
------------ | ------------- | -------------
`git clone` |  |
`git log` |  |
`git diff` |  |
`git checkout` |  |

<h2>Lesson 2 - Creating and Modifying a Repository</h2>

Command | Description | Options
------------ | ------------- | -------------
`git init` |  |
`git status` |  |
`git add` |  |
`git reset` |  |
`git branch` |  |
`git merge` |  |
`git show` |  |

<h2>Lesson 3 - Using GitHub to Collaborate</h2>

Command | Description | Options
------------ | ------------- | -------------
`git push` |  |
`git pull` |  |
`git remote` |  |
`git fetch` |  |

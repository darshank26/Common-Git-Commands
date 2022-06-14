# Common-Git-Commands

Git is the free and open source distributed version control system that's responsible for everything GitHub related that happens locally on your computer. Git commands, what each one means, and how to use them. Our motto is that this makes Git easier to use on day to day bases.


## Setup
Configuring user information used across all local repositories.

| Command | Description |
|--------- | ----------- |
| `git config --global user.name “[firstname lastname]”` | This command set user name commits will be from on a local computer. |
| `git config --global user.email “[valid-email]”` |  This command set user email that will be associated with each commits <br/>  from on a local computer. |
| `git config --global color.ui auto` | This command is use to set automatic coloring of Git Command line for easy reviewing |

##  Initializing and Cloning
Configuring user information, initializing and cloning repositories.

| Command | Description |
|--------- | ----------- |
| `git init` | This command convert current directory to Git Repository.  This is the first step in creating a git repository |
| `git clone [url]` | This command is use to clone remote git repository on the local system . Git will create a directory  locally with  all files <br/> and repository history.|

## Stagging and Snapshot
Following command is used for git stagging and snapshot.
| Command | Description |
|--------- | ----------- |
| `git status` | This command is used to the list of modified files in current working directory, that will be staged for your next commit.|




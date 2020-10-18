### Basic Git Commands
#### 1. Getting a Git Repository
* You can take a local directory that is currently not under version control, and turn it into a Git repository.
e.g.: **git init sampleProject**
* You can clone an existing Git repository from elsewhere.
e.g.: **git clone https://github.com/libgit2/libgit2**
#### 2.Git log
The Git Log tool allows you to view information about previous commits that have occurred in a project. The simplest version of the log command shows the commits that lead up to the state of the currently checked out branch. These commits are shown in reverse chronological order (the most recent commits first).
e.g.: **git log**
* **--pretty** option will change the log output to formats other than the defaults
e.g.: **git log --pretty=oneline**

|Option|Description|
|------|-----------|
|**--n**|Show last n number of commits|
|**--p**, **--patch**|Show the difference introduced in each commit|
|**--since**, **--after**|Limit the commits to those made after the specified date|
|**--until**, **--before**|Limit the commits to those made before the specified date|
|**--author**|Only show commits in which author entry matches the specified string|
|**--committer**|Only show commits in which committer entry matches the specified string|
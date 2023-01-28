# GIT CHEAT SHEET 📝

> Git is a version control system used to track changes in computer files and coordinate work on those files among multiple people. It is commonly used for software development, but can be used to track changes in any set of files. It allows users to easily keep track of modifications, revert to previous versions, and collaborate with others.
> Here is the cheat sheet consisting of some key commands

---

## 1. Git Installation

> 🔗 **[Download Git for all Platforms]("https://git-scm.com/downloads)**

---

## 2. Git Setup & Config

To configure user information used across all local repositories.

> Set a name: <br> **`git config --global user.name “[firstname lastname]”`**

> Set an email address: <br> **`git config --global user.email “[yourEmail@example.com]”`**

---

## 3. Git Initialization and Setup

> To initialize an existing local directory as a Git repository: <br> **`git init`**

> Fetching/downloading an entire repository from a hosted location via URL _(say: Github)_: <br> **`git clone [URL]`**

---

## 4. Git Staging:

Working with Git Staging area:

> Shows status like modifications in files and staging status also: <br> **`git status`**

> Add file to next commit: <br> **`git add [fileName]`** <br>
> Add all files to next commit: <br> **`git add .`**

> Redo/unstage a file that are already added: <br> **`git reset [fileName]`**

> To show difference of changes but not yet staged: <br> **`git diff`**

> To commit the staged files: <br> **`git commit -m "[commitment message of your choice]"`**

---

## 5. Branching and Merging

Help for multiple peoples working on the same project, to keep them isolated and integrate later on.

> list all the branches: <br> **`git branch`**

> create a new branch at present commit: <br> **`git branch [branchName]`**

> switching between the branches: <br> **`git checkout branchName`**

> To merge specific branch to current/working branch:<br> **`git metge [branch]`**

> To look all the commits in current branch: <br> **`git log`**

---

## 6. Share and Update

Fetching updates from another existing repository and updating local repository to hosted location _(eg: Github)_.

> To add git URL: <br> **`git remote add [aliasName] [URL}`**

> Fetching all branches from git remote: <br> **`git fetch [aliasName]`**

> To merge a remote branch to current branch for update: <br> **`git merge [aliasName]/[branch]`**

> Pushing local project to remote branch _(say: Github's repo branch)_: <br> **`git push -u [aliasName] [branch]`**

> To fetch and merge any commits from remote branch: <br> **`git pull`**

---

## 7. Rewrite History

To clear history, reset amd rewrite:

> apply any commits of current branch ahead of specified one: <br> **`git rebase [branch]`**

> Clear staging area and rewriting: <br> **`git reset --hard [commit]`**

---

**© SYYNCC**

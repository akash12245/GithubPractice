# GithubPractice

# Cloning

There are 3 ways to clone a Github repository :- HTTPS, SSH, Github CLI

> HTTPS

We clone the repository by using the command `git clone` followed by the URL of the repository.

```
git clone https://github.com/akash12245/GithubPractice.git
```

## Git Hidden Folder

There is a hidden folder `.git` which tells you that your project is a git repo.

If we want to create a git repo in a new project, we create a new folder and initialize it, using the command `git init`

```
git init
```

# Commits

When we want to move the changes from Stagged state to the Commited state, we use the following command.

```
git commit
```

Wehn we want to commit and use the command, this will open up the commit edit message in the editor of choice.


# Status

Git Status shows you what files will or will not be commited.

```
git status
```

# Add
When we want to stage changes that will be included in the comit staged.

To add single file from Unstaged state to Stagged state. We use the command `git add` followed by the filename with extension of the file.

> git add README.md

To add all the files from Unstaged state to Stagged state. We use -

> git add . 

```
git add README.md
git add . 
```

# Reset
Reset allows you to move the changes from Stagged Changes to Unstaged. This is useful when you want to revert all files in Staged state not to be comitted.

```
git reset
```



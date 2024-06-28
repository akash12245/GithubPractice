# GithubPractice

I am learning GitHub Foundations Certification Course from https://www.youtube.com/watch?v=Jdc0i7RcBv8

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

When we want to commit and use the command, this will open up the commit edit message in the editor of choice.

> Make a commit amd add a message without openning the editor. This can be done from terminal.

```
git commit -m "message"
```


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

# Push

When we want to push our repo to our remote ourigin (Github Portal). 

```
git push
```

## Git Log

Shows the logs when you made the modifications to your git repository.

```
git log
```

## Git Config file

This helps you store your global configurations for git such as email, name, editor and more.

```
git config --list
```
After running the above command it shows the connets of our `.gitconfig` file.

When you first install git on your machine, you are supposed to setup ypur name and email.

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```


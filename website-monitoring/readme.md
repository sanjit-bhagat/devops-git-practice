
# Git Practice - Project Cleanup

## About This Project

This is a Git practice project that I created to improve my Git and GitHub skills as part of my DevOps learning journey.

In this scenario, I worked on a sample project called **website-monitoring** and performed common Git operations that are used in real-world projects.

## What I Practiced

* Initializing a Git repository
* Adding and committing files
* Creating a new branch
* Deleting an unnecessary folder
* Tracking changes using Git
* Merging branches
* Deleting branches after merging
* Viewing commit history

## Commands Used

```bash
git init
git add .
git commit -m "Initial project setup"

git checkout -b cleanup-branch

rm -r temp

git status
git add .
git commit -m "Removed temporary files"

git checkout main
git merge cleanup-branch

git branch -d cleanup-branch

git log --oneline --graph
```

## Project Structure

```text
website-monitoring/
├── app.py
├── README.md
├── logs/
│   ├── app.log
│   └── error.log
├── temp/
│   ├── test.txt
│   └── sample.txt
└── config.yml
```

## Key Learnings

* How Git tracks file and folder changes.
* How to work with branches safely.
* How to remove files and folders from a repository.
* How to merge changes into the main branch.
* How to view commit history and project progress.


### Author

**Sanjit Bhagat**


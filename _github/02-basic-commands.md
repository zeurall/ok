---
layout: course_post
title: "Basic GitHub Commands"
course: github
---

Now that you understand the basics of what GitHub is, let's look at some of the most common commands you'll use with Git, the version control system that powers GitHub.

### Essential Git Commands 💻

*   `git clone [URL]`
    *   **What it does:** Creates a local copy of a remote repository on your machine. You only need to do this once per project.

*   `git status`
    *   **What it does:** Shows the status of your working directory. It will tell you which files have been modified, which are new (untracked), and which are staged for the next commit.

*   `git add [file-name]` or `git add .`
    *   **What it does:** Adds a file to the staging area. The staging area is a list of changes that you want to include in your next commit. Use `git add .` to stage all modified and new files.

*   `git commit -m "Your descriptive message"`
    *   **What it does:** Takes the staged snapshot of your project and saves it to your project's history. The message should clearly describe the changes you made.

*   `git push`
    *   **What it does:** Sends your committed changes from your local repository to the remote repository on GitHub.

*   `git pull`
    *   **What it does:** Fetches changes from the remote repository and merges them into your local branch.

This is just the tip of the iceberg, but these commands are the bread and butter of working with Git and GitHub. Practice them, and you'll be a pro in no time! 💪

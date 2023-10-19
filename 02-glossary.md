# Glossary

In this lecture, we'll explore key concepts related to version control and collaborative development using Git and GitHub. Understanding these terms is crucial for successful collaboration on coding projects.

## 2.1 Repository
A **repository**, often referred to as a "repo," is a folder or storage space where your project's files and the complete history of those files are stored. Repositories are typically used to organize and manage code projects. In the context of version control systems like Git, a repository stores all the files and metadata about your project, including information about who made changes and when those changes occurred.

**Example:** If you're working on a Python project, your project folder with all its files can be a repository. You can create a new repository for your project on platforms like GitHub.

## 2.2 Commit
A **commit** is a snapshot of your project at a specific point in time. It's like taking a picture of your code's current state. Commits are used to save changes to your repository. Each commit is accompanied by a commit message that describes the changes made in that particular commit.

**Example:** After writing a function in your Python project, you can create a commit to save your changes with a meaningful message like "Added a new function to calculate the average."

## 2.3 Branch
A **branch** is a separate line of development in a Git repository. It allows you to work on new features or fix bugs without affecting the main project. Branches are isolated from each other, so changes made in one branch won't immediately affect other branches.

**Example:** When working on a Python project, you can create a branch called "feature-x" to develop a new feature. This way, you can work on the feature without disturbing the main codebase.

## 2.4 Pull-request
A **pull request**, often abbreviated as PR, is a way to propose changes to a repository on platforms like GitHub. It's a request to merge your branch (with your changes) into another branch, typically the main branch. Others can review and discuss your changes before merging them into the main project.

**Example:** After completing your feature in the "feature-x" branch, you can create a pull request to ask for your changes to be merged into the main branch of the Python project.

## 2.5 Fork
A **fork** is a copy of a repository in which you can make changes without affecting the original project. Forks are used when you want to contribute to someone else's project, make changes, and later propose those changes via a pull request.

**Example:** You can fork an open-source Python project on GitHub to create your own copy of it, then make modifications to your forked repository.

## 2.6 Merge
**Merging** is the process of combining the changes from one branch into another. It's typically used to integrate the changes made in feature branches back into the main branch of a project.

**Example:** After reviewing and approving a pull request for a new feature, the changes are merged from the "feature-x" branch into the main branch of the Python project.

## 2.7 Rebase
**Rebasing** is the process of moving or combining a sequence of commits to a new base commit. It's often used to maintain a cleaner and more linear project history. Rebasing can be an alternative to merging.

**Example:** You can rebase your feature branch onto the latest changes in the main branch to keep your branch up-to-date and avoid creating unnecessary merge commits.

## Practice Problems
1. Explain the purpose of a repository and how it is used in version control systems.
2. What is the difference between a commit and a branch? Provide an example of when to use each.
3. Describe the steps involved in creating a pull request on GitHub.
4. When and why would you fork a repository on GitHub?
5. Differentiate between merging and rebasing in the context of Git.
6. Create a simple scenario where rebasing would be a better choice than merging and explain why.

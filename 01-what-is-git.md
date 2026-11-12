# 1. What is Git?

**Git is a version control system**, a tool used to record and manage changes to files over time, especially in software development.

## The Three States

Git has three main states that your files can reside in: *modified*, *staged*, and *committed*:

- Modified means that you have changed the file but have not committed it to your database yet.
- Staged means that you have marked a modified file in its current version to go into your next commit snapshot.
- Committed means that the data is safely stored in your local database.

This leads us to the three main sections of a Git project: the working tree, the staging area, and the Git directory.

![](https://git-scm.com/book/en/v2/images/areas.png)

The basic Git workflow goes something like this:

1. You modify files in your working tree.

2. You selectively stage just those changes you want to be part of your next commit, which adds only those changes to the staging area.

3. You do a commit, which takes the files as they are in the staging area and stores that snapshot permanently to your Git directory.

---

# More Context

## What is GitHub?

**GitHub is a cloud platform that hosts Git repositories** and adds collaboration tools such as pull requests, issue tracking, and automated workflows for software development.

## What is GitLab?

**GitLab is an all-in-one DevOps platform that hosts Git repositories** and integrates code collaboration, issue tracking, security scanning, and built-in CI/CD pipelines into a single application.
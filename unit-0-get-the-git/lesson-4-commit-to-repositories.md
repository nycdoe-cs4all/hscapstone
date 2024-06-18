---
description: How can I create new repositories and push through changes?
---

# Lesson 4: Commit to Repositories

### Overview

This is the lesson where students start putting their skills together in ways that will enable them to build a stellar Github portfolio throughout the year. In this lesson, students will create their first github repo, work with git init and commits, and more to get their work onto the web.\
\
**PLEASE NOTE:** _This is the first lesson where students may be asked to login to Github from the terminal. A fun quirk is that when asked about a password, **it will not display anything when they type** - that's by design! The typing \*is\* happening, they just have to trust the process and hit enter when done._

### Objectives

Students will be able to:

* Understand the basics of creating and managing a Git repository.
* Learn the difference between Git and GitHub.
* Gain hands-on experience initializing repositories, making commits, and pushing changes to GitHub.
* Practice cloning repositories and understanding the purpose of cloning.

### Suggested Duration

2-3 Days, 45 minutes each

### NYS Computing Standards

* **9-12.DL.4** Independently select advanced digital tools and resources to create, revise, and publish complex digital artifacts or collection of artifacts
* **9-12.DL.5** Transfer knowledge of technology in order to use new and emerging technologies on multiple platforms.

### Vocabulary

* **Repository (Repo)**: A storage location for software packages, typically used to track and manage changes to a project using version control systems like Git.
  * **Remote Repository**: A version of your project that is hosted on the internet or another network. GitHub is commonly used to host remote repositories. 'Origin' is the default name given to the remote repository when cloning a repository or adding a remote.
* **Version Control**: A system that records changes to a file or set of files over time so that specific versions can be recalled later.
* **Git**: A distributed version control system used to track changes in source code during software development.
* **GitHub**: A web-based platform that uses Git for version control and provides additional features for collaboration and project management.
* **Initialize (git init)**: The process of creating a new Git repository. The git init command sets up all necessary files and data structures to track project changes.
* **Stage (git add)**: The process of marking files that have changed in your working directory to be included in the next commit. The git add command adds changes to the staging area.
* **Commit (git commit)**: The action of saving changes to the local repository with a descriptive message ('commit message'). The git commit command records the changes in the repository.
* **Push (git push)**: The process of sending your committed changes to a remote repository. The git push command updates the remote repository with changes made to the local repository.
* **Clone (git clone):** The action of creating a copy of a remote repository on your local machine. The git clone command creates a new directory with a copy of the repository.
* **Working Directory:** The directory on your local machine where you work on your project files. Changes made here are tracked by Git.

### Assessments

**Formative:**

**Summative:**

### Resources

* [Learn GitHub Introduction: Module 3](https://www.codecademy.com/learn/learn-github-introduction) (Codecademy)
* [Learn Git: Introduction](https://www.codecademy.com/learn/learn-git-introduction) (Codecademy)
* [Pushing to GitHub from Replit](https://ask.replit.com/t/using-git-to-push-replit-code-to-github/76064) (Tutorial/Resource)

### Do Now (\~3-5 min)

**Activity: Reflect/Review/Recap:**

* Ask students to reflect on what they learned about Markdown in the previous lesson.
* Prompt them to write down one thing they found useful and one thing they found challenging about using Markdown.
* Have a few students share their reflections with the class.

**Discussion:**

* Use this as a segue to discuss how version control (using Git) can help manage changes in files like Markdown documents.

### Code Along: Initialize Your First Repo

Explain that today, students will learn how to use Git to create repositories and make commits. As you start, clarify the difference between Git (a version control system) and GitHub (a platform for hosting Git repositories).

With students, open your IDE and open to a project folder - something that was created in Lessons 1 -3.&#x20;

**Code Along in the IDE:**

1. While in the root folder of the project, enter the following command in the terminal to intialize a git repository: `git init`
2. Explain that this command sets up a new Git repository in the current directory.
3. Make an initial commit: `git commit -m "Initial commit"`
   1. Commit messages are tracked and important as they let the developer know what changed in that step. Emphasize to students that it is important to write useful, descriptive commit messages.
4. Have students change something in their project directory, such as adding a new document. Then, type `git status` into the console. This shows what has been staged and commited and what has not, via color.
5. To add new changes to the git stage, use the command `git add fileName`, which will add a specific file, or `git add .` which will add everything that has been changed.
6. Once you've added, `git commit` again with a new message.

This is great, but so far we have been just working with git without connecting to Github. Let's change that! Ask students to navigate to Github and click the '+' to create a new repository. If their project already has a README file, they can initialize without, otherwise this can be a useful thing to add.

Then, walkthrough:

1. Copying the repository URL
2. Add the remote repository to your local git repo, from the root folder of your project, by entering in the console: `git remote add origin <repository-url>`
   1. _At this point, students may be asked to login to Github - please see the note in the Overview to avoid password confusion._
3. Then, use a push command to get the contents online: `git push -u origin master`
4. Remind students that it's okay if they don't memorize these commands; knowing how to find and use resources is key.

**NB:** If you have students working on repl.it, you can still use git and push to github, but the steps may be slightly altered. [Please see special considerations if using repl.it.](https://ask.replit.com/t/using-git-to-push-replit-code-to-github/76064)

### Independent Practice: Codecademy Review

It's okay if that feels like a lot - it _was_ a lot! Reassure students that they will have a lot of chances to practice and that there are _many_ resources out there to help them.

We will take a step back from working with actual repos to return to the sandbox. Students should return to Codecademy and:

1. [Complete the last module of Github Introduction](https://www.codecademy.com/learn/learn-github-introduction)
2. [Complete the Introductio](https://www.codecademy.com/learn/learn-git-introduction)[n to Github](https://www.codecademy.com/learn/learn-git-introduction)

### Task: Make another repo

This is likely the start of another class period; to kick things off, have students create and commit another project, such as the Markdown partner profile project they didn’t commit during the Lesson 3. _If students have not already, ensure that they make another repo and push their maze of files form Lesson 2 - this will be a part of our spiral review!_

Students should follow all steps from earlier in the lesson, using resoures as necessary to remind themselves of what to do.

### Clone Repo & Spiral Review

When working with git and Github, you may need to use someone else's starter code or collaborate with someone else. This is where cloning comes in!

When we 'clone down' a repository, we make a copy that lives on our computer. We can either work on this cloned repo with the intent of pushing our changes back into a new branch for the original user to review (and potentially add) to their project, or we can make the clone our own and push it into a unique repo that we own.\
\
Cloning, essentially, creates a local copy of the file to work on.

Pair students up: each should clone down each others file maze repository. To do this, they will start in their root directory (not in a project folder) and enter the command: `git clone <repository-url>`

Now, if they do not intend to push any changes back to the original owner, they can run `git remove remote origin`. This will remove the reference to the original, and students can remix to their hearts content.

Frame the next lesson: explain that cloning is the first step towards working with branches, which will be covered next, and in that instance, we will _not_ remove the remote origin.

**For now, ask students to navigat each other's file mazes using ls and cd - they should try to find all the x's with only their keyboard.**

### Wrap Up (\~5 min)

**Reflection/Exit Slip Questions:**

* What was the most challenging part of initializing and committing to a repository?
* How do you think using Git and GitHub will help you in your future projects?
* Write down one command you learned today and explain what it does.

### Extensions

[Introduction to Command Line: Viewing and Changing the File System](https://www.codecademy.com/learn/learn-the-command-line-viewing-and-changing-the-file-system): Advanced students may be interested in looking at more complex ways to use git. This is by no means required.

# Lesson 5: Branches and Versioning

### Overview

In this lesson, students will delve into the concepts of branching and versioning using Git. Through a combination of interactive tutorials and practical exercises in a sandbox environment, students will learn how to create branches, manage different versions of a project, and collaborate with others effectively. This hands-on approach ensures that students gain a thorough understanding of how branching facilitates concurrent development and version control, essential skills in software development.

### Objectives

Students will be able to:

* Understand the purpose and benefits of branching in version control.
* Create and switch between branches in a Git repository.
* Merge branches and resolve conflicts.
* Collaborate on projects using branches.
* (Eventually) Apply these skills in practical, real-world scenarios.

### Suggested Duration

\~1 - 2 periods, assuming 45 minute periods

### NYS Computing Standards

* **9-12.DL.4** Independently select advanced digital tools and resources to create, revise, and publish complex digital artifacts or collection of artifacts
* **9-12.DL.5** Transfer knowledge of technology in order to use new and emerging technologies on multiple platforms.

### Vocabulary

* **Branch**: A parallel version of a repository that diverges from the main codebase to work on different tasks or features independently.
* **Versioning**: The process of assigning unique version numbers to different states of a project, enabling tracking of changes over time.
* **Merge**: Combining changes from one branch into another, integrating the divergent branches back together.
* **Conflict**: A situation that arises when changes from different branches cannot be automatically merged, requiring manual resolution.
* **Pull Request (PR)**: A method of submitting contributions to a repository, where changes are reviewed before being merged into the main branch.
* **Fork**: A personal copy of another user’s repository that can be modified without affecting the original.
* **Checkout**: The process of switching between different branches or commits in a repository.

### Assessments

**Formative:**

* Observation during interactive tutorials and practical exercises.
* Participation in discussions and activities

**Summative:**

* Upcoming end of unit project

### Resources

* [Learn Git Branching](https://learngitbranching.js.org/?locale=en\_US) (Interactive Tutorial)
* [Learn Git: Branching and Collaboration](https://www.codecademy.com/learn/learn-git-branching-and-collaboration) (Codecademy)
* [Learn Enough Git to Be Dangerous](https://www.learnenough.com/git-tutorial) (Tutorial)

### Do Now (\~3-5 min)

**Activity:**

* Ask students to think about scenarios where multiple people work on a project simultaneously.
* Have them write down what they think might be useful and what could be problematic in such scenarios.

**Discussion:**

* Prompt students to share their thoughts.
* Highlight the importance of managing changes and coordinating efforts, setting the stage for learning about branching.

### Mini Lesson: Branching, Versioning (5 - 7 min)

Explain that branching allows multiple people to work on different features or fixes simultaneously without interfering with each other’s work. Emphasize that versioning helps keep track of changes, making it easier to manage and revert to previous states if needed.

**Branching:** Creating a new branch allows you to make changes without affecting the main codebase. Once the changes are complete and tested, the branch can be merged back.

* Example: A team working on a website might have branches for new features, bug fixes, and experiments.

**Versioning:** Assigning version numbers helps track the progress of a project. Each commit represents a snapshot in time, which can be revisited or compared with others.

* Example: Software might have versions like 1.0, 1.1, 2.0, indicating major and minor updates.

### Exploration: Learn Git Branching

To begin, students will be exploring git branching in a visual environment to help them make sense of what's happening.

Direct students to the [Learn Git Branching](https://learngitbranching.js.org/?locale=en\_US) website, which will step them through the process with clear, visual examples. Again, they do not need to complete everything, but should use this to get a clearer understanding before they start working in the command line of Codecademy and eventually their local terminal.

### Independent Practice: Codecademy

For their final Codecademy tutorail, ask students to complete [Learn Git: Branching and Versioning](https://www.codecademy.com/learn/learn-git-branching-and-collaboration). This safe, sandbox environment will provide guidance while students cement their understanding of branching and versioning.

### TIME PERMITTING: Folder Poetry

Melanie Hoff led a workshop for the School of Poetic Computing on [Folder Poetry](https://github.com/melaniehoff/folderpoetry?tab=readme-ov-file) - how creating folders and files with interesting names and strategic placement can create poetry that tells you about their author.\
\
If you have the time, create a Folder Poetry repository for your class. Ask each student to make a pull request and push a folder with their name that contains their folder poetry. Approve requests and merge branches as a class demonstration.

### Wrap Up (\~5 minutes)

**Share Out:**

* Have a few students share their experiences and any challenges they faced during the tutorials.
* Discuss how branching and versioning can be applied to their own projects.

**Reflection/Exit Slip Questions:**

* What is one new thing you learned about branching today?
* How do you think branching can help in collaborating on projects?
* Write down one command you learned today and explain what it does.

### Extensions

Students can explore further in Learn Enough Git to be Dangerous (linked in resources) or can begin working to collaborate with partners, testing their own pull requests and mergers.


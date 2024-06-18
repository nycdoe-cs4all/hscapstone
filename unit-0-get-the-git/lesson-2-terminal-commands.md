---
description: How can I engage with my computer through the terminal?
---

# Lesson 2: Terminal Commands

### Overview

In this lesson, students learn to use the terminal to navigate a file system. Much of the git work flow will also be taking place in the terminal, and being able to utilize these simple commands will make their lives much easier.

contain basics: `mkdir`, `ls`, `cd`, `touch`, etc etc

### Objectives

Students will be able to:

* Learn the concept of terminal and command-line interfaces.
* Understand and practice advanced file manipulation commands.
* Be able to use command options and arguments effectively.

### Suggested Duration

\~1-2 class periods, 45 minutes each

### NYS Computing Standards

* **9-12.DL.4** Independently select advanced digital tools and resources to create, revise, and publish complex digital artifacts or collection of artifacts
* **9-12.DL.5** Transfer knowledge of technology in order to use new and emerging technologies on multiple platforms.

### Vocabulary

* **Terminal**: A text-based interface used to interact with the computer by typing commands.
* **Command-Line Interface (CLI):** A method of interacting with a computer system or software by typing textual commands.
* **Shell**: A program that interprets and executes commands typed into the terminal. Common shells include Bash, Zsh, and PowerShell.
* **Directory**: A folder in the file system that contains files and other directories.
* **Path**: The address of a file or directory in the file system. It can be absolute (from the root directory) or relative (from the current directory).
* **Command**: A text instruction given to the terminal to perform a specific task.
  * **`pwd` (Print Working Directory)**: A command that displays the current directory you are in.
  * **`ls` (List Directory Contents)**: A command that lists the files and directories within the current directory.
  * **`cd`** **(Change Directory)**: A command used to navigate between directories.
  * **`mkdir` (Make Directory)**: A command used to create a new directory.
  * **`touch` (Create a File)**: A command used to create a new, empty file.
  * **`rm` (Remove File)**: A command used to delete a file.
  * **`rmdir` (Remove Directory)**: A command used to delete an empty directory.

### Assessments

**Formative:**

* Codecademy Independent Practice
* File Warren Practice

**Summative:**

* Upcoming End of Unit Project

### Resources

* [Introduction to the Command Line](https://www.codecademy.com/learn/intro-to-the-command-line) (Codecademy Free Course)
* [Command Line Tutorial | Terminal Basics](https://www.youtube.com/watch?v=EbuzaDlhJbE) (Youtube - short video ideal for sharing with students)
* [Command Line for Beginners](https://www.youtube.com/watch?v=uwAqEzhyjtw) (Youtube - long video ideal for teacher review)
* [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial/basics) (Tutorial/Reference)

### Do Now (\~3-5 min)

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>Image of Apple 2 computer with keyboard and disk drives displaying white text on black screen.</p></figcaption></figure>

Display the image above to your students. Ask them to write down:

* What they _notice_ about this computer
* What looks _familiar_ about this computer
* What might be _missing_ from this computer
* What they _wonder_ about this computer

### Mini Lesson: Introducing the Terminal (\~7 - 10 minutes)

After the Do Now, have a class discussion about their observations. Highlight the lack of a mouse and graphical interface, emphasizing that users interacted with these computers entirely via the keyboard.

Explain that early computers like the Apple II were operated using a command-line interface (CLI), where users typed commands to perform tasks. Discuss how, despite the advancements in graphical user interfaces (GUIs), the CLI remains a powerful tool for developers and system administrators. Today, students will begin to master the command-line! This will increase efficiency, automation, and access to powerful tools.

Students will be working in the **terminal** or **console** of their computer and/or IDE. _Be sure to define what a terminal is: a text-based interface to the computer._ Regardless of where you are working, it's worth showing students that terminals exist in both places.

**NB:** _Not sure how to find the terminal on your computer or IDE? Try a quick google search like 'Terminal Macbook Pro' or 'Terminal Windows' to get steps to open the terminal. In most IDEs, the terminal shares space with the console, where output is printed._

Navigate to a safe working space and ask students to do the same. A recommendation is to do this in your IDE - you may need to make some files in advance, or ask students to create some files in advance, to make the actions more meaningful. Students will jump into practice immediately after the demonstration - exercise your best judgement in deciding if they would benefit from a code along, or just watching before cementing understanding in the Codecademy guided practice.

**One at a time, demonstrate:**

* `pwd` (print working directory)
  * Demonstrate how to display the current directory.
  * Syntax: `pwd`
  * Example: `pwd`
  * Ask students to follow along and check their current directories.
* `ls` (list directory contents)
  * Demonstrate how to list the contents of a directory.
  * Syntax: `ls`
  * Example: `ls`
  * Students practice listing the contents of different directories.
* `cd` (change directory)
  * Demonstrate how to navigate between directories.
  * Syntax: `cd [directory]` or `cd ..` (step back)
  * Example: `cd Documents`
  * Students practice changing directories and navigating the file system.
* `mkdir` (make directory)
  * Demonstrate how to create a new directory.
  * Syntax: `mkdir [directory_name]`
  * Example: `mkdir my_folder`
  * Students create their own directories.
* `touch` (create a file)
  * Demonstrate how to create an empty file.
  * Syntax: `touch [file_name]`
  * Example: `touch myfile.txt`
  * Students create files within their directories.
* `rm` (remove file)
  * Demonstrate how to delete a file.
  * Syntax: `rm [file_name]`
  * Example: `rm myfile.txt`
  * Students practice deleting files they created.
* `rmdir` (remove directory)
  * Demonstrate how to remove an empty directory.
  * Syntax: `rmdir [directory_name]`
  * Example: `rmdir my_folder`
  * Students practice removing directories they created.

_If you are looking for ways to meaningfully demonstrate the above commands, consider something like:_

* Create a directory named `projects`.
* Navigate into the `projects` directory.
* Create a file named `project1.txt` inside the `projects` directory.
* List the contents of the `projects` directory.
* Delete the `project1.txt` file.
* Remove the `projects` directory.

### Independent Practice: Introduction to Command Line (\~15 - 25 minutes)

The best instruction often comes directly from a teacher, but guided practice can be wildly helpful as students navigate things like terminal commands and git. Codecademy provides a safe sandbox space for guided play, so to get students going, we recommend this [codecademy](https://www.codecademy.com/learn/intro-to-the-command-line) practice activity.

Student should work individually and aim to complete as much as possible. Preview the material, as it may not be necessary that \*everything\* is finished as long as \*most\* things are understood - consistent practice throughout this unit and the year will also go along way to making the skills durable.

### Partner Practice: Create a File Warren (\~10 - 15 minutes)

Have students work together to create a labyrinth of directories and files. This will let them practice their `mkdir`, `cd`, and `touch` skills especially.

Have students begin by creating a new project directory in their IDE. In the new project, `mkdir` to create nested files, hide x.md (markdown) files inside of these using `touch`. Navigate through the labyrinth using `cd` and `ls`.\
\
Students will eventually push this project to a repo - in a future lesson, other pairs will clone down their work and navigate to find the hidden x.md files as a form of spiral review.

### Wrap Up (\~3-5 minutes)

Consider having students answer one or more of the exit slip questions for submission:

* How do you change to a directory named `Documents` using the terminal?
* If you wanted to create a new directory named `Homework`, what command would you use?
* Which command did you find most interesting or useful today, and why?

### Extensions

_While none of these are required, the extensions for this learning activity are game-based - we strongly recommend making them available with students to explore on their own time even if they do not get to them in class, or dedicating an extra day to explore and play if your timeline permits._

* [**Bandit**](https://overthewire.org/wargames/bandit/bandit0.html) is a command line based game - it uses more commands than students are introduced to in this course, so they may need to do some Googling to deepen their learning.
  * **See also,** [**3 Command Line Games**](https://opensource.com/article/19/10/learn-bash-command-line-games)**:** these three similar games (with different interfaces, scenarios, and goals that may appeal at different levels to your students) are also a great way to reinforce and deepen learning. Some require installation and may require prescreening to ensure use is possible in your school setting.

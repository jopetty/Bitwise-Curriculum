# Bitwise 01: Introduction to Computer Science

Hello there. If you are reading this, congratulations on deciding to learn about the fascinating world of computers, electronics, mathematics, and programming known as computer science. This curriculum will cover topics like Web Development, Object Oriented Coding, Python Syntax, User Interface Design, and even the Architecture of the Internet. If you're feeling intimidated by all of that technical vocabulary, don't worry; this curriculum is designed to teach you about computer science from the ground up.

### What this course covers
Bitwise is an introductory computer science program, meaning that it will give you a good overview of many different aspects of computer science. We won't go into so much detail as to overwhelm you with new information, but rather strive to cover a broad scope of knowledge. Think of this as a "Liberal Arts Approach to Computer Science". Each lesson will cover a new topic, and will likely build upon this skills learned in the previous lesson.

In addition to talking about programming or coding, this course will touch on aspects of electrical engineering and mathematics to give you an understanding of how and why what you develop works the way it does. It will also cover concepts that at first glance may not seem like they have much to do with conventional computer science, like art, history, physics, philosophy, language, music, biology, and literature. These topics are included because computer science, like all aspects of life, does not exist in a vacuum. Whether you are a software developer or a painter, you will live in and interact with a world that contains a vast multitude of knowledge and disciplines. It is important to understand how the knowledge obtained through history, math, engineering, and art shape the development of computers and how computers shape those bodies of knowledge in turn.

### Format
Each lesson will start out roughly like this. There will be a folder named ```Lesson-n```, where ```n``` is the lesson number, and inside that folder will be a markdown file to give you an overview of what the lesson will cover, what tools will be needed, simple examples of code, tasks and objectives for each lesson, and resources for you to explore if you want to learn more about the topics covered. There will also be a folder with any files you will need to complete the lesson.

Throughout each lesson there will be a core topic such as "What is a Computer" or "Loops in Python"; this will be what the lesson is about. There will also be a list of objectives for you to complete; these will be questions about the content covered and tasks you should complete to ensure that you are learning about the topic. With the more traditional information about computer science, there will also be tie-ins to interdisciplinary themes. For the "What is a Computer" lesson, this includes interdisciplinary content such as "The physics of electricity, electrical circuits, an overview of Moore's Law, and references to an xkcd comic".

## Lesson 1: An Introduction to Computer Science
### Required Materials:
* [ ] Your computer (or the computer you plan to use for the duration of this course)
* [ ] Access to the Internet

### Objectives
* [ ] Getting to know the other people, if you are taking this course in a classroom setting
* [ ] Understanding what computer science is
* [ ] Why do you want to learn about computer science?
* [ ] Setting up your computer
* [ ] Scheduling
* [ ] *Troubleshooting (optional)*

### What Is Computer Science?
According to a quick Google search<sup>[1]</sup>, computer science is defined as the following:

>computer science (noun): the study of the principles and use of computers

As you might suspect, this is a perfectly valid definition. It is not, however, the *only* definition. While unsurprisingly computer science does have a lot to do with the use of computers, it also has to do with how those computers work, and why they work in the way that they do. It has to do with how those computers came to be, and why they were first created. It has to do with the mathematics and design of computer systems, from the chip in a digital watch to the most powerful supercomputing clusters. It has to do with the impacts computers have influenced our day to day lives and the ways we interact with them. Perhaps most importantly, computer science has to do with the way computers will change in the future, and the philosophical, ethical, and technological implications those changes will bring.Computer science is not limited in scope to just learning how to program.

Consider for a moment that for much of the 20th century, the idea that a fully functional computer could fit inside your pocket would have been considered a piece of science fiction, and an unbelievable one at that. In those days, writing a program had less to do with learning the words that a particular programming language used and a whole lot more to do with punching holes in a very long strip of paper. Back then, computers were not a very large part of most peoples' daily routine. Today, we find computers in our watches, phones, refrigerators, and cars. They are in the satellites that orbit above our heads and in the giant server farms that we call 'The Cloud'. In this sense, the very idea of what a computer is or can be has changed, and will continue to change, as time goes on. With this in mind, a more holistic definition of what computer science is can be formed.

> Computer science is the study of the history, use, design, function, and change of computers.  It encompasses the technological, scientific, economic, and moral implications of the advancement of computers as well as the understanding of the people, principles, and ideas that have shaped their development.

### Why do You Want to Learn About Computer Science?
Admittedly, this is a slightly broader topic that the previous because there are a multitude of reasons why one might be interested in computer science, and these reasons can be different for every person. Perhaps you think it would be a cool career. Maybe you know someone who is a programmer and you want to know more about it. You may think it seems like a fun way to pass the time. Ultimately you must decide for yourself why you are motivated to learn about computer science, but there are plenty of reasons why it is worth considering.

#### Computer Science As a Job
According to data from the U.S. Bureau of Labor Statistics<sup>[2]</sup>, the projected job outlook for software developers until 2022 is 22%, far higher than average. Computer science is a well paying career with lots of room for creativity and development. In terms of employability and job growth, computer science is a good choice.

#### An Engaging Field
Computer science is a broad term. If you are interested in computer science, you can choose from a wide array of career paths like Web Design or Software Development. Understanding how your computer connects to the Internet or how to write simple programs to solve problems can be useful in your day to day life. Computer science also allows you to integrate math and science in a meaningful way; most scientific analysis can use computers when working with data or visualizing patterns.

Think about why you want to learn about computer science, and use those ideas to set goals for yourself. Talk about what you want to learn from this class, and what you want to do with computer science; this will make it easier to get the most out of your experiences.

### Setting Up Your Computer
For the next few lessons, your development setup (the collection of software and hardware tools) will be relatively simple. The coming lessons will focus on some broad topics and web development, so it is important that you have a functioning web browser, like Google Chrome, Mozilla Firefox, or Safari. If you can, install multiple browsers so that you can test what you design in multiple settings. Later on you will also need to install Python, a versatile and human-readable programming language.

#### Installing Python
The first step to installing Python is checking to see if Python is already installed! If you are using a Mac computer, this is likely the case. To check, open up a command line window and enter the following:
```
python --version
```
If you are running Windows, enter this into Command Prompt by navigating to [Start Menu] > [All Programs] > [Accessories] > [Command Prompt]. If you are running OS X (Mac), enter this into Terminal by navigating to [Finder] > [Go (menu bar item)] > [Applications] > [Utilities] > [Terminal]. If you are running a Linux distribution, the location of your terminal emulator may vary, but is usually located with your other applications.

If you have Python installed, your will get the following response:
```
python --version
>> Python X.X.XX
```
Where X.X.XX is the version number. Make a note of whether this begins with a 3 or a 2; it will be important later on in the course.

If you do not have Python installed, you will get an error message. If this is the case, you will need to install Python from the [Python website](https://wiki.python.org/moin/BeginnersGuide/Download). It is recommended that you download and install Python 3. For more in depth instructions on how to install, consult your teacher or find tutorials on the Python website.

### Scheduling
If you are taking this course as a class, it is likely that you will be doing so in weekly classes. If you are following along on your own, that's great too! It is recommended that you still stick to the weekly schedule of the lessons. They are spaced out for several reasons. First, it's good to learn this skill over time. Refreshing yourself every week on what you have already learned will make the knowledge stick. Second, we want you to work on your lesson over the whole week, not just during the time you attend class or read the lesson information. Not only will you retain more content, you will also get more practice! Some of the tasks for each lesson may require an extended bit of time to complete, so work on them during the rest of the week. If you finish early, see if you can find ways to add to or improve that you have made. In the long run, it will help you.

### Troubleshooting
Hopefully you have gotten this far and everything works perfectly. Unfortunately, that may not be the case. Fear not, for there are things you can do to solve these problems. The first step is finding out what went wrong. If you can't install a new web browser, check to see if there are any reasons why (maybe it can't run on your computer, or maybe you don't have the right privilegesliges or permissions to install the software). The next step is figuring out how to solve said problem. If you can, ask your teacher for help; chances are that they have experience with this kind of thing. If that isn't an option for you, check to see if there is any helpful information on the websites where you got the software. YouTube can also be a good resource for finding tutorials on software installation. To search for good tutorials, try to follow the following format:
```
[What you are trying to do] [Your current Operating System]
```
For example, ```Installing Python Windows 8```. This should help you find answers to your questions.

#### A Note on Privileges and Permissions
It may be the case that your account is not allowed to preform certain tasks like installing new software or running a terminal/command prompt. If this is the case, see if you can contact your computer's administrator (maybe a parent or teacher) and see if they can change this for you. If not, it will be very difficult to continue with this course as you will need some software in order to follow along with the lessons. Feel free to read through, but try and get acess to a computer where you can use the necessary software.

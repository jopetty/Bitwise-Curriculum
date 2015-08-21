# Bitwise Education: Introduction to Computer Science

We all remember [that classic scene](http://www.wired.com/2015/06/tech-time-warp-time-unix-saved-day-jurassic-park/) from Jurassic Park (if you haven’t seen it, I highly recommended it). Trapped in a room by paleontologically inaccurate velociraptors, Lex, the young teenage hacker, rushes to the lab’s computer terminal and discovers it runs Unix. Navigating the 3D maze of files, she finds the controls for the park and reboots the system, locking the doors and saving the day.

Although this scene seems today a poorly rendered CGI cliché, a Unix system is a real thing, and has led to the development of software that today runs on millions of devices world wide. Unix is a type of operating system - a central component of your computers software and the tool that enables you to run programs and applications. This week, we take a look at just what operating systems are and how they function.

## Lesson 03: It’s a *NIX System!
### Required Materials
* [ ] Your computer (preferably running a Windows, Mac, or Linux/Unix operating system)
* [ ] Access to the internet

### Objectives
* [ ] Understanding what an operating system is
* [ ] Knowing how operating systems differ from each other and why this is important
* [ ] Knowing the general characteristics of major operating systems

### What Is an Operating System?
Like other software, an operating system is a collection of instructions that runs on a computer’s hardware. These instructions enable your computer to do most of the things that make it useful to you, like storing data displaying pictures on the screen. Allow you to use flash drives and move your cursor around the screen when you move the mouse or use the trackpad. Most importantly, operating systems allow the computer to run other software, like the programs you use on a daily basis. Why are operating systems necessary? Think of it like this: operating systems are very low-level pieces software, meaning that they interact directly with a computer’s hardware. They can access your computer’s processor, RAM, and storage directly. Now, every computer has a finite number of resources: only so much available memory, so much storage, so much processing power. Every program needs those things to run. Part of an operating system’s job is to allocate, or assign those resources in an efficient way. This allows multiple pieces of software to play nicely with each other.

Another key feature of operating systems is that they provide the tools for a user to interact with the computer. They display  and move windows, allow your keyboard to send instructions to software to display text, and so on. Finally, one of the more overlooked qualities of operating systems is that they do this, for the most part, automatically in the background. When you open a web browser, you don’t need to tell your computer how to create the window, or where it should be placed, or how to draw the little close and maximize buttons. Your operating system takes care of this so that you don’t have to.

### How Are Operating Systems Different?
As you’ve probably noticed, there is a bit of a competition going on in the tech world between Apple and Microsoft. These companies make and sell computers, and each develops their own operating system. Apple has Mac OS X, and Microsoft has Windows. While both Mac OS X and Windows preform essentially the same tasks, there are some under-the-hood differences in how they each work. Usually, this means differences in their **kernel** - the core collection of software that forms the foundation for an operating system.

OS X and Windows can both trace their origins back as far as the late 1980s. Since 1985, Windows has existed in some variant or another, although all releases since Windows XP have been based on the Windows NT kernel, first released in 1993. OS X derives from Unix, an operating system first developed at Bell Labs, and BSD, a Unix variant developed by UC Berkeley. This was modified into NeXTSTEP, and then in 2000 into Darwin, the kernel that forms the basis of OS X. 

#### Linux
The other major operating system for desktop computers is Linux, another operating system based on Unix. If you haven’t heard about it before, don’t worry, you’re not alone. Linux isn’t as well known as Windows or OS X for several reasons. Firstly, Linux is not a single, cohesive unit. There are many, many different varieties called distributions or ‘flavors’, and they can vary in appearance and functionality. Secondly, Linux is not made by a single, multi-billion dollar corporation like Apple or Microsoft. The core code for Linux was made by a guy named Linus Torvalds, but he isn’t the one who makes all of the distributions. Instead, distributions are made by different groups of people and companies. While Linux is not as common among most users, it *is* highly popular with software developers and computer scientists. One of the major benefits of Linux is that it is free, on multiple levels. Linux distributions are almost always free to download and install. They are also free in the sense that their code is free to use and change. Linux is **open-source** software, meaning that anyone can view the code. This is very different from most commercial, **closed-source** software, where a company will charge you money for the right to use their software, but you can’t make any changes to it or build off of it to create something new.

OS X, like other operating systems that are based in some part off of Unix, are sometimes grouped as *nix or Unix-like systems because they all share similar features not found on other types of operating systems.

The differences between operating are important because they will affect how you as a developer will want create software. Firstly, software that is made for a particular operating system won’t always run on a system it was not designed for. Software that is designed to run on multiple systems is known as **cross platform software**. If you design your code to be platform independent, it can be used by more people on different systems. Secondly, if the tools you use to create software are specific to a particular operating system, you may need to use multiple pieces of software to create code that is cross platform.

### Characteristics of Operating Systems
Arguably the most important job for an operating system is allowing a user to interact with a computer. There are two primary approaches to this: **Graphical User Interfaces** and **Command Line Interfaces**. Graphical User Interfaces, usually shortened to GUIs, are what you are most likely familiar with. Almost all common operating systems designed for everyday users use a GUI, including OS X, Windows, and several Linux distributions. They display information on a screen using icons, pictures, windows, and other visual cues.

Command Line Interfaces, shortened to CLIs, instead use only text to display information, requiring users to memorize sets of commands to be entered in order to manipulate data and preform tasks. CLIs used to be the standard for human-computer interaction, but most newer operating systems have adopted the ability to use GUIs because they make it easier for people to learn to use a computer. Although they can be more difficult to learn how to use, CLIs do have some advantages; it’s much easier for a computer to only display text, so CLI systems don’t need to devote as much processing power to displaying fancy graphics. They can also be more powerful than their graphical counterparts, making it easier to do certain tasks in a relatively simple fashion.

Today, most operating systems use a mix of CLI and GUI. While usually using a GUI, they use a special program to emulate a CLI environment. In Windows, this is Command Prompt and Power Shell, and in OS X and Linux the terminal.As a bonus, most Unix-like operating systems share a standardized, or at least very similar terminal, meaning you can use most of the same commands in the Mac Terminal app as you would in a Linux terminal emulator.

### Recap
* [ ] Do you understand what an operating system is and how it functions?
* [ ] Can you name major operating systems and what makes them different?
* [ ] Can you define the terms Linux and Unix and explain why they are important?
* [ ] Do you know what GUIs and CLIs are, and why they are used or not used?


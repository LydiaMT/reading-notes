# Text Editors
While every computer comes with it's own text editor for coding and building websites (*i.e. Text Edit or Notepad*) these text editors are limited in their features. There are text editors you can download that have features like code completion, syntax highlighting, themes, and the ability to add extentions:

* Code Completion: As you type code, this feature in a text editor will offer assumptions and suggestions which can save time and reduce typing errors
* Syntax Highlighting: This is essentially color coding for various features in your code to distinguish features from one another
* Themes: allow you to change the color of your text editor to reduce eyestrain. 
* Extensions: plugins that allow you to add functionality to your coding processes

### Common Text Editors

Text Editor | Operation System
------------ | -------------
NotePad++ | Windows
BB Edit | Mac
Visual Studio Code | Windows, Mac, Linux
Atom | Windows, Mac, Linux
Brackets | Windows, Mac, Linux
Sublime Text | Windows, Mac, Linux

Note source: [Choosing A Text Editor](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf) by The Older Coder


# Cheatsheet for the Terminal

The following is a compilation of notes from these articles:
* [The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)
* [Basic Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php)
* [About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

### **Notes**
#### The Command Line
* The command line is a *text based interface system*. You typically enter a command, get an output, then the terminal is ready for you to enter another command via the prompt it displays. 
* To open a terminal on your **Mac** click command + Space and search for 'Terminal'. You can also find the terminal in your applications under utilities. 
* To open a terminal in **Linux** go to Applications -> System *or* Applications -> Utilities
* On **Windows** you will remote login via SSH
* The terminal might feel intimidating at first, but once you get the hang of it it's a great tool! You feel like you're in the Matrix. 

![Neo from the Matrix](https://pbs.twimg.com/media/DzPqcK4X0AAJ9JO.jpg)

#### Basic Navigation
* **pdw**: Print Working Directory - tells you where your current working directory is
* **ls**: List - this gives you a list of all of the documents or folders in your *current location*. Some variations of a ls command are ls -l, ls /etc, ls -l /etc
* **Paths**: There are *absolute* and *relative* paths. Paths start with a root directory, or the primary folder, and each sub folder follows a forward slash i.e.  (/) . Absolute paths show the entier pathway whereas relatives paths show files in relation to where you currently are in you system. Some other ways to build paths include:
1. tild (~): shortcuts to your home directory
1. dot (.): shows you your current directory
1. dotdot (..): references the parent directory
* **cd**: change directory
* **pro-tip**: If you suck at spelling, like me, you can always hit tab which will autocomplete your command. 

#### About Files
* If you think of your computer as a car, the terminal is like looking 'under the hood'. Under the hood, everything is basically a file. Files are strctures as filename[path], and the path can be .txt .png .doc and so on. 
* Note that commands are case sensitive
* You separate items in your command with spaces. However, if your file has a space in it already, you can put quotes around it so the terminal reads it as one file or you can put a backslash (\ ) between your words to nullify the meaning of the next character. 


Return to [README](README.md)

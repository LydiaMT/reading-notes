# Cheatsheet for the Terminal

The following is a compilation of notes from the following articles:
* [The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)
* [Basic Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php)
* [About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

### **Notes**
#### The Command Line
* The command line is a *text based interface system*. You typically enter a command, get an output, then the terminal is ready for you to enter another command via the propt it displays. 
* To open a termial on your **Mac** click command + Space and search for 'Terminal'. You can also find the terminal in your applications under utilities. 
* To open a termial in **Linux** go to applications -> systerms *or* applications -> utilities
* On **Windows** you will remote login via SSH
* The terminal might feel intimidating at first, but once you get the hang of it it's a great tool! You feel like you're in the Matrix. 

#### Basic Navigation
* **pdw** :Print Working Directory - tells you where your current working directory is
* **ls** :list - this gives you a list of all of the documents or folders in your *current location* . Some variations of a ls command are ls -l, ls /etc, ls -l /etc
* **Paths** :There are *aboslute* and *relative* paths. Paths start with a root directory, or the primary folder, and each sub folder follows a forward slash i.e.  / . Abolute paths show the entier pathway whereas relatives paths show files in relation to where you currently are in you system. Some other ways to build paths include
1. tild (~): shortcuts to your home directory
1. dot (.): shows you your current directory
1. dotdot (..): references the parent directory
* **cd** : change directory
* **pro-tip** : if you suck at spelling, like me, you can always hit tab which will autocomplete your command. 

#### About Files
* If you think of your computer as a car, the terminal is like looking 'under the hood'. Under the hood, everything is basically a file. Files are strctures as file [path], and the path can be .txt .png .doc and so on. 
* Note that commands are case sensitive
* You sepearte items in your command with spaces. However, if your file has a space in it already, you can put quotes around it so the terminal reads it as one file or you can put a backslash \


Return to [README](README.md)

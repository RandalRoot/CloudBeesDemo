
# Python Basics   <img src="./images/Figure01.png" alt="Python Icon" width="10%" height="10%" /> 

In this demo we will cover the basics of installing, running, and programming with Python. By the end of this demonstration you will know how Python can be installed and used on your Mac or Windows computer.

## What is Python?
Python is a simple yet powerful programing language. It is an easy language to learn but still powerful due to the extensive pre-made code modules you can download freely (code modules are files with code in them.) 

Here are some good facts to know about Python:

-	Python is free to use, even for commercial products! 
- Python runs on Windows, Linux/Unix, and Mac OS X 
-	There are two main versions of Python 2.x and 3.x 
- Both version 2.x and 3.x can be installed on the same computer
-	Mac already has 2.x installed  
-	Python 2.x has been deprecated as of January 2020
-	Python 3.x is recommended for all new projects


## Installing Python
Python is easy to download and install. A quick internet search will provide you with a download link and several installation videos based on your chosen OS. https://www.google.com/search?q=How+to+install+python (external site). 

You must first download the installation program from  https://www.python.org/downloads/ website (Figure 2). This page is context-sensitive, so it should recognize your OS and then provide the appropriate download option. Afterward, you run the Windows .exe or the macOS .pkg file to begin installing. 
 
Figure 2. Downloading Python's installation program

<img src="./images/Figure02.png" alt="The Python Download page" width="80%" height="80%" />

Figure 2. Downloading Python's installation program

For a Windows installation, I recommend you check the checkbox to include Python's executable in the OS path, then click the custom option to choose an easy-to-access location like C.\Python\Python3.x for its installation folder (Figure 3).

<img src="./images/Figure03.png" alt="The Python Installation app on Windows" width="80%" height="80%" /> 

Figure 3. Customizing the Python installation


The Mac installer has fewer options than the Windows version and more text to read, but selecting the default options is fine (Figure 4).

<img src="./images/Figure04.png" alt="The Python Installation app on Mac" width="80%" height="80%" />

Figure 4. The Python installation on Mac OS


**_Important:_** Restarting your Mac may be required and is recommend after the installation.

## Demonstration
In this demonstration your instructor will walkthrough the process of installing Python on a Windows computer. Your are encourged to follow along if you would like.

This demo consists of the following steps:

1. Download the Python installer from Python.Org.
2. Run the installation program.

In this demonstration you saw how Python on a Windows computer. Next we will look at how to use your installation.

<hr/>

## Running Python
Once you have installed Python, you can run it interactively using a Console/Terminal or by creating scripts with a text editor. Both options have their place, and I recommend you always test your programs using both. 

### The Console/Terminal Interface
To open a command console in Windows 10, click the Start button then type in the command "CMD" into "Open" the textbox. Clicking the Command Prompt App option opens a command prompt window. With the Command Prompt open, type Python.exe to begin an interactive session (Figure 5).

<img src="./images/Figure05.png" alt="Starting Python's interactive mode on Windows" width="80%" height="80%" />

Figure 5. The Run dialog window


It is almost the same if you use a Mac, but now the Command Prompt is called a "Terminal" window. Open a Terminal window using Finder > Applications > Utilities > Terminal.app. You can access Python's interactive mode by typing in the "Python3" command in the Terminal window (Figure 6).
 
<img src="./images/Figure06.png" alt="Starting Python's interactive mode on Mac OS" width="100%" height="100%" />

Figure 6. A Mac Command prompt


**Note:** Remember, the macOS includes Python 2.x, so make sure you remember to use the correct version when you are running your code. On Mac, typing "python3" should connect you to your Python 3.x installation, while typing "python" will connect you to the Python 2.x installation. You can verify the version you are running using the -V switch from the command terminal of your computer (Figure 7). 
  
 <img src="./images/Figure07.png" alt="Testing Pythons version with -V" width="60%" height="60%" />
 
 Figure 7. Running multiple versions of Python on the Mac OS.


### The Windowed Editor
You can create and run Python code files (Scripts) using its built-in editor called IDLE. IDLE is simple to use software, and you can find several resources on how to use it via an internet search; https://www.google.com/search?q=How+to+use+Python+idle (external site)
On Windows, the necessary steps are:

1.	Click the Start menu icon.
2.	Type "idle" to search for the application.
3.	Launch IDLE from the link presented.

On macOS, the necessary steps are:
1.	Click on Finder
2.	Type in "idle.app" to search for the application.
3.	Launch IDLE from the file presented.

<img src="./images/Figure08.png" alt="Starting Python's Windowed Editor IDLE" width="100%" height="100%" />

Figure 8. Steps to open the Python's IDLE Application


Whether you use the interactive console/terminal or the windowed editor option, the code you enter is sent to the Python interpreter for processing (figure 9. This interpreter application is what we refer to when we say your code runs on Python. 

<img src="./images/Figure09.png" alt="Pythons apps work with the Python Interpreter" width="50%" height="50%" />
 
Figure 9. The Python interpreter



## Demonstration
In this demonstration your instructor will walkthrough the process of using Python's Interactive console/terminal application and IDLE. Your are encourged to follow along if you would like. Though, I will be using Windows, the process is very simular on macOS.

This demo consists of the following steps:

1. Open a command prompt and start Python in interactive mode.
2. Use the following common commands, one at a time, to show how the interactive mode works.

```python
first_name = input("Enter your first name")
last_name = input("Enter your last name")
print("You entered:", first_name, last_name)

```
5. Download the Python code file [demo01.py](../codefiles/demo01.py "download to open file in IDLE") and open it in IDLE:
 
   1. Click on the provide link to access the file's GitHub page.
   2. Right-Click the "Raw" button and choose the "Save link as..." option to download the file.
     <img src="./images/Figure10.png" alt="The RAW button context menu" width="50%" height="50%" />
   3. <ADD Instructions for using IDLE>

In this demonstration you saw how Python can be use with the interactive mode. In the next section, look at how to create a Python script.

<hr/>


## Summary
In this demo we covered how to install and start programming in Python. While we only covered the very basics, I have more material I am willing to share if you are interested. Here is my contact info on [Google Slides](https://docs.google.com/presentation/d/10KeZQ35RM3d9cDY5KNjvyz2z844UNtCt5Nl7brti-VQ/edit#slide=id.p).


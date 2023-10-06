# Ethical_Hacking_Tools
Ethical hacking tools are used by security professionals especially to get access to computer systems in order to access the vulnerabilities in computer systems so that their security will improve.

Run Python Script using Command-Line:
The most sought-after way to write a Python program is using a plain text editor. The code written in the Python interactive session is lost once it is closed, though it allows the user to write many lines of code. On Windows, the files use the .py extension.  

If you are at the beginning of working with Python, you can use editors like Sublime or Notepad++ which are easy to use, or any other text editors.

1. Using the python command
The most basic and easy way to run a Python script is by using the python command. You need to open a command line and type the word python.Then you hit the ENTER button from the keyboard, and that's it. You can see the phrase Hello World! on the screen. Congrats! You just ran your first Python script. 

However, if you do not get the output, you might want to check your system PATH and the place where you saved your file. If it still doesn’t work, re-install Python in your system and try again.

2. Redirecting output
Windows and Unix-like systems have a process called stream redirection. You can redirect the output of your stream to some other file format instead of the standard system output. It is useful to save the output in a different file for later analysis.

An example of how you can do this:

python first_script.py > output.txt

3. Using Script Filename
Windows makes use of the system registers and file association to run Python scripts. It determines the program needed to run that particular file. You need to simply enter the file name containing the code.

An example of how to do this using the command prompt:

C:\Users\Local\Python\Python37> first_script.py
Hello World!

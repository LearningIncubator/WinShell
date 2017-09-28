# WinShell
# Commands Covered:[HELP][/?][DEL][CLS][TYPE][DIR]
Ok Sooo lets talk about the command line in windows
Why is the command line black? because satan created it, and it is infuriating. With this said, i will continue.

For the shell windows, wimic, powershell, or any other , it needs to be in the correct form called syntax, without the proper syntax we endup with a less than desired effect.

the format in the shell(in this case im talking only windows shell not powershell) is this:
 # Command parameter1 parameter2 parameter3....etc ...etc
 
 Keep in mind that most commands Must come from the user but may be one of 2 types of commands
  Internal- these are the native commands to the windows shell, they are recognized and processed by the CLI(command Line Interface), and are not stored as an executable somewhere on disk.[del, dir, type, cls] are some.
  External - These are the commands that are part of the Operating System and are stored on disk somewhere.[attrib.exe,netsh.exe,ping.exe] are a few examples of External Commands.
  
The Parameters are also entered by the user but are optional
  Think about when you just type out a command like [DIR].  DIR has parameters like /h for help and /l
  
We also have special characters that can be used with commands like :
  # <space> & () [] {} ^ = ; ! ' + , ' ~
  
We can also Pipe commands together to execute commands successively or concurrently like:
  tasklist /svc | find /i "svchost"   (i used the tasklist.exe command with the flags /svc i then used the find command against the results to display the processes using "svchost.exe"

# Requirement for this task:
    Windows VM or Windows Computer(administrator level access)
    EYEBALLS, Fingers and Brain.... LOL

# Skill Level : Basic
_______________________________________________________________________________________

With a Shell[Command Prompt] open I want you to try these commands and you should recieve output either exactly like I display or Similar.

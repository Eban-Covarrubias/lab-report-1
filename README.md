# lab-report-1

Step 1: Installing VScode
You can download from this link -> https://code.visualstudio.com/
make sure to get a version that is compatible with your device, if you are on Windows you will also need to download git
here is the link for that -> https://gitforwindows.org/
Open up VScode and you are ready to start the next step.
View OpeningVScode.png, this is what you should see.

![Image](OpeningVScode.png)


Step 2: Remotely Connecting
Open the terminal by going to the menu bar on top and clicking terminal -> new terminal. Set the default terminal to use Git Bash by clicking the 
lauch profile drop down arrow and selecting git bash from the list. The arrow is circled below:
![Image](GitBash.png)

Type this line into the terminal "ssh cs15lwi23zz@ieng6.ucsd.edu" but instead of the wi23zz enter the correct characters for your specific account name. 
If the terminal asks you if you want to continue connecting type yes, and then enter your password when promted. The end result should look something like this:

![Image](RemotelyConnecting.png)

You are now successfully connected! Congrats

Step 3: Trying Some Commands
Now that you are logged in, you can try running some commands such as ls, cat, cd and so forth. I used the ls and cat commands to find files in other directories and print them to the terminal. Below you can see some of what is inside of README.instructor. Note that this file actually isn’t in my user’s directory, it's instead inside of a directory called public.

![Image](TryingSomeCommands.png)

In my 12th command I used the ls command, this command lists all of the directories in my current path. You can see my output in blue that the only directory was one called perl5. In my 14th command I used cat perl5, the cat command is used to read and print data from a file, the output was the terminal telling me that perl5 was a directory. Then in my 17th command I used cd, this command is used to change my directory. Using the command cd perl5 brought me into the directory perl5. In command 18 I used ls yet again to list out the files inside of the directory perl5. It was empty. I used cd.. in command 19 to return to the parent directory. I tried using ls on a specified path in command 22, doing so allowed me to output the directories in a different path than the one I was currently in. I continued to use the cat commands on specified paths to directories on lines 23 and 24.

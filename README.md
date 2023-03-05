# stopsleep
### prevent screen lock without admin privilages

This simple Batch script should stop your PC from going to sleep, locking the screen, and setting your status to "inactive". 

Very useful in corporate environment. 

The script waits 30 seconds, open another instance of the script and quits.
This creates an infinite loop of starting and closing windows. 

If you need to adjust the script, then right-click and edit/open with notepad. 

## Options

There are 2 variables: time and filename. 
### Time
Change time to whatever value you need. In my opinion 30 seconds is a safe bet. 
Make it too short, it might appear suspicious to computer or the sysadmins. 
Make it too long, the screen will lock before the instance is called. 
### Filename
You can change the filename however you wish, just keep in mind that the filename must match the name inside the script. 


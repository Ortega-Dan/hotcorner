FIRST INSTALL ONLY THE EXE FILE SOMEWHERE (WHEREVER YOU WANT) PREFERABLY IN YOUR DOCS FOLDER, only place the dll files in the same directory with the exe if errors pop up at execution.

For you to get it running at user log in ...
create a Runner.bat file with the following content:

start C:\Users\dev1\Documents\CHotCorners\ChotCorners.exe

.... end of the content ...
... being "start" the command that runs and the path must be the place where you locate the executable ...

and place that .bat file in

C:\Users\[YOUR SPECIFIC USER NAME]\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup

that way you will have hot corners right from the start of your session ...

Enjoy !!!


....
 
 OR TO BE HONEST ! JUST CREATE A TASK FROM TASK SCHEDULER AND HAVE IT TO TRIGGER WHEN YOUR USER LOGS IN !!!
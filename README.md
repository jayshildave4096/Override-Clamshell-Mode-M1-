# Override-Clamshell-Mode-M1-Mac
Here you will find a fully-native way to do this on a Mac without any third party apps.  It takes like 5 minutes to set up (all steps below), and let's you enable an intelligent No Sleep Mode with just a single click. No other menus, no fiddling around, no third party security threats. It just does exactly what it needs, nothing more, nothing less.
Steps:

1. Open Terminal.app and run these 5 commands to create the script files and set their permissions:
2. Go to Desktop > PauseSleep and double click on DontSleep.myscript. This will ask you what application to open the file with: Choose Utilities > Terminal.app. (This step is important because it will later let you click-to-run your script.)
3. Now, right click DontSleep.myscript and choose Open With > Other > TextEdit.app so we can edit the file. Simply copy-and-paste all the  code into the file from DontSleep.myscript. That's it. No fiddling required.
4. Follow the same for Sleep.myscript

The benefit of this approach (besides being safe from having to trust third parties) is that it reverts all of the changes the script made after 1 minute, but your computer will remain Awake until the next time you open and close the lid or until your normal sleep time is reached.



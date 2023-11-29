### this and that

from: https://www.techrepublic.com/article/16-terminal-commands-every-user-should-know/

Command: sudo

What it does: sudo is a command that allows you to elevate your user privileges while executing the command to administrator privileges. This is required for some commands to run — for instance, removing a file that is owned by another user. When you run this command, you will see a password field appear in Terminal where you will need to type your user account password to finish the command execution.

Your Mac has security baked in at its core, which is why when typing a password, the command line hides the characters typed for security practices. Remember to never type your password into a field that you did not request!

Command: top

What it does: With top, you’ll see the stats of your system updated in Terminal’s window, such as the memory, CPU and disk utilization. You’ll also see a running list of the top apps using the CPU, including their state, ports used, memory per app and more, without needing to open the Activity Monitor app on your Mac. This command will execute until you close Terminal’s window or press Control + C to return execution back to the CLI.

Command: q

What it does: For commands that run in perpetuity when executed, you can end execution of the process by pressing the q key on your keyboard. Alternatively, you can press Control + C.

Command: clear

What it does: Typing commands one after another can make a mess in the Terminal. The clear command removes all previously typed commands from the Terminal app’s view and gives you back a clean slate to work from. Instead of typing clear, you can also press Command + K to perform the same action.

Example: clear (Figure M)

Command: ditto

What it does: The ditto command will execute a copy of all of the contents of one folder into another folder you specify. This is great for when you need to start a new project and use an older project as a base or if you just need to copy files in a folder from your computer to an external drive. Add a -V, as in the example below, to get verbose output for each file copied.

Example: ditto -V MyFolder MyNewFolder (Figure N)

Command: whatis

What it does: When you want to get a short description of a command and what it does on your Mac, use the whatis command.

Command: man

What it does: Most commands in Terminal ship with a manual that allows you to get help or look up arguments and other information on what a command does. Similar to the whatis command, you can use the man command to find more information about a particular command.

Example: man “command” (Figure P)

Command: exit

What it does: The exit command will close out the current session in Terminal. While you can simply close the window, that may not be possible when you’re using SSH through Terminal to access a remote machine. In this instance, you’ll want to use exit to hang up that remote connection before closing the window.

Example: exit (Figure Q)

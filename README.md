This is a simple project made to make task tracking easy in a very simplified way.

Specifications:

Basic usage: Upon opening, start typing to create a new task; press ESC to cancel the task. 
To save the task to the list, press CTRL-Q to queue it (goes to the end of the list) or CTRL-W to stack it (goes to the start of the list)
To save the list to the file specified in loc.conf, press CTRL-S. To open the list from that file, press CTRL-O. 
If there is a current list that conflicts with the one being opened, or if the current list being saved conflicts with the save file and was not opened from there, the list being overwritten will be saved in the temporary storage file (overwriting it) as specified in loc.conf, or discarded if no temporary filename is specified.
To complete a task, click the box to the right of the task. Scrolling is supported with the up and down arrow keys.
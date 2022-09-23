# Open source SoftWare Lab 4

### Contents
1. Kernel & Shell
2. CLI & GUI
3. Shell Commands
4. Commands behind ls

---

### 1. Kernel & Shell
Kernel : ***The most core part of the OS.*** The part that communicates with the hardware and manages commands.  
OS : ***An interface to communicate with the Kernel.*** Most users touch the Kernel by touching the Shell rather than directly touching the Kernel.  



### 2. CLI & GUI
#### CLI
- Difficulty remembering commands.
- Commands mainly using the keyboard.
- Speed is fast. 
- Scripts that enable automation and logging.
- The default environment for developers.

#### GUI
- Easy to use and intuitive. 
- Mostly use the mouse, and some keyboard shortcuts. 
- Slow speed. 
- The manual work required for repetitive tasks by everyday users.



### 3. Shell Commands
```sh
$ pwd : Show the current directory.  
$ cd : Change directory.  
$ ls : List files and directorys.  
$ cp a.py backup_a.py : Command to copy a file.  
$ mv a.py b.py : Change a to b.  
$ mv b.py ../address : Move b to that location.  
$ rm FileName : Delete files.  
```
. : current directory  
.. : upper-level directory  
~ : home of current user  
/[directory name] : absolute path  
./[] : relative path  
../[] : relative path  



### 4. Commands behind ls
```sh
$ ls -l : Show detailed information (long format)  
$ ls -lh : It also shows the size.  
$ ls /FileName : Maintain your current location and view other direcotry information.  
$ ls -la : By default, hidden files are not visible, but hidden files can also be viewed when using this command.  
```

# Open source SoftWare Lab 5  

### Contents
1. < > command  
2. | command & Expansions  
3. Premissions  
4. Superuser & Tip  

---

### 1. < > command
```sh
$ ls -lh > file_list.txt : It is possible to output the result value to file_list.txt instead of the screen by using >  
$ cat file_list.txt : The cat command outputs the values in the file to the monitor.  
$ ls -lh >> file_list.txt : If you write it twice like >>, the new content is saved after the previous content.  
$ sort < words.txt > sorted_words.txt : Use < to sort the contents of txt and > to save as a different name.  
```


### 2. | command & Expansions 
#### | command
```sh
$ ls -lh | less : | allows you to see as little as you want. Escape by pressing the q button.  
$ ls | wc -l : A command to check the number of files in the current directory.  
```

#### Expansions
\* : expansion containing information in the current directory.  
\~ : The current user's home directory.  



### 3. Premissions
***Permissions can be changed using chmod.***
```sh
$ chmod 600 some_file  
```

---

rws = 111 in binary = 7  
rw- = 110 in binary = 6  
r-s  = 101 in binary = 5  
r--  = 100 in binary = 4  

---

Procedure is for owner, for groupt, for others.  
**So 'chmod 600 some_file' means, rw-------**  



### 4. Superuser & Tip
#### Superuser
put 'sudo' before the command if you are a superuser.  
sudo some_command  

#### Tip
If you type history , you can see all the commands you have typed.  
***You can check more conveniently by viewing the command as a file using cat history.***

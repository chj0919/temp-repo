# Open source SoftWare Lab 6  

### Contents
1. Changes & Snapshots  
2. A three-part version control system  
3. Three composition of git configurations  
4. Today's git commends  

---

### 1. Changes & Snapshots  
**Changes** : This system accumulates and stores changes according to the version in the earliest version.  
**Snapshots** : As used in git, as the version evolves, the entire previous version is brought as it is.  


  
### 2. A three-part version control system  
#### - Local
Collaboration is difficult because we have to store and transmit our local information with other people.  

#### - Centralized
A central server that manages multiple versions while providing the versions you need.  
The downside is that if one central server goes down, it becomes difficult for everyone to use.  

#### - Distibuted
Used by git. Unlike centralized, each local PC contains all versions of central server data.  
This means there is no need to communicate with a central server unless necessary, so there is less risk than centralized if the server goes down.  


### 3. Three composition of git configurations
#### - System level
--system option. Affects all uses and repositories on the system (administrative).  

#### - Global (user) level
--global option. Affects all repositories of a current user.  

#### - Local level
--local option. Specific to the current repository.  

***Each level overrides values in the previous level: system -> global -> local***  


### 4. Today's git commends
```sh
$ git --version : Git version check.
$ git config --list : Check my git configurations.
$ git config --list --show-orgin : Storage information is also provided.
$ git config --global user.name "NAME" : Set name. / You can check your name if you enter it without --global and "NAME".
$ git config --global user.email E-MAIL : Set e-mail. / You can check your e-mail if you enter it without --global and E-MAIL.
$ git config --global init.defaultBranch NAME : Set the MainBranch's name.
$ nano [file_name] : File edit.
$ git add words.txt : Upload to staging area.
$ git add. : Upload all the file to staging area.
$ git rm --cached [file_name] : A command to remove [file_name] from the staging area.
$ nano .gitignore : If you create .gitignore and write [file_name] in it, [file_name] will not be tracked.
```

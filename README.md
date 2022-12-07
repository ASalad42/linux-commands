# linux-commands

- `ls`  `cd`  `mkdir`  `touch`   `cat`  `mv`  	`cp`  `rm`  `chmod` i.e `chmod 777 my_file`


- find out OS name 
`uname` or `uname -a`


- how to create file in linux 
`touch filename` or `nano filename`

- how to check existing file/fodlers
`ls` or `ls -a`

- how to create a folder `mkdir fodlername`

- how to navigate inside the folder `cd foldername`

- how to come out of the folder or 1 step back `cd ..`

- how can we check our current location `pwd`
- `whoami`

- how to copy file `cp filename destination`

filename_with_absolute_path 
destination_with_absolue_path

- how to remove file/folder `rm -rf file/foldername`

- how to cut paste file/ move the test file inside 

`mv filename distination`

- how to check all processes `top` and `ps aux`

- how to remove/delete/kill process ``

- `sudo su -` > `exit` then enter 
can use `sudo` with any command 

- how to use `` pipe 
- how to check file permission `ll`
- change file permission `chmod +x filename`
- `sudo usermod -aG docker ubuntu`
- `r` or `w` or `rw` `all` also numbers `400` or `600` for all `700`

#### Updating and upgrading 
- update our ubuntu  OS `apt-get install update `
anytime i have permission issues use `sudo` ie `sudo apt-get install update`

- upgrade our ubuntu os 
`apt-get upgrade -y`

- how to create automate tasks with provisioning scripts 
- automate update and upgrade 

- `cat filename`

- run provision.sh `./provision.sh`


Automate update and upgrade 
1. `sudo nano filename.sh`
2. `sudo apt-get update -y`
3. `sudo apt-get upgrade -y`
4. ctrl x > yes > enter 
5. check content with `cat filename`
6. `ll` to check permision 
7. `sudo chmod +x filename.sh` 
8. `ll` to check again 
9. run filename.sh `sudo ./filename.sh`

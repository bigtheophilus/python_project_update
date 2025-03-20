# This project was done to upgrade the version of python3 in my linux machine .

### it is impotant to know that python is recognised in my linux machiene as Python3

### first the version of python was checked with 

python3 --version

#### output : python3.10.12

### ran: "sudo apt update" to update the repo.

### then "sudo apt install python3.13"
 ### which was the latest version as at this projects.

 ### when i checked the version with the "python3 --version

 ## output: python3.10  which was the old or existing version 

 ## To solve this, alternatives was updated by adding python3.10 and python3.13 to alternatives with the following command

 "update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.10 1" 

 "update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.13 2"

 ## (for the old version. note that the "1"and "2" after "10" and "13" is not parth of the python3 version but a numeric number for the version priority)

 # then:
 "sudo update-alternatives --config python3"

 # output: 

selection                path                       priority        status

*0              /usr/bin/python3.13.2          2                   auto mode

 1             /usr/bin/python3.10.12          1                   manual mode

 2            /usr/bin/python3.3.13.2          2                   manual mode

 press <enter> to keep the current choice[*]. or type selection number:

 ## then i entered the selection number:0
### by that i selcted to work with the python3.13.12 which is the latest verion.
# ckecked the python3 version by: 

"python3 --version"

## output: python3.13.2  which shows the latest version of python is now installed and running on my OS

"sudo rm /usr/bin/python3

"sudo ln -s python3.13 /usr/bin/python3" 

## Note: there were alot of errors or challenges during the execution of this project. refer to the images to see.
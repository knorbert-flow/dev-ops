# Linux 1 - Final Practice

### Setup

- Use SSH to connect to your Virtual Desktop
- Create a new directory in your */home* directory called *final_practice*. This will be your working directory for the following tasks.
- Change your working directory to *final_practice*. 



**NOTE: You should *never* change your working directory while completing any of the following tasks.**
**NOTE: You are allowed to use previous class materials as a reference or ask for help at any time**

----

### Practice Tasks

- Create the following directories in your current directory **only using one command for each**:
  - tree/branch/leaf
  - continent/country/city/street
  - organism/molecule/atom
- Modify the permissions to the directories in the following way:
  - tree:
    - user: every permission
    - group: read access only
    - others: no access
  - continent:
    - user: every permission
    - group: read and write access
    - others: read access
  - organism:
    - user: read access only
    - group: no access
    - others: no access
- Create a file called *trash.txt* in your current directory
- Create a CRON job which attempts to delete this trash.txt every minute
- Create a copy of your cron file into the *continent* directory with the name *copy_of_cron.txt* **with one command**
- Save the string *"I am having so much fun using Linux"* into a new file called *truth.txt* which should be located in *tree/branch/leaf* **with one command**
- Save the output of the **ls -l** command into a file called *list_of_directories.txt* which should be located in the *continent/country* directory
- Edit the *list_of_directories.txt* file with **nano**, and add your name in a new line at the end of the file 
- Attempt to install the **nano** package and append the output to the end of the *list_of_directories.txt*

>  *Nano is most likely already installed. There is no need to delete and install it again, we just need the output of what the package manager returns with after attempting the install.* 

- Save the command line history to *my_history.txt* which should be located in the *tree* directory
- Create a new file named *everything* in your current directory which contains everything ( **also should be done in one line** ) from the following files:
  - copy_of_cron.txt
  - my_history.txt
  - truth.txt
  - list_of_directories.txt

----

### Finishing up

- Disconnect from the **SSH** session
- Reconnect to the Virtual Machine using **SFTP**
- Download everything.txt to your local machine
- Send me  the file you just downloaded
- Close the **SFTP** connection

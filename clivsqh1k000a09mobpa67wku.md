---
title: "Day-2 of #90DaysOfDevOps"
datePublished: Sat Jun 10 2023 14:16:46 GMT+0000 (Coordinated Universal Time)
cuid: clivsqh1k000a09mobpa67wku
slug: day-2-of-90daysofdevops
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1686746050804/3409077e-bfaa-473e-aca1-ba62433bbbf8.avif
tags: devops, 90daysofdevops, 90daysofdevops-chanllenge, 90daysofdevops-trainwithshub

---

Welcome to Day-2 of the #90DaysOfDevOps challenge, today we will be exploring and learning some basic Linux commands like Listing Commands and Directory Commands. These commands are crucial to managing Files and Folders in Linux systems. Let's dive into these commands along with some examples.

### Listing Command

The `ls` command is used to list down all files, directories, and subdirectories in the present working directory.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686748043177/979240ce-5d65-435f-8049-9be8d2659851.png align="center")

let's look at ls along with various flags and some examples:

```bash
ls [option flag] [arguments]
```

* `ls -l`: This command is used to list the files and directories in a long list format with extra information like Permission, Owner, Size, and Modification date.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686748148523/96c5881f-c821-49ae-a486-516edb6d8930.png align="center")
    
    `ls -a`: It lists all files and directories including hidden files and directories that start with a dot (.).
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686748315484/998dbd76-f5ea-4ae5-8058-b6969177c0a2.png align="center")
    
    `ls *.sh`: It lists down all the files with the .sh extension, it is used when a user wants to filter based on some specific pattern.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686748646608/d6580e1e-d119-4681-9582-42df21317114.png align="center")
    
* `ls -i`: It lists files and directories along with their index number(inodes).
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686748848908/3040242d-7076-420f-94de-c328b75b06c8.png align="center")
    
    `ls -d */`: It lists only directories that is allowing the user to view the directory structure without files and you can also specify a pattern to narrow down the output.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686749325220/39f426a6-e360-4866-a21d-0d6ee32e70c3.png align="center")
    

### Directory Commands

* `pwd:` This command prints the Present Working Directory.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686749610880/531e87da-c6ab-4a0d-b995-b893eaf34e3a.png align="center")
    
    `cd path_to_directory`: This command changes the current path to provided path of a directory.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686749779617/686b4a07-8f05-4064-be61-97d0052cd6a4.png align="center")
    
    `cd ~ or just cd`: This command changes the directory to the home directory.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686749892182/a024ecc1-106c-4ae8-9927-203b7bd51318.png align="center")
    
    `cd -`: It allows you to go back to the last working directory.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686750018427/a4d10624-603c-46d4-bf2f-a615a07456da.png align="center")
    
    `cd ..`: This command allows you to back one step backward in the directory structure.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686750140801/2a10f76a-2b33-40a8-870a-5bff9f48b521.png align="center")
    
    `cd ../..`: This command allows you to move two steps backward in the directory structure.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686750348175/f4407e6b-3fba-4906-bfde-a4bd8f7d0afe.png align="center")
    
    `mkdir directoryName`: This command is used to make a directory. Here are some examples.
    
* ```bash
      mkdir newFolder # Creates a new folder named 'newFolder'
      
      mkdir .NewFolder # Creates a hidden directory (prefixing with a dot)
      
      mkdir A B C D # Creates multiple directories at the same time
      
      mkdir /home/user/Mydirectory # Creates a new folder in a specific location
      
      mkdir -p A/B/C/D # Creates a nested directory structure
    ```
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686750989243/6df73652-aa5b-4dab-9631-abcd15c3ac5e.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686751015411/5ca83e48-fb4a-4bfd-a797-d66e3bd4c3e8.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686751035397/4cd0dd64-bda4-462e-8e02-ca0bc257f1b9.png align="center")

Congratulations! We've learned some of the basic Linux commands for listing files and directories, navigating through directories, and creating new folders. T

Stay tuned for Day 3 of the #90DaysOfDevOps challenge, where I'll explore more advanced Linux commands and their practical applications.

Connect with me on [Twitter](https://twitter.com/Gaurav52856773), [Linkedin](https://www.linkedin.com/in/gaurav-mathur2702), and [Github](https://github.com/GMATHUR90).

If you found this blog post helpful, please consider sharing it with others who might benefit from it and share your valuable feedback.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686751780398/45207d61-4a84-4f37-affc-2d8180336b17.gif align="center")
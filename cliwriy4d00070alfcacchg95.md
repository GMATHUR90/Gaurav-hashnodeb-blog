---
title: "Day-3 of #90DaysOfDevOps"
datePublished: Sun Jun 11 2023 06:30:05 GMT+0000 (Coordinated Universal Time)
cuid: cliwriy4d00070alfcacchg95
slug: day-3-of-90daysofdevops
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1686753946623/e123e4df-e35f-4121-b506-9ac6f3c3eda7.avif
tags: devops, 90daysofdevops, 90daysofdevops-devops-projectdevelopment-nonitbackground-github-docker-cloudplatforms-ec2-aws-elasticbeanstalk-lambdafunctions-devopspipelines-terraform-jenkins-docker-devsecops-scm-git-gitlab-bitbucket-buildtools-griddle-maven-ant-msbuild-monitoringtools-prometheus-grafana-ansible-ai-chatgpt-valueaddition-realworldproblems, 90daysofdevopschallenge, 90daysofdevops-trainwithshub

---

Welcome to Day 3 of the #90DaysOfDevOps challenge. Today we will be exploring some more basic Linux commands that are essential for any DevOps engineer. These commands will help you navigate and manage your Linux system efficiently. So, let's dive in!!!

### a) To view the content of the file

```bash
cat <filename> # To view the content of any text file.
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686754421512/0a37d242-dd28-4013-ac88-369e1af1ffc5.png align="center")

### b) To change the access permissions of files

```bash
chmod 777 <filename> # To provide all access including read,write 
                     #and execute
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686755297530/481031e2-49cc-47a0-bb8e-d13e0ddcea97.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686755324733/2e5f5100-e670-4479-82aa-0260570b9fc4.png align="center")

### c) To check which commands you have run till now.

```bash
history  # To check command which was previously run
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686755410853/a9304caa-71e4-4ba7-9cbc-b4199bdf2e7c.png align="center")

### d) To remove a directory/ Folder.

```bash
rmdir <Directory> # To remove a directory
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686807718001/618e8688-187f-4f8a-a543-bf4d4731db88.png align="center")

### e)To create a fruits.txt file and view the content

```bash
touch <file.txt> # To create a file
echo "Content to be added in file" > file.txt #To add content in a file
cat <filename.txt> # To view the content of any text file.
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686809651641/e4e5e2d1-7c37-4d48-8466-34ca86aa6724.png align="center")

Since no content in Colors.txt why it prints nothing .

### f) Add content in fruit's.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.

```bash
vim filename.txt # Create a text file and add content in it
cat filename.txt # To view the content of any text file.
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686809743543/0947821a-544a-4998-84a6-5fb29b494fc5.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686808269700/693f07b4-3ff5-495a-945f-09e8b99bd4e6.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686809859406/8fd77316-554c-4ca1-b189-9d6ce80962d9.png align="center")

### g) To Show only the top three fruits from the file.

```bash
head -n 3 filename # To show top three content in the file
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686808488270/7baee72e-abee-4e60-99fb-5657e3ce44f3.png align="center")

### h) Show only the bottom three fruits from the file.

```bash
tail -n 3 filename # To show bottom 3 content from the file
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686808627896/34c112a7-8647-47cf-9013-5b96f277518a.png align="center")

### i) To create another file Colors.txt and to view the content.

```bash
touch <file.txt> # To create a file 
cat <filename.txt> # To view the content of any text file.
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686808806966/6a5da632-ccbb-4346-8edf-aa979375ff97.png align="center")

Since no content in Colors.txt why it prints nothing .

### j)Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, and Grey.

```bash
echo -e "Red\nPink\nWhite\nBlack\nBlue\nOrange\nPurple\nGrey" > filename.txt
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686809172942/a31f6f33-015e-41e7-8098-3c702b7e8139.png align="center")

### k) To find the difference between fruits.txt and Colors.txt files.

```bash
diff <firstfile.txt> <secondfile.txt> #The diff command will show 
                                      # the lines that are different 
                                      #between the two files, 
                                      #highlighting any changes made.
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1686810014162/8e41bd11-3ef9-469e-8659-b805775b913f.png align="center")

These are some basic Linux commands that will prove helpful throughout your DevOps journey. Understanding and practicing these commands will enable you to navigate and manage your Linux system with ease.

That's all for Day-3 of the #90DaysOfDevOps challenge. Stay tuned for Day 4 of the #90DaysOfDevOps challenge, where I'll explore basic Linux Shell scripting for DevOps Engineers.

Connect with me on [Twitter](https://twitter.com/Gauravmtwt), [Linkedin](https://www.linkedin.com/in/gaurav-mathur2702), and [Github](https://github.com/GMATHUR90).

If you found this blog post helpful, please consider sharing it with others who might benefit from it and share your valuable feedback.

![](https://t3.ftcdn.net/jpg/03/04/16/56/360_F_304165657_LYpZdhDBGPdP1LNVBhF2bS5XyssZ52WG.jpg align="left")
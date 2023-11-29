# Shell-Script-Labs

# LAB1

## Using sed utility

### 1- Display the lines that contain the word “lp” in /etc/passwd file.
![1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/a271cce4-f71c-4b91-8243-2b91edfd1d56)

### 2- Display /etc/passwd file except the third line.

![2](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/8dfd5e04-fb35-4554-8d64-c0c8ded6ef5a)

### 3- Display /etc/passwd file except the last line.

![3](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/7a648235-31e5-4143-8c88-f70d4002b945)
### 4- Display /etc/passwd file except the lines that contain the word “lp”.

![4](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/a177bcff-e13d-4537-af16-16d49150e1e9)
### 5- Substitute all the words that contain “lp” with “mylp” in /etc/passwd file.

![5](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/159d415d-16c5-4df2-b73b-ea1a410ecb64)

## Using awk utility

### 1- Print full name (comment) of all users in the system.

![1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/ef2ed5d9-19e9-4e61-8b1b-173056e590c2)
### 2- Print login, full name (comment) and home directory of all users.( Print each line preceded
### by a line number)

![2](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/9e82df92-75f3-4951-85bb-c4755de26145)
### 3- Print login, uid and full name (comment) of those uid is greater than 500

![3](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/aa4a907a-b87e-4caa-bd27-e8f9322c0724)

### 4- Print login, uid and full name (comment) of those uid is exactly 500

![4](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/1591b259-0412-49a5-ae62-c837640d890c)
### 5- Print line from 5 to 15 from /etc/passwd

![5](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/68eb9adf-d622-4fe9-9908-df88770f450e)
### 6- Change lp to mylp

![6](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/87bc6a1c-f212-4cc1-b5f7-4fa156fcf29e)
### 7- Print all information about greatest uid.

![7](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/c27e4100-3cf5-4f5d-852e-265a775a2551)
### 8- Get the sum of all accounts id’s.

![9](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/e23a400c-593f-49fa-aecc-07199ec0c2aa)

## ........................................................................................

# LAB2

### 1. Create a script that asks for user name then send a greeting to him.
![1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/b28c0f09-b3e4-4b58-b584-d5f79eaf1861)

![1 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/c55abf4f-adde-4ef5-9bfe-2c79abdf5ed5)

### 2. Create a script called s1 that calls another script s2 where:
### a. In s1 there is a variable called x, it's value 5
### b. Try to print the value of x in s2 by two different ways.

#### The first way
![2 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/2ae61b6e-df06-43be-9899-d56608bf50a5)
![2 s2](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/7c3dda0c-0277-4c67-beb0-5280004259d5)
#### The second way
![2 s1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/27953a6e-af41-4c7e-a399-edaa14e82abc)
![2 2](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/0ed607ca-9f09-4b01-83e6-0c989cec0a3e)

### 3. Create a script called mycp where:
### a. It copies a file to another
### b. It copies multiple files to a directory.
![3 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/d7a4e5e2-0489-4d97-9e69-708ddd677d08)
![3](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/693bae5e-b4bd-4bde-a7bd-44442779a4a5)


### 4. Create a script called mycd where:
### a. It changed directory to the user home directory, if it is called without arguments.
### b. Otherwise, it change directory to the given directory.
![4 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/c591c9c5-57ca-4a0e-b789-41ed3a6ac7a4)
![4](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/54da3960-f417-46a6-820e-c5a73dd10101)


### 5. Create a script called myls where:
### a. It lists the current directory, if it is called without arguments.
### b. Otherwise, it lists the given directory.
![5 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/53021d2c-ca2e-4658-ad56-95a8c7dec5ea)
![5](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/770183bb-4c69-41a3-bcae-2ed17d272aec)

### 6. Enhance the above script to support the following options individually:
### a. –l: list in long format
### b. –a: list all entries including the hiding files.
### c. –d: if an argument is a directory, list only its name
### d. –i: print inode number
### e. –R: recursively list subdirectories
![6](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/cc83b2d2-96e8-4b7e-ada3-ad65da10e949)
![6 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/c05a1602-31bd-4353-bdac-a64550fef304)


### 7. Create a script called mytest where:
### a. It check the type of the given argument (file/directory)
### b. It check the permissions of the given argument (read/write/execute)
![7](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/7ac5cb53-7327-4bd1-be91-26f75f3096ed)
![7 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/fdc4760b-c9d2-4727-a121-80ba83608525)


### 8. Create a script called myinfo where:
### a. It asks the user about his/her logname.
### b. It print full info about files and directories in his/her home directory
### c. Copy his/her files and directories as much as you can in /tmp directory.
### d. Gets his current processes status.



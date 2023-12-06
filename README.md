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



## ................................................................................

# LAB3

### 1. Write a script called mycase, using the case utility to checks the type of character
### entered by a user:
### a. Upper Case.
### b. Lower Case.
### c. Number.
### d. Nothing.
![1 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/694a0b71-aac3-45c3-84b7-1bd76457b42e)

![1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/405fc3de-b505-4ccc-9788-5a1fa04ea01f)

### 2. Enhanced the previous script, by checking the type of string entered by a user:
### a. Upper Cases.
### b. Lower Cases.
### c. Numbers.
### d. Mix.
### e. Nothing.
![2 2](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/7aa195c9-b84c-4ea7-a566-abd22d6a50fc)

![2](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/53026da5-2cc9-402e-887e-075ab358d8d8)

### 3. Write a script called mychmod using for utility to give execute permission to all files and
### directories in your home directory.
![3 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/771e4265-e006-4171-90c3-8096e077432e)

![3](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/e8d660b0-44f0-493e-86e8-8ad571574add)

### 4. Write a script called mybackup using for utility to create a backup of only files in your
### home directory.
![4](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/ff41567e-4990-487d-af5f-dacdbfd8a799)

![4 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/c44fe33d-39a6-4432-bbec-8175d96c3f17)


### 5. Write a script called mymail using for utility to send a mail to all users in the system.
### Note: write the mail body in a file called mtemplate.
![5](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/faab31eb-0e2d-47b1-952e-cc54d82051d3)


### 6. Write a script called chkmail to check for new mails every 10 seconds. Note: mails are
### saved in /var/mail/username.

### 7. What is the output of the following script
### typeset –i n1
### typeset –i n2
### n1=1
### n2=1
### while test $n1 –eq $n2
### do
### n2=$n2+1
### print $n1
### if [ $n1 –gt $n2 ]
### then
### break
### else
### continue
### fi
### n1=$n1+1
### print $n2
### done
![Screenshot from 2023-12-06 19-27-58](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/954e4b15-a7b9-46d9-afdb-b05801472450)


### 8. Create the following menu:
### a. Press 1 to ls
### b. Press 2 to ls –a
### c. Press 3 to exit
### Using select utility then while utility.
![8 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/7c5e7d23-09db-4d6d-90c9-7dee6f1f6b13)
![8 2](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/428b4d99-526b-4332-8e94-eb3f232c388b)
![8 3](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/e5ec0f27-90af-4615-92e0-2b0b29f78b0f)
![8](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/d389d0d4-02b1-4281-8b04-ea5e7460d7c0)


### 9. Write a script called myarr that ask a user how many elements he wants to enter in an
### array, fill the array and then print it.
![9](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/02aa551d-9b3e-4992-a34d-a0cadb815128)

![9 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/7a02fd35-896e-42a1-ba5a-ea41480fd6dd)

### 10.Write a script called myavg that calculate average of all numbers entered by a user.
### Note: use arrays
![10 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/baf71df3-528e-4980-be40-d21fa8dc4db9)

![10](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/39b6d902-a7f3-4401-8d44-16f5f46ecf39)

### 11.Write a function called mysq that calculate square if its argument.
![11 1](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/9fd7e68b-7c95-40ce-a5ec-bb8dba01e226)

![11](https://github.com/ahmedkhaled4219/Shell-Script-Labs/assets/146847357/47c69ba2-6bf4-4ed3-bd0a-6fa9619cad80)












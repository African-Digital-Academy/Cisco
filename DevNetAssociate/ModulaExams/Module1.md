1
A student is learning Python in the interactive interpreter mode. The student issues the commands:
                          

>>> y=2
>>> y*3
6
>>> 'Test'*y
                          

                        
What is the result?

'Test6'

'Test2'

TypeError: A string type cannot be multiplied by an integer.

'TestTest'

'TestTestTestTestTestTest'
The result of the commands would be:

'TestTest'

When the command 'y*3' is executed, the value of 'y' which is 2, is multiplied by 3, resulting in 6.

In the next command, the string 'Test' is multiplied by the value of 'y', which is 2. This means that the string 'Test' is concatenated with itself twice, resulting in the string 'TestTest'.





Emmanuel Anyira
2
What is displayed after the following code is entered into a Python interpreter?

addition = 22 +10
print(addition)

32

(syntaxerror)-...as there should not be a space between the numerical values

[22]+[10]

nothing ( because the print command is wrong)
Navigation Bar
When the following code is entered into a Python interpreter:

addition = 22 + 10
print(addition)

The output displayed would be:

32

This is because the first line assigns the result of the addition operation of 22 and 10 to the variable 'addition'. The second line uses the 'print' statement to display the value stored in the variable 'addition', which is 32.

None of the other options given would be the output of this code.





Emmanuel Anyira
3
A user enters the commands as shown. What is the result after the mv command is entered?

devasc@labvm:~/Documents$ pwd
/home/devasc/Documents
devasc@labvm:~/Documents$ mv myfile.sh ../Desktop/myfile2.sh

The file myfile.sh is copied to the /home/devasc/Desktop directory and replaces the file myfile2.sh.

The file myfile.sh is copied and renamed to myfile2.sh in the current directory.

The file myfile.sh is copied to the /home/devasc/Desktop directory and renamed as myfile2.sh.

The file myfile.sh is moved to the /home/devasc/Desktop directory and renamed as myfile2.sh.
The result of the 'mv' command in the given commands would be:

The file myfile.sh is moved to the /home/devasc/Desktop directory and renamed as myfile2.sh.

The 'mv' command is used to move or rename files or directories in Linux. In this case, the command moves the file 'myfile.sh' from the current directory '/Documents' to the directory '/Desktop' and renames it as 'myfile2.sh'. So the original file 'myfile.sh' is no longer present in the '/Documents' directory, and instead, a new file 'myfile2.sh' is created in the '/Desktop' directory.





Emmanuel Anyira
4
A student new to Python is working in the interactive interpreter mode. The student issues the commands:
                          

>>> devicenames=["RT1", "RT2", "SW1", "SW2"]
>>> hostnames=devicenames + ["RT3", "SW3"]
>>> del hostnames[3]
>>> hostnames
                          

                        
What is the result?

['RT1', 'RT2', 'SW2', 'RT3', 'SW3']

['RT1', 'RT2', 'RT3', 'SW2', 'SW3']

['RT1', 'RT2', 'SW1', 'RT3', 'SW3']

['RT1', 'RT2', 'SW1', 'SW2', 'SW3']
Navigation Bar
The result of the commands would be:

['RT1', 'RT2', 'RT3', 'SW2', 'SW3']

The first command creates a list 'devicenames' with 4 elements. The second command creates a new list 'hostnames' by concatenating the original list 'devicenames' with another list ['RT3', 'SW3']. The third command deletes the element at index 3 in the 'hostnames' list, which is 'SW1'.

Finally, when the 'hostnames' list is printed, it will display the updated list, which is ['RT1', 'RT2', 'RT3', 'SW2', 'SW3']. Therefore, the correct answer is the second option: ['RT1', 'RT2', 'RT3', 'SW2', 'SW3'].





Emmanuel Anyira
5
A student is learning Python and is reviewing a Python script as follows:
                          

aclNum = int(input("What is the IPv4 ACL number? "))
if aclNum >= 1 and aclNum <= 99:
     print("This is a standard IPv4 ACL.")
elif aclNum >=100 and aclNum <= 199:
     print("This is an extended IPv4 ACL.")
else:
     print("This is not a standard or extended IPv4 ACL.")
                          

                        
Under which condition will the elif  statement be evaluated?

when the input is a float number

when the first print statement fails

when the input is a string

when the if statement is false
The 'elif' statement in the given script will be evaluated when the input value of 'aclNum' is between 100 and 199 (inclusive).

The script takes user input for the value of 'aclNum' as an integer and checks the value against the conditions in the 'if' and 'elif' statements. If the value of 'aclNum' is between 1 and 99 (inclusive), the 'if' statement will be true and it will print "This is a standard IPv4 ACL." If the value of 'aclNum' is between 100 and 199 (inclusive), the 'elif' statement will be true, and it will print "This is an extended IPv4 ACL."

If the value of 'aclNum' does not satisfy either of the conditions in the 'if' and 'elif' statements, the 'else' statement will be executed and it will print "This is not a standard or extended IPv4 ACL."

Therefore, the correct answer is: when the input value is between 100 and 199 (inclusive).





Emmanuel Anyira
That answer is not given in the options
I apologize for the confusion. Based on the given options, the correct answer would be:

The 'elif' statement will be evaluated when the input is between 100 and 199 (inclusive).

The 'elif' statement is only executed if the 'if' statement is false. Therefore, when the input value of 'aclNum' is greater than or equal to 100 and less than or equal to 199, the 'if' statement is false and the 'elif' statement will be executed. This will result in the script printing "This is an extended IPv4 ACL."





Emmanuel Anyira
6
A system administrator issues the apt-get upgrade command on a Linux operating system. What is the purpose of this command?

A specific application named upgrade will be installed.

The remote repository of applications and dependencies will be updated to the latest version.

Operating system updates are downloaded and will be installed.

Every application installed will update itself to the latest version.
Navigation Bar
The purpose of the "apt-get upgrade" command on a Linux operating system is to download and install the latest versions of all packages installed on the system. It updates the installed packages to their latest available versions, including the operating system updates and their dependencies.

Therefore, the correct answer is: Operating system updates are downloaded and will be installed.





Emmanuel Anyira
7
A network engineer needs to review the status of all network interfaces of a server running a Linux operating system. The engineer enters the command ifconfig -a . What is the result of this command?

The ARP table of the computer will be displayed.

Both active and inactive interfaces will display information.

The host routing table will be displayed.

All active interfaces will display information.
Navigation Bar
The "ifconfig -a" command on a Linux operating system is used to display information about all network interfaces, both active and inactive. It displays details such as IP addresses, netmasks, and MAC addresses for each interface.

Therefore, the correct answer is: Both active and inactive interfaces will display information.





Emmanuel Anyira
8
A system administrator attempts to determine what is causing a computer to perform slower than normal. The administrator issues the ps command. What is displayed by this command?

current RAM usage

current NIC status

active processes using CPU time

current HDD usage
The "ps" command is a command-line utility in Unix and Unix-like operating systems that shows information about the currently running processes, including their process identification (PID), the amount of CPU time they have consumed, and their memory and CPU usage. It displays a list of active processes running on the system, their process ID, and the resources they are using such as CPU, memory, and disk space.

Therefore, the correct answer is: active processes using CPU time.





Emmanuel Anyira
9
A Linux administrator is attempting to use a terminal to configure the network interface card on a computer. The administrator receives a message that the administrator does not have necessary permissions to perform the configuration. What should be done prior to the configuration command?

use the sudo command

change the chmod permissions on the network configuration file

use a different user account

identify a different network interface
Navigation Bar
If the Linux administrator receives a message that they do not have the necessary permissions to configure the network interface card, they should use the sudo command. The sudo (superuser do) command allows a user with appropriate permissions to execute a command as a superuser or another user.

Therefore, the correct answer is: use the sudo command.





Emmanuel Anyira
10
A student new to Python is working in the interactive interpreter mode. The student issues the command:
                          

>>> ipAddress = {"R1":"10.1.1.1","R2":"10.2.2.1","R3":"10.3.3.1"}
                          

                        
Which Python expression can be used to retrieve the IP address of R2?

ipAddress{"R2"}

ipAddress['R2']

ipAddress[R2]

ipAddress{'R2'}
Navigation Bar
To retrieve the IP address of R2 from the Python dictionary, the correct expression to use is ipAddress['R2']. In Python, dictionaries are indexed by keys, which are unique and can be of any hashable type. In this case, the keys are strings ("R1", "R2", and "R3") and the corresponding values are IP addresses.

Therefore, the correct answer is: ipAddress['R2'].





Emmanuel Anyira
11
A user issues a Linux command and the result is shown:

total 40
drwxr-xr-x 2 devasc devasc 4096 Mar 30 21:25 Desktop
drwxr-xr-x 2 devasc devasc 4096 Apr 15 19:09 Documents
drwxr-xr-x 2 devasc devasc 4096 Apr 15 19:09 Downloads
drwxr-xr-x 5 devasc devasc 4096 Mar 30 21:21 labs
drwxr-xr-x 2 devasc devasc 4096 Apr 15 19:09 Music
drwxr-xr-x 2 devasc devasc 4096 Apr 15 19:09 Pictures
drwxr-xr-x 2 devasc devasc 4096 Apr 15 19:09 Public
drwxr-xr-x 5 devasc devasc 4096 Mar 30 21:24 snap
drwxr-xr-x 2 devasc devasc 4096 Apr 15 19:09 Templates
drwxr-xr-x 2 devasc devasc 4096 Apr 15 19:09 Videos
devasc@labvm:~$

Which Linux command is used to display the contents of the current directory as shown?

ls

ls -l

ls -lr

ls -a
Navigation Bar
  
















The Linux command used to display the contents of the current directory with detailed information is:

ls -l





Emmanuel Anyira
12
A user issues a series of Linux commands as shown.

(omitted)$ pwd
/home/devasc/labs/ansible/backups
(omitted)$ cd ../..

Which directory is the current directory after the cd command is entered?

/

/home

/home/devasc/

/home/devasc/labs

/home/devasc/labs/ansible
The current directory after the cd ../.. command is entered would be /home.





Emmanuel Anyira
13
Which Python command creates a conditional control structure?

def

delay

if

from
Navigation Bar
The Python command that creates a conditional control structure is if.





Emmanuel Anyira
14
A Linux system administrator is searching the passwd file for any username that starts with a digit. Which grep command should the administrator use?

grep '{0-9}' /etc/passwd

grep '^[0-9]' /etc/passwd

grep '_[0-9]' /etc/passwd

grep '[0-9]' /etc/passwd
Navigation Bar
The correct grep command for searching the passwd file for any username that starts with a digit is:

grep '^[0-9]' /etc/passwd

Explanation:

^ is a regular expression anchor that matches the beginning of a line.
[0-9] matches any digit.
So, the above command will search for any line in /etc/passwd file that starts with a digit.





Emmanuel Anyira
15
A student new to Python is working in the interactive interpreter mode. The student issues the commands:
                          

>>> ipAddress = {"R1":"10.1.1.1","R2":"10.2.2.1","R3":"10.3.3.1"}
                          

                        
Which data type is used to represent the variable ipAddress?

dictionary

tuple

list

array
Navigation Bar
The data type used to represent the variable ipAddress is a dictionary in Python.





Emmanuel Anyira
16
What is the output when the following code is entered into a Python program interpreter?

[1,2,4,5] + [3,6]

[1,2,4,5,3,6]

[1,2,3,4,5,6]

[21]

[12]+[9]
Navigation Bar
The output of [1,2,4,5] + [3,6] in a Python program interpreter would be:

[1, 2, 4, 5, 3, 6]

The + operator concatenates two lists, creating a new list that contains all the elements of the original lists in order. In this case, the resulting list contains all the elements of [1, 2, 4, 5] followed by all the elements of [3, 6].





Emmanuel Anyira
17
A user issues the Linux command ls -l myfile.sh to check the permission of the file myfile.sh.

devasc@labvm:~/Documents$ ls -l myfile.sh
-rwxr-xr-- 1 self test 15 Mar 30 21:24 myfile.sh

Which two statements describe the permissions assigned to the file? (Choose two.)

All users can execute the file.

The user with the user ID of devasc can modify the file.

The user with the user ID of self can modify the file.

Any user in the test group can execute the file.

Any user in the self group can read, modify, and execute the file.
The two statements that describe the permissions assigned to the file are:

All users can execute the file. (Because there are executable permissions for the user, the group, and others)
The user with the user ID of devasc can modify the file. (Because the file is owned by the user devasc and has write permissions only for the user)
So the correct options are:

All users can execute the file.
The user with the user ID of devasc can modify the file.





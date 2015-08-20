


Download Git at "https://git-scm.com/downloads"
Create a GitHub account at "https://github.com/join"

First open terminal command to get a text file then write a C program by using the popen function and string tokenizer function to split the outputs of popen function to retrieve a local IP address (eth0 or eth1) (NOT localhost / 127.0.0.1) of a particular device/machine.


Steps
Get Local IP Address:
1.) Open text file name as "horse" and complete the popen function given by question to retrieve Local IP address(eth0).
    ~$ gedit horse.c
   
2.) Compile and run program
    ~$ gcc horse.c -o horse 
    ~$ ./horse
 
3.) Ensure get the correct Local IP Address compare
    ~$ ifconfig 

To split the outputs of popen function:
1.) Open and add string tokenizer function to split the outputs of popen function.
2.) After add the string tokenizer function, using this command to execute and run program.
    ~$ gcc horse.c -o horse (compile program)
    ~$ ./horse (run program)
3.) Successfully split thes eth0 IP address in the terminal.

Assign Tasks:
-Wong Wei Ye completed the task of the first onw that get the all local IP-Address(eth0).
-SIM Wei Xiong completed the task of using the string tokenizer function to split the output and write read me files together with WeI Ye.

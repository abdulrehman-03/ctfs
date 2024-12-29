### Challenge

![Challenge](./challenge.png)


### Solution

We have two files, `user.txt` and `passwd.txt`. We have to find the passwd for user `osman`. All users have their respective password in the password file. So we can simply see the line number at which the user osman is located and user file, and then see the respective password in passwd file. 


![Credentials](./credentials.png)


The 337 entry contains which is shift cipher. Shifting values by 25, we get the flag:

![flag](./flag.png)
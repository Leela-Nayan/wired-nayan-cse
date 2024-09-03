# level 13-14

1. Used the ls command and found the ssh key.
2. Used nano and opened the key, and copied.
3. On my local machine, used nano to create a new file and pasted the ssh key into it.
4. Then went through the man page of ssh and found the arguement was -i, so did ssh -i /home/Desktop/nayan/sshkey bandit14@bandit.labs.overthewire.org -p 2220. Got a wrong permissions error for the ssh key.
5. I knew I had to use the chmod command, but didn't know the arguments, so I used the manpage of ssh, and then used chmod u=rwx sshkey
6. Now i reran the command and logged into level14.
7. Next i directly ran cat /etc/bandit_pass/bandit14 and got the password.

Password to log into level 14: sshkey or MU4VWeTyJk8ROof1qqmcBPaLh71DCPvS
# level 16-17

1. Upon reading this level's objective, from my prior knowledge of tinkering with raspi, I knew the first command I'd have to use was nmap, so I just started with the man page of nmap to find the args required for it.

2. Ran the command nmap -p 31000-32000 localhost, and it returned 5 ports.

3. Now I used openssl s_client -connect localhost:[port number] and found the right port by trial and error since there were only 5 ports and I wasn't really in the mood to spend another half an hour going through all the man pages.

4. After finding the port, I sent the current level's password, but instead of getting the next level's password, I got "KEYUPDATE" back. I remember seeing that word under the objective, and upon reading, the question asked me to see the connected commands in the man page. The solution was literally in the man page, I just had to include another -quiet argument in my command.

5. Reran the command with -quiet arg and got the sshkey for the next level.

Password for login into level 17: sshkey
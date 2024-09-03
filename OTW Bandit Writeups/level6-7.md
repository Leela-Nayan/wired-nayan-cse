# level 6-7

This one took me a bit of a time, because I had to read the man page of find for all the arguments and even after writing the command, I got a lot of results. I was dumbfounded and was just randomly scrolling through all the hits when I saw only one file did not have "Permission denied" and that one file conveniently also had the name "bandit7.password", so I just used the cat command next and printed its contents.

Commands Used: find / -type f -user bandit7 -group bandit6 -size 33c, 
               cat /var/lib/dpkg/info/bandit7.password

Password to login into level 7: morbNTDkSW6jIlUcOymOdMaLnOlFVAaj
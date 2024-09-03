# level 18-19

1. This was I think the first level where I literally didn't have any idea whatsoever as to what to do. Because, before I could even try anything out, I would be logged out because the .bashrc file was modified.

2. So i raised a ticket, and one senior just hinted at me to take a look at the man page and to see if there were any possibilities where I could do something before logging in.

3. And that was literally printed in fine print of the man page, that specific solution. That I could execute commands if I mentioned them as args in the ssh command.

4. So to test, I included the ls command and ran: ssh bandit18@bandit.labs.overthewire.org -p 2220 ls, and then entered the password, and it gave me an output saying that there was a readme file present.

5. So naturally, my next command was: ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme, and voila, just like that, I got my password.

Password to login into level 19: cGWpMaKXVwDUNgPAVJbWYuGHVn9z13j8
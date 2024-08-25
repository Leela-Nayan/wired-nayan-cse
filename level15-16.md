# level 15-16

1. Yet again, I had to start from scratch for this level. Ngl, figuring out the command took some time. Started with man page of openssl because the command had ssl in its name, figured that would be it.
2. Upon reading the man page, got to know that we would need to include another sub command named s_client, so included that and ran the following command: openssl s_client localhost 30001, got an error and it asked me to run openssl s_client -help.
3. After running that, got to know I missed an arguement named -connect and that we would have to write the host and port not with a space between them, but with a colon.
4. So now I ran openssl s_client -connect localhost:30001, gave the password for this level and got the password for the next level.

Password to login into level 16: kSkvUpMQ71BYyC4GBPvCvT1BfWRy0Dx

![alt text](Screenshots/level15-1.png) ![alt text](Screenshots/level15-2.png) ![alt text](Screenshots/level15-3.png)
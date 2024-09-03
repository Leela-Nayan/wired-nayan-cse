# gh0st_h0rs3

1. In this challenge, I took a bit of help from Arjun anna. I did read the bi0s wiki page prior to the CTF but all I understood was that the CAN network was primarily used for communication between different parts in a vehicle.

2. But seeing the log file, I had no clue what to do. So Arjun anna told me that there would be a GitHub page and told me to look for it. 

3. Found the GitHub Page, looked for the CAN IDs of Mustang S550 and he asked me to look for the RPM ID because the question asked for it. But the RPM ID was not mentioned in our log file, so I was looking for similar IDs when the throttle position ID gave 7-8 matches.

4. After filtering them and seperating the payload, I tried base64 first, didn't give any readble things, then I tried hex, and it worked. 

5. Joining all of them gave the flag.
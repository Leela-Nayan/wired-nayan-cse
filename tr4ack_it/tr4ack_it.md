# tr4ack_it

1. As soon as I read the last line, I knew somewhere along the way that I'd have to grep for 'deriw' instead of wired or 'galf' instead of flag. But little did I know, getting the flag would be way harder than that.

2. Ran the file command on the file, it returned that it was a compressed squashfs filesystem. Anna suggested me to unsquash it, I unsquashed it and then grepped for wired, didn't get any readable strings. Then grepped for 'deriw', and it returned logs. 

3. Searched up the command to print grep results to a .txt file, ran it and then converted that .txt file to a .xlsx cuz Anna asked me to sort through it chronologically and analyse it and that seemed like the fastest way to me. 

4. Found differences in "Numbers" of entries, found the differences and anna hinted at me that it could be ASCII code. 

5. Converted the differences to ASCII and got the flag.
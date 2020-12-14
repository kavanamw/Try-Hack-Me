Command for wfuzz
```
wfuzz -c -z file,big.txt http://shibes.xyz/api.php?breed=FUZZ
```
Use GoBuster (against the target you deployed -- not the shibes.xyz domain) to find the API directory. What file is there?
```
site-log.php
```
Fuzz the date parameter on the file you found in the API directory. What is the flag displayed in the correct post?
```
THM{D4t3_AP1}
```

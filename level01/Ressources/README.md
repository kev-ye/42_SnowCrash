# First step

We have a hash in /etc/passwd on flag01:42hDRfypTqqnw:3001:3001::/home/flag/flag01:/bin/bash
-> use SCP, get file to local
    -> scp -P 4242 scp://level01@192.168.64.2/../../../etc/passwd /Users/kev_ye/Code/42/snow-crash level01/Ressources/passwd

# Second step

Using john the ripper to brute force the hash,
-> john passwd
    -> 'abcdefg          (flag01)'
-> flag: f2av5il02puano7naaf6adaaf
# First step

I was tried to check /etc/shadow but no have access
I also check the /etc/passwd, nothing except for a hash with flag01

# Second step

I launch a research to find all flag00 file with 'find' command using -user & -group flag
-> find / -user flag00 -group flag00 2>/dev/null
    -> /usr/sbin/john
    -> /rofs/usr/sbin/john
-> cat these file
    -> cdiiddwpgswtgt
-> use: 'https://www.dcode.fr/cipher-identifier' to identifier the cipher
    -> we will know this is a caesar cipher or ROT cipther
    -> brut-the-force using tool in 'dcode' about caesar cipher
    -> only 'nottoohardhere' have some logic sentense
-> flag: x24ti5gi3x0ol2eh4esiuxias
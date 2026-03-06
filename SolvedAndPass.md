#### Lv0  : ssh -p 2220 -l bandit0  bandit.labs.overthewire.org 
#### Lv1  : ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If  /   cat ./-
#### Lv2  : 263JGJPfgU6LtdEvgfWU1XP5yac29mFx  /   cat "./--space in file--"
#### Lv3  : MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx  /   cat [tab]
#### Lv4  : 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ  /   cat ./-file007
#### Lv5  : 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw  /   find . -size 1033c ! -executable
#### Lv6  : HWasnPhtq9AVKe0dmk45nxy20cvUa6EG  /   
bandit6@bandit:~$ find / -size 33c -group bandit6 -user bandit7 2>/dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
#### Lv7  : morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj  /   cat data.txt | grep millionth
#### Lv8  : dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc  /   sort data.txt | uniq -u (uniq chi dem so trung lap ke nhau nen sort )
#### Lv9  : 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM  /   strings data.txt
#### Lv10 : FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey  /   base64 -d data.txt
#### Lv11 : dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr  /   cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'  (tr la rot13)
#### Lv12 : 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4  /   
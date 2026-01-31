# Bandit
## Levels 11-23
### Level 11
**Commands Used**
```bash
1) ssh bandit11@bandit.labs.overthewire.org -p 2220
2) cat data.txt | tr 'a-zA-Z' 'n-za-mN-ZA-M'
```
**Password**
```bash
7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
```

### Level 12
**Commands Used**
```bash
1) ssh bandit12@bandit.labs.overthewire.org -p 2220
2) mktemp -d
3) cd /tmp/tmp.6mIsyuNYgD
4) cp ~/data.txt /tmp/tmp.6mIsyuNYgD
5) mv data.txt data.hex
6) xxd -r data.hex data.bin
7) file data.bin
8) mv data.bin data.gz
9) gunzip data.gz
10) file data
11) mv data data.bz2
12) bunzip2 data.bz2
13) file data
14) mv data data.gz
15) gunzip data.gz
16) file data
17) tar -xf data
18) ls 
19) file *
20) tar -tf data
21) tar -xf data
22) ls -l
23) file *
24) tar -xf data5.bin
25) ls -l
26) file *
27) mv data6.bin data6.bz2
28) bunzip2 data6.bz2
29) file data6
30) tar -xf data6
31) ls
32) file *
33) mv data8.bin data8.gz
34) gunzip data8.gz
35) file data8
36) cat data8

```
**Password**
```bash
FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
```

### Level 13
**Commands Used**
```bash
1) scp -P 2220 bandit13@bandit.labs.overthewire.org:/home/bandit13/sshkey.private .
2) ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220
3) cat /etc/bandit_pass/bandit14
```
**Password**
```bash
MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
```

### Level 14
**Commands Used**
```bash
1) nc localhost 30000
2) MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
```
**Password**
```bash
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
```

### Level 15
**Commands Used**
```bash
1) ssh bandit15@bandit.labs.overthewire.org -p 2220
2) openssl s_client -connect localhost:30001
3) 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
```
**Password**
```bash
kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
```

### Level 16
**Commands Used**
```bash
1) ssh bandit16@bandit.labs.overthewire.org -p 2220
2) nmap -p 31000-32000 localhost
3) openssl s_client -connect localhost:31790 -quiet
4) kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
5) exit
6) vim key
7) chmod 400 key
8) ssh -i key bandit17@bandit.labs.overthewire.org -p 2220
9) cat /etc/bandit_pass/bandit17
```
**Password**
```bash
EReVavePLFHtFlFsjn3hyzMlvSuSAcRD
```

### Level 17
**Commands Used**
```bash
1) diff passwords.old passwords.new
```
**Password**
```bash
x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO
```

### Level 18
**Commands Used**
```bash
1) ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme
```
**Password**
```bash
cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8
```

### Level 19
**Commands Used**
```bash
1) ssh bandit19@bandit.labs.overthewire.org -p 2220
2) ls
3) ./bandit20-do
4) ./bandit20-do cat /etc/bandit_pass/bandit20
```
**Password**
```bash
0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO
```

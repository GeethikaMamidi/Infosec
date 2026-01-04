# Bandit

## Levels 6-10

### Level 6

**Commands Used**

```bash
ssh bandit6@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
```

**Commands Used**

```bash
ls -a
```

**Output**

```bash
.  ..  .bash_logout  .bashrc  .profile
```

**Commands Used**

```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
```

**Output**

```bash
/var/lib/dpkg/info/bandit7.password
```

**Commands Used**

```bash
cat /var/lib/dpkg/info/bandit7.password
```

**Output**

```bash
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
```

### Level 7

**Commands Used**

```bash
ssh bandit7@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
```

**Commands Used**

```bash
ls -a
```

**Output**

```bash
.  ..  .bash_logout  .bashrc  data.txt  .profile
```

**Commands Used**

```bash
grep millionth data.txt
```

**Output**

```bash
millionth       dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
```

### Level 8

**Commands Used**

```bash
ssh bandit8@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
```

**Commands Used**

```bash
ls -a
```

**Output**

```bash
.  ..  .bash_logout  .bashrc  data.txt  .profile
```

**Commands Used**

```bash
sort data.txt | uniq -u
```

**Output**

```bash
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
```

### Level 9

**Commands Used**

```bash
ssh bandit9@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
```

**Commands Used**

```bash
ls -a
```

**Output**

```bash
.  ..  .bash_logout  .bashrc  data.txt  .profile
```

**Commands Used**

```bash
strings data.txt | grep "="
```

**Output**

```bash
========== the
9=H`
[!#=Z
========== password
xWf=
f\Z'========== is
e=i{\#
/1=s
nS=F
M=Sl
=LGT
y =1
========== FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
'+Y=+
```

### Level 10

**Commands Used**

```bash
ssh bandit10@bandit.labs.overthewire.org -p 2220
```

**Password**

```bash
FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
```

**Commands Used**

```bash
ls -a
```

**Output**

```bash
.  ..  .bash_logout  .bashrc  data.txt  .profile
```

**Commands Used**

```bash
base64 -d data.txt
```

**Output**

```bash
The password is dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
```

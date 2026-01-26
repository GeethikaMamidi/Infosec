# Linux Luminarium
## Module 8: Data Manipulation
### Challenge 1: Translating characters 

**Commands used:**
``` bash
1) /challenge/run | tr 'a-zA-Z' 'A-Za-z'
```

**Flag:**
pwn.college{QgwztY8fq1BWvF6P-fHmjO_Harr.01MxEzNxwyM1YDM1EzW}


### Challenge 2: Deleting characters 

**Commands used:**
``` bash
1) /challenge/run | tr -d ^%
```

**Flag:**
pwn.college{Q0KhhFXP9Q24efgwV3ci5wDiQBs.0FNxEzNxwyM1YDM1EzW}


### Challenge 3: Deleting newlines

**Commands used:**
``` bash
1) /challenge/run | tr -d "\n"
```

**Flag:**
pwn.college{8flrH2j3PjhqPCsR0-LXQ1T5uSn.0VNxEzNxwyM1YDM1EzW}


### Challenge 4: Extracting the first lines with head

**Commands used:**
``` bash
1) /challenge/pwn | head -n 7 | /challenge/college
```

**Flag:**
pwn.college{oCPjl2j24iBQkAjWAcX_d0C_CK3.0lNxEzNxwyM1YDM1EzW}


### Challenge 5: Extracting specific sections of the text

**Commands used:**
``` bash
1) /challenge/run
2) /challenge/run | cut -d " " -f 2 | tr -d "\n"
```

**Flag:**
pwn.college{wTRJoIMxVGhzo6dzY2hKP1nMtkP.01NxEzNxwyM1YDM1EzW}


### Challenge 6: Sorting data

**Commands used:**
``` bash
1) sort /challenge/flags.txt
```

**Flag:**
pwn.college{w3JVR3ArmJkLQZ-oWmFH5uMwrBH.0FM0MDOxwyM1YDM1EzW}
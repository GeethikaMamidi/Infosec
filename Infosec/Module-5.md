# Linux Luminarium
## Module 5: File Globbing
### Challenge 1: Matching with *
**Goal:**
```bash
Change directory to /challenge using globe '*'
```
**Commands used:**
```bash
1) cd /c*
2) /challenge/run
```

**Flag:** pwn.college{0qPkM5XwTmkAWQ3iNRV2Gua90Es.QXxIDO0wyM1YDM1EzW}

### Challenge 2: Matching with ?
**Goal:**
```bash
Change directory to '/challenge' using globe '?'
```
**Commands used:**
```bash
1) cd /?ha??enge
2) /challenge/run
```

**Flag:** pwn.college{wG0U_Be0RexFSan7Oq7zLMiwJzi.QXyIDO0wyM1YDM1EzW}

### Challenge 3: Matching with []
**Goal:**
```bash
Run using globe '[]' with a single argument.
```
**Commands used:**
```bash
1) cd /challenge/files
2) /challenge/run file_[bash]
```

**Flag:** pwn.college{sTCjUKeq0dxx8Qz5-HDhxDM1Raw.QXzIDO0wyM1YDM1EzW}

### Challenge 4: Matching paths with []
**Goal:**
```bash
Run with a single argument that bracket-globs into the absolute paths to the files.
```
**Commands used:**
```bash
1) /challenge/run /challenge/files/file_[bash]
```

**Flag:** pwn.college{0O0iVEZTN8Q4BSRVmXFSxFr08VH.QX0IDO0wyM1YDM1EzW}

### Challenge 4: Multiple globs
**Goal:**
```bash
Run with a single argument containing two '*' globs and letter 'p'.
```
**Commands used:**
```bash
1) cd /challenge/files
2) /challenge/run *p*
```

**Flag:** 
pwn.college{QuUODWoA7dDOXi5klIavawZgR_Y.0lM3kjNxwyM1YDM1EzW}

### Challenge 5: Mixing globs
**Goal:**
```bash
Mix globs to get the flag.
```
**Commands used:**
```bash
1) cd /challenge/files
2) ls
3) /challenge/run [cep]*
```

**Flag:** 
pwn.college{kZk8a1ROcdn3ZqzZJjXV7ERm9gN.QX1IDO0wyM1YDM1EzW}

### Challenge 6: Exclusionary globbing
**Goal:**
```bash
Exclude files that start with p,w,n using globbing with '[!]' or '[^]'.
```
**Commands used:**
```bash
1) cd /challenge/files
2) /challenge/run [!pwn]*
```

**Flag:** 
pwn.college{Y-aCImCG5E52w3z5ZJ9uE1oxhW_.QX2IDO0wyM1YDM1EzW}

### Challenge 7: Tab completion
**Goal:**
```bash
Hit tab to auto-complete the filename.
```
**Commands used:**
```bash
1) ls /challenge
2) cat /challenge/pwn<TAB>
```

**Flag:** 
pwn.college{AVtSAYgu2MMm3mGY3ICfGdxCU27.0FN0EzNxwyM1YDM1EzW}

### Challenge 8: Multiple options for tab completion
**Goal:**
```bash
Hit tab multiple times to auto-complete the filename.
```
**Commands used:**
```bash
1) cd /challenge/files
2) cat /challenge/files/p<TAB>
3) cat /challenge/files/pwnc<TAB>
4) cat /challenge/files/pwncollege-flag
```

**Flag:** 
pwn.college{06EeONkFNy65lqVvVpUwakBGPoQ.0lN0EzNxwyM1YDM1EzW}

### Challenge 9: Tab completion on commands
**Goal:**
```bash
Hit tab to auto-complete the command.
```

**Commands used:**
```bash
1) pwncollege<TAB>
2) pwncollege-379 
```

**Flag:** 
pwn.college{AooT5nFKILngOd3ecRaZs9VPfyS.0VN0EzNxwyM1YDM1EzW}
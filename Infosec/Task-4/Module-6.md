# Linux Luminarium
## Module 6: Practicing Piping
### Challenge 1: Redirecting Output

**Goal:**
Use output redirection to write the word 'PWN' to the filename 'COLLEGE'.

**Commands used:**
``` bash
1) echo PWN > COLLEGE
```

**Flag:**
pwn.college{UqYCDLhNvV7x2iIxNJ1K6H-nVMQ.QX0YTN0wyM1YDM1EzW}

### Challenge 2: Redirecting more Output

**Goal:**
Redirecting the output of '/challege/run' to the file 'myflag' and read it.

**Commands used:**
``` bash
1) /challenge/run > myflag
2) cat myflag
```

**Flag:**
pwn.college{ILShjz96B-vmgVbk7n6P8Q0cp8m.QX1YTN0wyM1YDM1EzW}

### Challenge 3: Appending Output

**Goal:**
Redirect output of '/challege/run' in append mode to the file 'the-flag' and reading it.

**Commands used:**
``` bash
1) //challenge/run >> /home/hacker/the-flag
2) cat the-flag
```

**Flag:**
pwn.college{YD92AyGr3a0iN1XLY4CTZW0FbNQ.QX3ATO0wyM1YDM1EzW}

### Challenge 4: Redirecting errors

**Goal:**
Redirect output of '/challenge/run' to 'myflag' and errors to 'instructions' and read 'myflag'.

**Commands used:**
``` bash
1) /challenge/run > myflag 2> instructions
2) cat myflag
```

**Flag:**
pwn.college{YhXhFhobH0Uypk3ylmUhvm_XhFZ.QX3YTN0wyM1YDM1EzW}

### Challenge 5: Redirecting input

**Goal:**
Redirect output 'COLLEGE' into 'PWN' file and then redirect input 'COLLEGE' to '/challenge/run'

**Commands used:**
``` bash
1) echo COLLEGE > PWN
2) /challenge/run < PWN
```

**Flag:**
pwn.college{s7UPRkIZUKYUyCYe5X0j9rj8bdJ.QXwcTN0wyM1YDM1EzW}

### Challenge 6: Grepping stored results

**Goal:**
Redirect the output of '/challenge/run' to '/tmp/data.txt' and grep the flag.

**Commands used:**
``` bash
1) challenge/run > /tmp/data.txt
2) grep 'pwn.college' /tmp/data.txt
```

**Flag:**
pwn.college{EiAedgf1iXPfXPP_Kf9LrQpyfDH.QX4EDO0wyM1YDM1EzW}

### Challenge 7: Grepping live output

**Goal:**
Grepping using piping.

**Commands used:**
``` bash
1) /challenge/run | grep 'pwn.college'
```

**Flag:**
pwn.college{cpodpZCyvHm06nhpr9LAhqpiQ03.QX5EDO0wyM1YDM1EzW}

### Challenge 8: Grepping errors

**Goal:**
Grepping after redirecting standard error to standard output.

**Commands used:**
``` bash
1) /challenge/run 2>&1 | grep 'pwn.college'
```

**Flag:**
pwn.college{YstlAsB3XS3w6bxBMgErmNUCapH.QX1ATO0wyM1YDM1EzW}

### Challenge 9: Filtering with grep -v

**Goal:**
Filtering out decoys using grep to get the real flag.

**Commands used:**
``` bash
1) /challenge/run | grep -v DECOY
```

**Flag:**
pwn.college{UcBqd-8kzX3rZ7ODD1_yNnlYYZq.0FOxEzNxwyM1YDM1EzW}

### Challenge 10: Filtering with sed

**Goal:**
Filtering out decoys using grep to get the real flag.

**Commands used:**
``` bash
1) /challenge/run |sed "s/FAKEFLAG//g"
```

**Flag:**
pwn.college{YRXHQETvkSi9SJd2O62h3xXTzDY.01NxQTMywyM1YDM1EzW}

### Challenge 11: Duplicating piped data with tee

Filtering out decoys using grep to get the real flag.

**Commands used:**
``` bash
1) /challenge/pwn | tee pwn | /challenge/college
2) cat pwn
3) /challenge/pwn --secret UHeQpJ6c | /challenge/college
```

**Flag:**
pwn.college{UHeQpJ6c9zKlyme5pZtMuc1uKdo.QXxITO0wyM1YDM1EzW}
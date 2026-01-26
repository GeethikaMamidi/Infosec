# Linux Luminarium
## Module 7: Shell Variables
### Challenge 1: Printing variables

**Commands used:**
``` bash
1) echo $FLAG
```

**Flag:**
pwn.college{8skuEPyZ3wyGUQQCD1LqknyU-Zu.QX3UTN0wyM1YDM1EzW}


### Challenge 2: Setting variables

**Commands used:**
``` bash
1) PWN=COLLEGE
```

**Flag:**
pwn.college{c9xzzkyFjn67UPGGhnHvASAGOq3.QX5UTN0wyM1YDM1EzW}


### Challenge 3: Multi-word variables

**Commands used:**
``` bash
1) PWN="COLLEGE YEAH"
```

**Flag:**
pwn.college{cCIZW_uF58eT2LrZgqJVllk3BtC.QXwYTN0wyM1YDM1EzW}


### Challenge 4: Exporting variables

**Commands used:**
``` bash
1) export PWN=COLLEGE
2) COLLEGE=PWN
3) /challenge/run
```

**Flag:**
pwn.college{s9MV7KhAOom6tLEA_dFaQ7SmYvl.QXyYTN0wyM1YDM1EzW}


### Challenge 5: Printing exported variables

**Commands used:**
``` bash
1) env
```

**Flag:**
pwn.college{IWxQPaHm7lTi_HmxdHKHiF22QCC.QX4UTN0wyM1YDM1EzW}


### Challenge 6: Storing command output

**Commands used:**
``` bash
1) PWN=$(/challenge/run)
2) $PWN
```

**Flag:**
pwn.college{kCfZDYS0uKlknpLjaOkwQkixhXi.QX1cDN1wyM1YDM1EzW}


### Challenge 7: Reading input

**Commands used:**
``` bash
1) read -p "INPUT: " PWN
2) INPUT: COLLEGE
```

**Flag:**
pwn.college{MAlXi8_AHejaqYcS24a0m05oJeS.QX4cTN0wyM1YDM1EzW}


### Challenge 8: Reading files

**Commands used:**
``` bash
1) read PWN < /challenge/read_me
```

**Flag:**
pwn.college{8ZoJPcZiE0lG8EwyM20bOtoiZYZ.QXwIDO0wyM1YDM1EzW}
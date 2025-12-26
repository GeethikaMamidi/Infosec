# Linux Luminarium

## Module 4: Digesting Documentation

### Challenge 1: Learning from Documentation

**Commands Used:**

```bash
/challenge/challenge --giveflag
```

**Output:**

```bash
Correct argument! Here is your flag:
pwn.college{05OVpM90QCXUL2dz-oCLwf8CcCw.QX0ITO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{05OVpM90QCXUL2dz-oCLwf8CcCw.QX0ITO0wyM1YDM1EzW}

### Challenge 2: Learning complex usage

**Commands Used:**

```bash
/challenge/challenge --printfile /flag
```

**Output:**

```bash
Correct argument! Here is the /flag file:
pwn.college{QPOG4OAuyboOLfRsPfZ-s9qMlPi.QX1ITO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{QPOG4OAuyboOLfRsPfZ-s9qMlPi.QX1ITO0wyM1YDM1EzW}

### Challenge 3: Reading manuals

**Commands Used:**

```bash
man challenge
```

**Output:**

```bash
CHALLENGE(1)                                                  Challenge Commands                                                  CHALLENGE(1)

NAME
       /challenge/challenge - print the flag!

SYNOPSIS
       challenge OPTION

DESCRIPTION
       Output the flag when called with the right arguments.

       --fortune
              read a fortune

       --version
              output version information and exit

       --ozlswi NUM
              print the flag if NUM is 869

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The repository for this dojo: <https://github.com/pwncollege/linux-luminarium/>

SEE ALSO
       man(1) bash-builtins(7)

pwn.college                                                        May 2024                                                       CHALLENGE(1)
~
 Manual page challenge(1) line 1/31 (END) (press h for help or q to quit)
```

**Commands Used:**

```bash
/challenge/challenge --ozlswi 869
```

**Output:**

```bash
Correct usage! Your flag: pwn.college{o8GW6BYzSlswi90lTxhMYYM7X4p.QX0EDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{o8GW6BYzSlswi90lTxhMYYM7X4p.QX0EDO0wyM1YDM1EzW}

### Challenge 4: Searching Manuals

**Commands Used:**

```bash
man challenge
/challenge/challenge --yhf
```

**Output:**

```bash
Initializing...
Correct usage! Your flag: pwn.college{Irf2CeVjbFcF4Pg3wuTdtle90XZ.QX1EDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{Irf2CeVjbFcF4Pg3wuTdtle90XZ.QX1EDO0wyM1YDM1EzW}

### Challenge 5: Searching for Manuals

**Commands Used:**

```bash
man man
man -k challenge
```

**Output:**

```bash
ycigkqueuw (1)       - print the flag!
```

**Commands Used:**

```bash
man ycigkqueuw
/challenge/challenge --ycigkq 654
```

**Output:**

```bash
Correct usage! Your flag: pwn.college{AyT6DMcRiF-gA54AkXq0LuIKe4u.QX2EDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{AyT6DMcRiF-gA54AkXq0LuIKe4u.QX2EDO0wyM1YDM1EzW}

### Challenge 6: Helpful programs

**Commands Used:**

```bash
/challenge/challenge --help
```

**Output:**

```bash
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to give you the flag
```

**Commands Used:**

```bash
/challenge/challenge -p
```

**Output:**

```bash
The secret value is: 906
```

**Commands Used:**

```bash
/challenge/challenge -g 906
```

**Output:**

```bash
Correct usage!  Your flag: pwn.college{MdF9rhEM_wGo0KOSlnylWVBuk6O.QX3IDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{MdF9rhEM_wGo0KOSlnylWVBuk6O.QX3IDO0wyM1YDM1EzW}

### Challenge 7: Help for Builtins

**Commands Used:**

```bash
help challenge
```

**Output:**

```bash
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "YSs_I2bn".
```

**Commands Used:**

```bash
challenge --secret YSs_I2bn
```

**Output:**

```bash
Correct! Here is your flag!
pwn.college{YSs_I2bnf_AM1DMY0s4cvp4zWGq.QX0ETO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{YSs_I2bnf_AM1DMY0s4cvp4zWGq.QX0ETO0wyM1YDM1EzW}

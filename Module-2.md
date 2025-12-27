# Linux Luminarium

## Module 2: Pondering Paths

### Challenge 1: The Root

**Task:**

Invoke pwn program.

**Commands Used:**

```bash
/pwn
```

**Output:**

```bash
BOOM!!!
Here is your flag:
pwn.college{c4yJUKq5cjgo2wbIyfFz7GNWqUy.QX4cTO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{c4yJUKq5cjgo2wbIyfFz7GNWqUy.QX4cTO0wyM1YDM1EzW}

### Challenge 2: Program and absolute paths

**Task:**

Invoke a program using its absolute path.

**Commands Used:**

```bash
/challenge/run
```

**Output:**

```bash
BOOM!!!
Correct!!!
/challenge/run is an absolute path! Here is your flag:
pwn.college{wzao2CAiePp0g_hp0UdHUF_CuWw.QX1QTN0wyM1YDM1EzW}
```

**Flag:**
pwn.college{wzao2CAiePp0g_hp0UdHUF_CuWw.QX1QTN0wyM1YDM1EzW}

### Challenge 3: Position thy self

**Task:**

Use cd and run the program.

**Commands Used:**

```bash
cd /
/challenge/run
```

**Output:**

```bash
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{I3Yfyo-Gm6knfnv1RUz4xIaS27H.QX2QTN0wyM1YDM1EzW}
```

**Flag:**
pwn.college{I3Yfyo-Gm6knfnv1RUz4xIaS27H.QX2QTN0wyM1YDM1EzW}

### Challenge 4: Position elsewhere

**Task:**

Use cd and run the program 5 times

**Commands Used:**

```bash
cd /
/challenge/run
```

**Output:**

```bash
Starting level 1.
Incorrect...
You are not currently in the /usr/share/build-essential directory.
Please use the `cd` utility to change directory appropriately.
```

**Commands Used:**

```bash
cd /usr/share/build-essential
/challenge/run
```

**Output:**

```bash
Starting level 1.
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 2
Please use the `cd` utility to change directory to /sys/kernel
```

**Commands Used:**

```bash
cd /sys/kernel
/challenge/run
```

**Output:**

```bash
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 3
Please use the `cd` utility to change directory to /sys
```

**Commands Used:**

```bash
cd /sys
/challenge/run
```

**Output:**

```bash
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 4
Please use the `cd` utility to change directory to /usr/share/doc/fontconfig
```

**Commands Used:**

```bash
cd /usr/share/doc/fontconfig
/challenge/run
```

**Output:**

```bash
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 5
Please use the `cd` utility to change directory to /usr/aarch64-linux-gnu/include/gnu
```

**Commands Used:**

```bash
cd /usr/aarch64-linux-gnu/include/gnu
/challenge/run
```

**Output:**

```bash
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{o3lp0gNScf1QVEOKkqw56V_KYk4.QX3QTN0wyM1YDM1EzW}
```

**Flag:**
pwn.college{o3lp0gNScf1QVEOKkqw56V_KYk4.QX3QTN0wyM1YDM1EzW}

### Challenge 5: Implicit relative paths from /

**Task:**

Run /challenge/run using a relative path while having a current working directory of /.

**Commands Used:**

```bash
cd /
challenge/run
```

**Output:**

```bash
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{YqpRIUMrtK0XsDes6Zf1TZEpjxk.QX5QTN0wyM1YDM1EzW}
```

**Flag:**
pwn.college{YqpRIUMrtK0XsDes6Zf1TZEpjxk.QX5QTN0wyM1YDM1EzW}

### Challenge 6: Explicit relative paths from /

**Task:**

Using . in relative paths.

**Commands Used:**

```bash
cd /
./challenge/run
```

**Output:**

```bash
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{QuDWO4MqHMADCvaDUpQmZKxjQbS.QXwUTN0wyM1YDM1EzW}
```

**Flag:**
pwn.college{QuDWO4MqHMADCvaDUpQmZKxjQbS.QXwUTN0wyM1YDM1EzW}

### Challenge 7: Implicit relative path

**Task:**

Run it from the /challenge directory by using .

**Commands Used:**

```bash
cd /challenge
./run
```

**Output:**

```bash
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{wbMzF4M_6WgQq6lW2nTLWJIcUv6.QXxUTN0wyM1YDM1EzW}
```

**Flag:**
pwn.college{wbMzF4M_6WgQq6lW2nTLWJIcUv6.QXxUTN0wyM1YDM1EzW}

### Challenge 8: Home sweet home

**Commands Used:**

```bash
/challenge/run ~/f
```

**Output:**

```bash
Writing the file to /home/hacker/f!
... and reading it back to you:
pwn.college{Q9rpCdIehw1L428UJ8QW64MrFGF.QXzMDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{Q9rpCdIehw1L428UJ8QW64MrFGF.QXzMDO0wyM1YDM1EzW}

# Linux Luminarium

## Module 1: Comprehending Commands

### Challenge 1: cat: not the pet, but the command!

**Commands Used:**

```bash
cat flag
```

**Output:**

```bash
pwn.college{4QO9yLwCSlsdcoYshMV92VIohdf.QXxcTN0wyM1YDM1EzW}
```

**Flag:**
pwn.college{4QO9yLwCSlsdcoYshMV92VIohdf.QXxcTN0wyM1YDM1EzW}

### Challenge 2: catting absolute paths

**Commands Used:**

```bash
cat /flag
```

**Output:**

```bash
pwn.college{Qk9rtsDRx-y0Y9z5EKt3bEkoNG7.QX5ETO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{Qk9rtsDRx-y0Y9z5EKt3bEkoNG7.QX5ETO0wyM1YDM1EzW}

### Challenge 3: more catting practice

**Commands Used:**

```bash
cat /lib/i386-linux-gnu/flag
```

**Output:**

```bash
pwn.college{Mwrutwk_SUE2F0VFN6MXmxo2Lch.QXwITO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{Mwrutwk_SUE2F0VFN6MXmxo2Lch.QXwITO0wyM1YDM1EzW}

### Challenge 4: grepping for a needle in a haystack

**Commands Used:**

```bash
grep pwn.college /challenge/data.txt
```

**Output:**

```bash
pwn.college{oUG-H55VcWERQJNagJSPGV83iSx.QX3EDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{oUG-H55VcWERQJNagJSPGV83iSx.QX3EDO0wyM1YDM1EzW}

### Challenge 5: comparing files

**Commands Used:**

```bash
diff decoys_only.txt decoys_and_real.txt
```

**Output:**

```bash
32a33
> pwn.college{8uNSlJ0WGihoMFt3vRaZUDCtaEL.01MwMDOxwyM1YDM1EzW}
```

**Flag:**
pwn.college{8uNSlJ0WGihoMFt3vRaZUDCtaEL.01MwMDOxwyM1YDM1EzW}

### Challenge 6: listing files

**Commands Used:**

```bash
ls /challenge
```

**Output:**

```bash
770-renamed-run-8579  DESCRIPTION.md
```

**Commands Used:**

```bash
/challenge/770-renamed-run-8579
```

**Output:**

```bash
Yahaha,  you found me! Here is your flag:
pwn.college{UXu4LkdFFPdTG3vELLBYvyMrCUJ.QX4IDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{UXu4LkdFFPdTG3vELLBYvyMrCUJ.QX4IDO0wyM1YDM1EzW}

### Challenge 7: touching files

**Commands Used:**

```bash
cd /tmp
touch pwn college
ls
```

**Output:**

```bash
bin  college  hsperfdata_root  pwn  tmp.2dyEZcT2Od
```

**Commands Used:**

```bash
/challenge/run
```

**Output:**

```bash
Success! Here is your flag:
pwn.college{QIzNY0BkqCmYpWQKUrNrPVu2zIK.QXwMDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{QIzNY0BkqCmYpWQKUrNrPVu2zIK.QXwMDO0wyM1YDM1EzW}

### Challenge 8: removing files

**Commands Used:**

```bash
rm delete_me
/challenge/check
```

**Output:**

```bash
Excellent removal. Here is your reward:
pwn.college{EKakd28hfnP8ukQNCFJt5Bo58vy.QX2kDM1wyM1YDM1EzW}
```

**Flag:**
pwn.college{EKakd28hfnP8ukQNCFJt5Bo58vy.QX2kDM1wyM1YDM1EzW}

### Challenge 9: moving files

**Commands Used:**

```bash
mv /flag /tmp/hack-the-planet
```

**Output:**

```bash
Correct! Performing 'mv /flag /tmp/hack-the-planet'.
```

**Commands Used:**

```bash
/challenge/check
```

**Output:**

```bash
Congrats! You successfully moved the flag to /tmp/hack-the-planet! Here it is:
pwn.college{we1sRe-STWXlujQtFDgsQuNM-vh.0VOxEzNxwyM1YDM1EzW}
```

**Flag:**
pwn.college{we1sRe-STWXlujQtFDgsQuNM-vh.0VOxEzNxwyM1YDM1EzW}

### Challenge 10: copying files

**Commands Used:**

```bash
cp /flag /tmp/hack-the-planet
```

**Output:**

```bash
Correct! Performing 'cp /flag /tmp/hack-the-planet'.
```

**Commands Used:**

```bash
/challenge/check
```

**Output:**

```bash
Congrats! You successfully copied the flag to /tmp/hack-the-planet! Here it is:
pwn.college{o5-8elxuY4WLZC765zvZr1gWXwp.0lNxQTMywyM1YDM1EzW}
```

**Flag:**
pwn.college{o5-8elxuY4WLZC765zvZr1gWXwp.0lNxQTMywyM1YDM1EzW}

### Challenge 11: hidden files

**Commands Used:**

```bash
cd /
ls -a
```

**Output:**

```bash
.   .dockerenv            bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-26021211098873  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
```

**Commands Used:**

```bash
cat .flag-26021211098873
```

**Output:**

```bash
pwn.college{UDwER33_fdnrEfbNI0xENV2S4uR.QXwUDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{UDwER33_fdnrEfbNI0xENV2S4uR.QXwUDO0wyM1YDM1EzW}

### Challenge 12: An epic Filesystem Quest

**Commands Used:**

```bash
cd /
ls
```

**Output:**

```bash
MEMO  bin  boot  challenge  dev  etc  flag  home  lib  lib32  lib64  libx32  media  mnt  nix  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
```

**Commands Used:**

```bash
cat MEMO
```

**Output:**

```bash
Yahaha, you found me!
The next clue is in: /var/cache/man/ko

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
```

**Commands Used:**

```bash
cd /var/cache/man/ko
ls
```

**Output:**

```bash
CACHEDIR.TAG  TIP  cat1  cat5  cat8  index.db
```

**Commands Used:**

```bash
cat TIP
```

**Output:**

```bash
Congratulations, you found the clue!
The next clue is in: /usr/lib/python3/dist-packages/sphinx/websupport

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
```

**Commands Used:**

```bash
cd /usr/lib/python3/dist-packages/sphinx/websupport
ls -a
```

**Output:**

```bash
.  ..  .CUE  __init__.py  __pycache__  errors.py  search  storage
```

**Commands Used:**

```bash
cat .CUE
```

**Output:**

```bash
Great sleuthing!
The next clue is in: /usr/local/share/jupyter/labextensions/@jupyter-notebook/lab-extension/schemas/@jupyter-notebook/lab-extension

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
```

**Commands Used:**

```bash
cd /usr/local/share/jupyter/labextensions/@jupyter-notebook/lab-extension/schemas/@jupyter-notebook/lab-extension
ls
```

**Output:**

```bash
BLUEPRINT  interface-switcher.json  launch-tree.json  package.json.orig
```

**Commands Used:**

```bash
cat BLUEPRINT
```

**Output:**

```bash
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/include/config/iommu

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
```

**Commands Used:**

```bash
ls -a /opt/linux/linux-5.4/include/config/iommu
```

**Output:**

```bash
.  ..  REVELATION-TRAPPED  api.h  helper.h  iova.h  support.h
```

**Commands Used:**

```bash
cat /opt/linux/linux-5.4/include/config/iommu/REVELATION-TRAPPED
```

**Output:**

```bash
Yahaha, you found me!
The next clue is in: /opt/linux/linux-5.4/include/config/interval

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
```

**Commands Used:**

```bash
ls -a /opt/linux/linux-5.4/include/config/interval
.  ..  .POINTER  tree.h
```

**Output:**

```bash
.  ..  .POINTER  tree.h
```

**Commands Used:**

```bash
cat /opt/linux/linux-5.4/include/config/interval/.POINTER
```

**Output:**

```bash
Tubular find!
The next clue is in: /usr/share/racket/pkgs/r5rs-doc/r5rs/scribblings/r5rs-std

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
```

**Commands Used:**

```bash
ls -a /usr/share/racket/pkgs/r5rs-doc/r5rs/scribblings/r5rs-std
```

**Output:**

```bash
.                r5rs-Z-G-16.gif  r5rs-Z-G-27.gif  r5rs-Z-G-38.gif  r5rs-Z-G-49.gif  r5rs-Z-G-6.gif    r5rs-Z-G-D-3.gif  r5rs-Z-H-15.html
..               r5rs-Z-G-17.gif  r5rs-Z-G-28.gif  r5rs-Z-G-39.gif  r5rs-Z-G-5.gif   r5rs-Z-G-60.gif   r5rs-Z-G-D-4.gif  r5rs-Z-H-2.html
NOTE-TRAPPED     r5rs-Z-G-18.gif  r5rs-Z-G-29.gif  r5rs-Z-G-4.gif   r5rs-Z-G-50.gif  r5rs-Z-G-61.gif   r5rs-Z-G-D-5.gif  r5rs-Z-H-3.html
index.html       r5rs-Z-G-19.gif  r5rs-Z-G-3.gif   r5rs-Z-G-40.gif  r5rs-Z-G-51.gif  r5rs-Z-G-62.gif   r5rs-Z-G-D-6.gif  r5rs-Z-H-4.html
r5rs-Z-C.css     r5rs-Z-G-2.gif   r5rs-Z-G-30.gif  r5rs-Z-G-41.gif  r5rs-Z-G-52.gif  r5rs-Z-G-63.gif   r5rs-Z-G-D-7.gif  r5rs-Z-H-5.html
r5rs-Z-G-1.gif   r5rs-Z-G-20.gif  r5rs-Z-G-31.gif  r5rs-Z-G-42.gif  r5rs-Z-G-53.gif  r5rs-Z-G-64.gif   r5rs-Z-G-D-8.gif  r5rs-Z-H-6.html
r5rs-Z-G-10.gif  r5rs-Z-G-21.gif  r5rs-Z-G-32.gif  r5rs-Z-G-43.gif  r5rs-Z-G-54.gif  r5rs-Z-G-65.gif   r5rs-Z-H-1.html   r5rs-Z-H-7.html
r5rs-Z-G-11.gif  r5rs-Z-G-22.gif  r5rs-Z-G-33.gif  r5rs-Z-G-44.gif  r5rs-Z-G-55.gif  r5rs-Z-G-7.gif    r5rs-Z-H-10.html  r5rs-Z-H-8.html
r5rs-Z-G-12.gif  r5rs-Z-G-23.gif  r5rs-Z-G-34.gif  r5rs-Z-G-45.gif  r5rs-Z-G-56.gif  r5rs-Z-G-8.gif    r5rs-Z-H-11.html  r5rs-Z-H-9.html
r5rs-Z-G-13.gif  r5rs-Z-G-24.gif  r5rs-Z-G-35.gif  r5rs-Z-G-46.gif  r5rs-Z-G-57.gif  r5rs-Z-G-9.gif    r5rs-Z-H-12.html  r5rs.html
r5rs-Z-G-14.gif  r5rs-Z-G-25.gif  r5rs-Z-G-36.gif  r5rs-Z-G-47.gif  r5rs-Z-G-58.gif  r5rs-Z-G-D-1.gif  r5rs-Z-H-13.html
r5rs-Z-G-15.gif  r5rs-Z-G-26.gif  r5rs-Z-G-37.gif  r5rs-Z-G-48.gif  r5rs-Z-G-59.gif  r5rs-Z-G-D-2.gif  r5rs-Z-H-14.html
```

**Commands Used:**

```bash
cat /usr/share/racket/pkgs/r5rs-doc/r5rs/scribblings/r5rs-std/NOTE-TRAPPED
```

**Output:**

```bash
Yahaha, you found me!
The next clue is in: /opt/linux/linux-5.4/tools/testing/selftests/bpf/gnu

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
```

**Commands Used:**

```bash
ls -a /opt/linux/linux-5.4/tools/testing/selftests/bpf/gnu
```

**Output:**

```bash
.  ..  .LEAD  stubs.h
```

**Commands Used:**

```bash
cat /opt/linux/linux-5.4/tools/testing/selftests/bpf/gnu/.LEAD
```

**Output:**

```bash
Great sleuthing!
The next clue is in: /usr/share/maxima-sage/5.42.2/share
```

**Commands Used:**

```bash
ls -a /usr/share/maxima-sage/5.42.2/share
```

**Output:**

```bash
.                   builtins-list.txt  draw              integration       minpack        readme-share.txt      stringproc
..                  calculus           dynamics          lapack            misc           share.usg             sym
MYTOPIC-index.lisp  cobyla             ezunits           lbfgs             mnewton        share_testsuite.lisp  template-standalone.texi
MYTOPIC.info        colnew             finance           linearalgebra     multiadditive  simplex               template.texi
README              combinatorics      fourier_elim      lisp-utils        numeric        simplification        tensor
TRACE               contrib            fractals          logic             numericalio    solve_rat_ineq        to_poly_solve
affine              descriptive        graphs            lsquares          odepack        solve_rec             trigonometry
algebra             diff_form          hypergeometric    macro             orthopoly      sound                 utils
amatrix             diffequations      integequations    matrix            pdiff          specfun.lisp          vector
bernstein           distrib            integer_sequence  maxima-init.lisp  physics        stats                 z_transform
```

**Commands Used:**

```bash
cat /usr/share/maxima-sage/5.42.2/share/TRACE
```

**Output:**

```bash
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{cCwjup-C7wp7zhRBxJkZ7lPYBEs.QX5IDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{cCwjup-C7wp7zhRBxJkZ7lPYBEs.QX5IDO0wyM1YDM1EzW}

### Challenge 13: making directories

**Commands Used:**

```bash
cd /tmp
mkdir pwn
cd pwn
touch college
ls
```

**Output:**

```bash
college
```

**Commands Used:**

```bash
/challenge/run
```

**Output:**

```bash
Success! Here is your flag:
pwn.college{0yk_-2KOSgZzvvYFTp5etPdkH-J.QXxMDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{0yk\_-2KOSgZzvvYFTp5etPdkH-J.QXxMDO0wyM1YDM1EzW}

### Challenge 14: finding files

**Commands Used:**

```bash
find / -name flag
```

**Output:**

```bash
find: ‘/root’: Permission denied
find: ‘/proc/1/task/1/fd’: Permission denied
find: ‘/proc/1/task/1/fdinfo’: Permission denied
find: ‘/proc/1/task/1/ns’: Permission denied
find: ‘/proc/1/fd’: Permission denied
find: ‘/proc/1/map_files’: Permission denied
find: ‘/proc/1/fdinfo’: Permission denied
find: ‘/proc/1/ns’: Permission denied
find: ‘/proc/7/task/7/fd’: Permission denied
find: ‘/proc/7/task/7/fdinfo’: Permission denied
find: ‘/proc/7/task/7/ns’: Permission denied
find: ‘/proc/7/fd’: Permission denied
find: ‘/proc/7/map_files’: Permission denied
find: ‘/proc/7/fdinfo’: Permission denied
find: ‘/proc/7/ns’: Permission denied
find: ‘/var/log/private’: Permission denied
find: ‘/var/log/apache2’: Permission denied
find: ‘/var/log/mysql’: Permission denied
find: ‘/var/cache/ldconfig’: Permission denied
find: ‘/var/cache/apt/archives/partial’: Permission denied
find: ‘/var/cache/private’: Permission denied
find: ‘/var/lib/apt/lists/partial’: Permission denied
find: ‘/var/lib/php/sessions’: Permission denied
find: ‘/var/lib/mysql-files’: Permission denied
find: ‘/var/lib/private’: Permission denied
find: ‘/var/lib/mysql-keyring’: Permission denied
find: ‘/var/lib/mysql’: Permission denied
find: ‘/tmp/tmp.2dyEZcT2Od’: Permission denied
find: ‘/run/mysqld’: Permission denied
find: ‘/run/sudo’: Permission denied
find: ‘/etc/ssl/private’: Permission denied
/usr/local/lib/python3.8/dist-packages/setuptools/_vendor/importlib_resources/tests/data02/flag
/usr/local/lib/python3.8/dist-packages/pwnlib/flag
/opt/pwndbg/.venv/lib/python3.8/site-packages/pwnlib/flag
/nix/store/7ns27apnvn4qj4q5c82x0z1lzixrz47p-radare2-5.9.8/share/radare2/5.9.8/flag
/nix/store/5z3sjp9r463i3siif58hq5wj5jmy5m98-python3.12-pwntools-4.13.1/lib/python3.12/site-packages/pwnlib/flag
/nix/store/5n5lp1m8gilgrsriv1f2z0jdjk50ypcn-rizin-0.7.3/share/rizin/flag
/nix/store/bnlabj2vsbljhp597ir29l51nrqhm89w-rizin-0.7.4/share/rizin/flag
/nix/store/s8b49lb0pqwvw0c6kgjbxdwxcv2bp0x4-radare2-5.9.8/share/radare2/5.9.8/flag
/nix/store/1hyxipvwpdpcxw90l5pq1nvd6s6jdi5m-python3.12-pwntools-4.14.1/lib/python3.12/site-packages/pwnlib/flag
/nix/store/h88mxp2mbgyj06vypwmqpy05idhwimnp-python3.13-pwntools-4.14.1/lib/python3.13/site-packages/pwnlib/flag
/nix/store/5qz6hgb1qzpvjrsw20wyiylx5zw8b9bk-pwntools-4.14.0/lib/python3.13/site-packages/pwnlib/flag
```

**Commands Used:**

```bash
cat /usr/local/lib/python3.8/dist-packages/setuptools/_vendor/importlib_resources/tests/data02/flag
```

**Output:**

```bash
pwn.college{UQfnV4qGbkhLOf1FGQnjNsKxiAI.QXyMDO0wyM1YDM1EzW}
```

**Flag:**
pwn.college{UQfnV4qGbkhLOf1FGQnjNsKxiAI.QXyMDO0wyM1YDM1EzW}

### Challenge 15: linking files

**Commands Used:**

```bash
ls
```

**Output:**

```bash
f  not-the-flag
```

**Commands Used:**

```bash
rm not-the-flag
ln -s /flag not-the-flag
ls -l not-the-flag
```

**Output:**

```bash
lrwxrwxrwx 1 hacker hacker 5 Dec 24 09:23 not-the-flag -> /flag
```

**Commands Used:**

```bash
/challenge/catflag
```

**Output:**

```bash
About to read out the /home/hacker/not-the-flag file!
pwn.college{kIZNdfcPlUsgorZ82ajxfkPMaor.QX5ETN1wyM1YDM1EzW}
```

**Flag:**
pwn.college{kIZNdfcPlUsgorZ82ajxfkPMaor.QX5ETN1wyM1YDM1EzW}

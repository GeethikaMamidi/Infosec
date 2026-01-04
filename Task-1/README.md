# Infosec

Bandit levels 0-5
<br>
<br>
Level 0
<br>
Username: bandit0
<br>
Password: bandit0
<br>
command: ssh bandit0@bandit.labs.overthewire.org -p 2220
<br>
Result: Password in terminal.
<br>
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
<br>
<br>
Level 1
<br>
Password: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
<br>
command: ssh bandit1@bandit.labs.overthewire.org -p 2220
<br>
steps: ls,cat
<br>
Result: Password in readme file.
<br>
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
<br>
<br>
Level 2
<br>
Password: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
<br>
command: ssh bandit2@bandit.labs.overthewire.org -p 2220
<br>
steps: ls,cat ./-
<br>
Result: Password in - located in the home directory.
<br>
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
<br>
<br>
Level 3
<br>
Password: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
<br>
command: ssh bandit3@bandit.labs.overthewire.org -p 2220
<br>
steps: ls,cat ./--spaces\ in\ this\ filename--
<br>
Result: Password in a file with spaces in its name.
<br>
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
<br>
<br>
Level 4
<br>
Password: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
<br>
command: ssh bandit4@bandit.labs.overthewire.org -p 2220
<br>
steps: cd inhere,ls,file ./\*
<br>
Result: Password in only human-readable file inside the inhere directory.
<br>
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
<br>
<br>
Level 5
<br>
Password: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
<br>
<br>

<p>
CIA is the abbreviation for Confidentiality, Integrity and Availability; three pillars of effective IT security system which helps in protecting data and securing information in organisations.
<br>
<br>
1)	Confidentiality:
It ensures that data is private and is accessible to authorised personnel only.
•	Sensitive info(passwords, personal data) is kept secret.
<br>
•	Encryption, authentication, VPNs can be used to enhance confidentiality.
<br>
2)	Integrity:
<br>
It ensures that data is authentic, accurate and unaltered.
<br>
•	Prevents unauthorised modifications and builds trust.
<br>
•	Methods like hashing, digital signatures and version controls.
<br>
3)	Availability:
<br>
Availability ensures that systems, networks, and data are accessible to authorized users whenever needed.
<br>
•	Business continuity.
<br>
•	Regular maintenance, updates and backups.
<br>
<br>
Relationship between CIA components:-
<br>
All the components are important, improving one affects the other. So, one must make sure that all the three are balanced properly.

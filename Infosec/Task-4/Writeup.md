# Security concepts

## Passwords vs SSH keys

### Passwords

1) Username and password credentials are transmitted to server for authentication. This makes your account vulnerable to unauthorised access.
2) Your 8 short and predictable password is easy to guess and is prone to hacking.
3) Many users reuse the same password for multiple websites and apps, increasing their potential for breaching.

### SSH keys

1) SSH private keys are not sent to servers which makes your account safe even if there is a malicious attack to the server.
2) They can be upto 4096 bits of length, making it computationally infeasible to brute-force.
3) Security can further be increased by adding a passphrase to your SSH key authentication.

## Data Transformation vs Data Protection

### Data Transformation

1) It is the process of converting raw data into a clean and ready-to-use format for analysis or storage.
2) It is also known as ELT:
  <br>
  • Extract - Collection of raw data.
  <br>
  • Load - Storing data into a system or repository.
  <br>
  • Transform - Changing the data into required format for usage.
3) Data professional can opt ETL for:
<br>
  • Encryption of sensitive data before storage.
  <br>
  • Accommodating larger files into a repository of limited space.
4) Different tecniques of tranformation include Integration, Normalisation, Deduplication, Aggregation, Discretization and Feature engineering.

### Data Protection

1) It refers to the techniques to safeguard data and restore important information.
2) Data protection strategies involve:
<br>
  • Data inventory - Determines types and amount of data.
  <br>
  • Backup and recovery - Protects data from hardware failures.
  <br>
  • Data lifecycle management - Deals with data storage and classification.
3) It prevents unauthorized access, data breaches and accidental loss.
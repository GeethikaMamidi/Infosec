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
### Secure Copy file to remote server

Example of a scp command to copy a file from a windows PC to a remote server (which can be windows or linux as long as the OpenSSH server has been installed on the target system:

```
scp hello.txt user@10.10.0.1:/share
```

Copy file from remote server to local windows PC. The file will be put in the directory from where the command is executed.

```
scp user@10.0.0.1:/share/hello.txt .
```

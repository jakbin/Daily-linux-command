1. Read by owner only
```bash
chmod 400 sample.txt 
```
2. Read by group only
```bash
chmod 040 sample.txt 
```
3. Read by anyone
```bash
chmod 004 sample.txt 
```
4. Write by owner only
```bash
chmod 200 sample.txt 
```
5. Write by group only
```bash
chmod 020 sample.txt 
```
6. Write by anyone
```bash
chmod 002 sample.txt 
```
7. Execute by owner only
```bash
chmod 100 sample.txt 
```
8. Execute by group only
```bash
chmod 010 sample.txt 
```
9. Execute by anyone
```bash
chmod 001 sample.txt 
```
10. Allow read permission to owner and group and anyone.
```bash
chmod 444 sample.txt
```
11. Allow everyone to read, write, and execute file.
```bash
chmod 777 sample.txt
```
12. Deny execute permission to everyone.
```bash
chmod a-x sample.txt 
```
13. Allow read permission to everyone.
```bash
chmod a+r sample.txt 
```
14. Make a file readable and writable by the group and others.
```bash
chmod go+rw sample.txt 
```
15. Make a shell script executable by the user/owner.
```bash
chmod u+x samplescript.sh
```
16. Allow everyone to read, write, and execute the file and turn on the set group-ID.
```bash
chmod =rwx,g+s samplescript.sh
```
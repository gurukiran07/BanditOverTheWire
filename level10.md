### Level 10

```sh
urukiran@ch3ster:~$ ssh bandit10@bandit.labs.overthewire.org -p 2220
This is a OverTheWire game server. More information on http://www.overthewire.org/wargames

bandit10@bandit.labs.overthewire.org's password: 
Linux bandit.otw.local 5.4.8 x86_64 GNU/Linux

bandit10@bandit:~$ ls
data.txt
bandit10@bandit:~$ cat data.txt  | base64 --decode
The password is IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
bandit10@bandit:~$ base64 -d <data.txt
The password is IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
```

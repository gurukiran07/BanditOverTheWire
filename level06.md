### Level 6

```sh
gurukiran@ch3ster:~$ ssh bandit6@bandit.labs.overthewire.org -p 2220
This is a OverTheWire game server. More information on http://www.overthewire.org/wargames

bandit6@bandit.labs.overthewire.org's password: 
Linux bandit.otw.local 5.4.8 x86_64 GNU/Linux

bandit6@bandit:~$ ls -a
.  ..  .bash_logout  .bashrc  .profile
bandit6@bandit:~$ find / -user bandit7 -group bandit6 -size 33c 2> /dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@bandit:~$ find / -user bandit7 -group bandit6 -size 33c 2> /dev/null | xargs cat
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
```

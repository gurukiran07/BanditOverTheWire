### Level 5

```sh
bandit5@bandit:~$ ls
inhere
bandit5@bandit:~$ cd inhere/
bandit5@bandit:~/inhere$ ls
maybehere00  maybehere04  maybehere08  maybehere12  maybehere16
maybehere01  maybehere05  maybehere09  maybehere13  maybehere17
maybehere02  maybehere06  maybehere10  maybehere14  maybehere18
maybehere03  maybehere07  maybehere11  maybehere15  maybehere19
bandit5@bandit:~/inhere$ find -size 1033c ! -executable
./maybehere07/.file2
bandit5@bandit:~/inhere$ find -size 1033c ! -executable | xargs cat
DXjZPULLxYr17uwoI01bNLQbtFemEgo7
```

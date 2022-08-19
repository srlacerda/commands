# linux-commands
some linux commands

## commands
commands


1 - discover your user (who am i)
```
whoami
```

1 - (p)rint (w)orking (d)irectory
```
pwd
```

2 - show directorys
```
ls
```

3 - show directorys and some information
```
ls -l
```

4 - show directorys, hidden directorys and some information
```
ls -la
```


5 - (C)hange (D)irectory - Go to the directory
```
cd /users/diego.lacerda/repo
```

6 - cd .. -> previous directory
```
cd ..
```

6 - cd $HOME
```
cd $HOME
```

6 - cd ~ (same thing that cd $HOME)
```
cd ~
```

6 - cd / - Go to root folder
```
cd /
```

7 - show a manual of the command
```
man ls
```

8 - create a file, if the file exists then update data last modification
```
touch file.txt
```

9 - (m)a(k)e (dir)ectory
```
mkdir directory-name
```

10 - (r)e(m)ove 
```
rm -r directory-name
```

9 - (ch)ange (own)er
```
chown 
```

9 - ECHO - Show the value of the variable
```
echo $HOME
```
```
echo ~
```


9 - (M)a(k)e (dir)ectory
```
mkdir directory-name
```

9 - (M)a(k)e (dir)ectory
```
mkdir directory-name
```


## Directorys
Directorys

9 - Binaries of the System Operation (program "shutdown" is there)
```
cd /sbin
```

9 - Other programs of the system (bash, zsh, ls and others)
```
cd /bin
```

9 - (U)nix (S)ystem (R)esources, but you can consider like "USER", the biggest directory 
```
cd /usr
```

9 - Softwares that you install 
```
cd /usr/bin
```


## Others
others

9 - Process status
```
ps
```

9 - Process status of all proces running (inclusive wich you dont start)
```
ps aux
```

9 - writing in a file (overrwrite if there is something in the file)
```
touch a.txt
echo "hellow world" > a.txt
```

9 - writing in a file (appending if there is something)
```
echo "hellow world" >> a.txt
```

9 - show file (don't use with big files, because the "cat" send everything to the memory)
```
cat a.txt
```

9 - allow navigate between big files
```
ps aux | more
```

9 - allow navigate between big files (allow use VIM commands) - better
```
ps aux | less
```




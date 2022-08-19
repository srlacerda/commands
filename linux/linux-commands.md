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

9 - move
```
mv file.txt directory-name
```


10 - (r)e(m)ove 
```
rm -r directory-name
```
```
rm -Rf directory-name
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

9 - allow navigate between big files (not efficient, like the command above)
```
ps aux | more
```

9 - allow navigate between big files (allow use VIM commands) - better
```
ps aux | less
```

VIM commands
- j - up
- k - down
- gg - page up
- G - page down
- 10 e j - 10 lines down
- 5 e k - 5 lines up
- /word - find word -> downing word using key "n"
- q - quit/exit

9 - create a link from a file (a.txt) to link b.txt
```
ln -s a.txt b.txt
```


9 - watch the 
- 10 -> last 10 lines of the file
- -f -> the end of the file <br/>
Commonly used to monitor if the file is being changed
```
tail -10 b.txt
```
```
tail -f b.txt
```

9 - grep - (g)lobally search a (r)egular (e)xpression and (p)rint. <br/>
we use the **stdout** from "ps aux" to **stdin** to "grep bash"
```
ps aux | grep bash
```

9 - awk - allow filter a collum from stdout <br/>
- *$1* -> collum 1
- *$1* -> collum 2
- *$3* -> collum 3
```
ps aux | grep bash | awk '{print $2}'
```

9 - find commands that you already used <br/>
**ctrl + r** <br/>
text a part of the command and presse **"ctrl + r"** to navigate between the result


9 - show all ambient variables
```
set | less
```


9 - chmod <br/>
I HAVE TO LEARN!

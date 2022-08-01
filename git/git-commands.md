# git-commands
some git commands

## git squash

1 - Git pull
```
git pull
```

2 - Git rebase, HEAD~(number of commits that you want to squash)
```
git rebase -i HEAD~3
```

3 - "pick" or p on the commit that you want to stay

4 - "squash" or s on the commit that you want to remove

5 - To save press the key "ESC" and then the command ":wq" to confirm your changes and exit the interactive mode

6 - Check the logs
```
git log
```
or

```
git log --oneline
```
Pess the key "ESC" and then the command ":wq" to exit

7 - Git push force
```
git push origin main –-force
```

## git rebase
Rebase from develop to main

1 - Git checkout
```
git checkout main
```

2 - Git pull
```
git pull
```

3 - Git checkout
```
git checkout develop
```

4 - Git rebase
```
git rebase main
```

5 - Git push
```
git push origin develop -f
```

# git-commands
some git commands

## create a new repository on the command line
```
echo "# datomic-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/your-account/you-repository.git
git push -u origin main
```

## push an existing repository from the command line
```
git remote add origin https://github.com/your-account/your-repository.git
git branch -M main
git push -u origin main
```

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

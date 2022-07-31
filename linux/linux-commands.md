# aws-commands
commands

## publish lambda
aws-commands

1 - Install Amazon.Lambda.Tools
```
dotnet tool install -g Amazon.Lambda.Tools
```

2 - Publsh
```
dotnet lambda package -c relase -o Poc.Lambda.Zip -- framework netcoreapp3.1
```



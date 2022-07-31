# aws-commands
some aws commands

## publish lambda
aws-commands

1 - Install Amazon.Lambda.Tools
```
dotnet tool install -g Amazon.Lambda.Tools
```

2 - Publish
```
dotnet lambda package -c relase -o Poc.Lambda.Zip -- framework netcoreapp3.1
```



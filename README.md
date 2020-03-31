# UwebServerCert
LetsEncrypt bot to automatically create an LetsEncrypt certificate for UwebServer

## Packaging
```
dotnet pack -c Release
```

## Installation
```
sudo dotnet tool install UwebServerCert --global
```

## Executing the tool for the first time

Copy ```cert.json``` to current directory

```
sudo ~/.dotnet/tools/uwebcert -create -prod
``` 

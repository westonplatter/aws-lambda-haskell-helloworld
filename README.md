# mypackage

## development

## testing

## deployment

Pre Deploy setup:
- setup your default AWS profile with a valid AWS acccount
- provide 6GB of RAM to your local docker runtime

```sh
sls deoloy
```
Note: the first compilation + deploy will take a LONG time.


To test the function,
```sh
sls invoke -f mypackage-func
```


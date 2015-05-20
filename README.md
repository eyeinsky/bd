# bd

`bd` is a bash dependency loader. It's used as

```
bd $script
```

Prior to running the scipt itself it will source
patterns listed in both `${script}.bd`, `~/.bd`.

You can get some info out of the process by doing

```
DBG=1 bd $script
```

or 
   
```
DBG_FILE=log bd $script
```   

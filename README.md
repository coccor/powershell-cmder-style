# powershell-cmder-style
Make PowerShell look like cmder

Install Scoop:

``` 
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```

If  you get an error when tunning that command, make sure that you have PowerShell enabled for your user account by running:
```
set-executionpolicy remotesigned -s cu
```

Install concfg and use the molokai.json color theme:
```
scoop install concfg
concfg import path\to\molokai
```

Install pshazz and use the cmder.json preset:
```
scoop install pshazz
```
Copy cmder.json in your ```~/pshazz``` directory and run:
```
pshazz use cmder
```

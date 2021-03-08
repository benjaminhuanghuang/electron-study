


Electron has 2 processes:
- render: web UI
- main:  main.js  




## debug render
View -> Toggle Developer Tools



## debug main

- Debug in chrome 

start in debug mode
``` 
  electorn --inspect=6969 .
```

```
  chrome://inspect
```

- Debug in vscode
add .vscode/launch.json
```
  "runtimeExecutable": "{workspaceRoot}/node_modeules/.bin/electron"
  
```
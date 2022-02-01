## Angular resolve

- Install nodeJS
```
npm install -g npm
node -v
npm -v
```

- Unrestrict PowerShell, execute:
```
Get-ExecutionPolicy -list
Set-ExecutionPolicy Remotesigned
N
Set-ExecutionPolicy RemoteSigned -Force
Get-ExecutionPolicy
```

- Change version Angular
```
npm uninstall -g @angular/cli
```

- New project
```
npm install -g @angular/cli
ng new Project
```

- Execute project inside file
```
ng serve
```

- Any problem with the version
```
ng update --all

```

- Solution versions
```
npm install --save-dev @angular/cli@latest
npm install -g npm@"13.2"

```

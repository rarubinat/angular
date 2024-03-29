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
or
```
npm install -g @angular/cli --migrate-only --from=16.13.2

```
- Execute API REST
```
npm install
nest start --watch
```

- Git deploy pages github
```
git init
git remote add origin "url"
ng add angular-cli-ghpages
ng deploy --base-href=http://rarubinat.github.io/name-project/
````

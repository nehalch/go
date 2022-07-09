# My Go lang study notes


## Starting

### Seting up ENV
``` bash
mkdir $HOME/go
echo "export GOPATH="$HOME"/go" >> $HOME/.bashrc
```
### Creating project
``` bash
go mod init example/hello
vim hello.go
...
go run .
go build .
```

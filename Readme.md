```
wget https://golang.org/dl/go1.22.1.linux-amd64.tar.gz
```

```
tar -xvf go1.22.1.linux-amd64.tar.gz
```

```
sudo mv go /usr/local
```

```
nano ~/.profile
```

```
export GOPATH=$HOME/go
export PATH=$PATH:/usr/local/go/bin:$GOPATH/bin
```

```
source ~/.profile
```

```
go version
```

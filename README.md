use vps for better experience

use this command if u don't have go on your machine.if u already installed go, just paste ur private key to .env file then run code

```shell
wget https://go.dev/dl/go1.21.4.linux-amd64.tar.gz -O go.tar.gz
```

```shell
sudo tar -xzvf go.tar.gz -C /usr/local
```

```shell
echo export PATH=$HOME/go/bin:/usr/local/go/bin:$PATH >> ~/.profile
```

```shell
source ~/.profile
```

clone repo
```shell
git clonehttps://github.com/StephanieAgatha/sonic-sol.git
```

```shell
cd sonic-sol
```

paste private key in .env file
```shell
nano .env
```

```go
go run main.go
```


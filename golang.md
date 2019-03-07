env GOOS=linux GOARCH=amd64 go build main.go

Golang Install

brew update
brew install go / brew install golang


go version
go env
 

Bee go

Vim . /Users/arthaandriyanto/.bash_profile

export GOPATH=$HOME/go
  
export GOROOT=/usr/local/go

export GOBIN=$GOPATH/bin

export M2_HOME=/usr/local/apache-maven-3.5.4

export PATH=$PATH:$M2_HOME/bin:$GOPATH:$GOBIN

ulimit -n 4096

apply  . /Users/arthaandriyanto/.bash_profile
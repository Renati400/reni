# reni
cat &lt;&lt;EOF >> ~/.profile export GOROOT=/usr/local/go export GOPATH=$HOME/go export GO111MODULE=on export PATH=$PATH:/usr/local/go/bin:$HOME/go/bin EOF source ~/.profile go version rm -rf go1.19.4.linux-amd64.tar.gz

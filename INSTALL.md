#### Go on Root
```
sudo bash
```

#### Install go
```
wget https://golang.org/dl/go1.16.4.linux-amd64.tar.gz
tar -xvf go1.16.4.linux-amd64.tar.gz
mv go /usr/local/
export GOROOT=/usr/local/go/
export PATH=/usr/local/bin:$GOROOT/bin:$PATH
```

#### Install mig-parted
```
git clone http://github.com/NVIDIA/mig-parted
cd mig-parted/
go build ./cmd/nvidia-mig-parted
mv nvidia-mig-parted /usr/local/bin/
```

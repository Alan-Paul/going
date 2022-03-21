#环境搭建
版本：go1.17.2
步骤：
```
1、官网https://go.dev/dl/ 下载对应版本的包
2、解压至 /usr/local/go
3、环境变量：export PATH=$PATH:/usr/local/go/bin  
修改go env，
go env -w GO111MODULE="on"
go env -w GOPROXY="https://goproxy.cn,https://mirrors.tencent.com/go,https://mirrors.aliyun.com/goproxy,direct"
go env -w GOPATH="/home/ubuntu/go"
go env -w GOROOT="/usr/local/go"
执行 go env 输出如下
GO111MODULE="on"
GOARCH="amd64"
GOBIN="/home/ubuntu/gobin"
GOCACHE="/home/ubuntu/.cache/go-build"
GOENV="/home/ubuntu/.config/go/env"
GOEXE=""
GOEXPERIMENT=""
GOFLAGS=""
GOHOSTARCH="amd64"
GOHOSTOS="linux"
GOINSECURE=""
GOMODCACHE="/home/ubuntu/go/pkg/mod"
GONOPROXY=""
GONOSUMDB=""
GOOS="linux"
GOPATH="/home/ubuntu/go"
GOPRIVATE=""
GOPROXY="https://goproxy.cn,https://mirrors.tencent.com/go,https://mirrors.aliyun.com/goproxy,direct"
GOROOT="/usr/local/go"
GOSUMDB="sum.golang.org"
GOTMPDIR=""
GOTOOLDIR="/usr/local/go/pkg/tool/linux_amd64"
GOVCS=""
GOVERSION="go1.17.2"
GCCGO="gccgo"
AR="ar"
CC="gcc"
CXX="g++"
CGO_ENABLED="1"
GOMOD="/home/ubuntu/code/go_test/gin_test/go.mod"
CGO_CFLAGS="-g -O2"
CGO_CPPFLAGS=""
CGO_CXXFLAGS="-g -O2"
CGO_FFLAGS="-g -O2"
CGO_LDFLAGS="-g -O2"
PKG_CONFIG="pkg-config"
GOGCCFLAGS="-fPIC -m64 -pthread -fmessage-length=0 -fdebug-prefix-map=/tmp/go-build2386416741=/tmp/go-build -gno-record-gcc-switches"
```

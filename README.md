# ginblog
这是一个博客网站实现了，增删改查，登录session

# 源码阅读从router.go 开始

# 编译
在GoLand中
```bash
$env:GOOS = "linux"
$env:GOARCH = "amd64"
go build -o bjz .
```

# 部署
把static,view目录 拷贝到服务器
```bash
chmod +x bjz
./demo
```

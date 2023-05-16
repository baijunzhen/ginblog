# ginblog
这是一个博客网站实现了，增删改查，登录session

# 源码阅读从router.go 开始

```html
源码阅读从router.go 开始
来源：https://www.bilibili.com/video/BV1vB4y1n7km
项目地址：https://github.com/szkjtv/ginblog
项目简单的配置介绍：http://ecs.wwfeng3045.top:30056/deltel/112   （这个直接复制到浏览器打开）
```

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

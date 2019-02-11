```
语言特点：
  1. 静态类型、编译型语言
  2. 脚本化的语法，支持多种编程范式（函数式&面向对象）
  3. 原生给力的并发编程支持
  
Linux下的设置：
  GOROOT：安装目录
    export GOROOT=/usr/local/go
  GOPATH：工作目录
    export GOPATH=~/golib:~/goproject
    
工作目录结构：
  golib：
    src/ 源码文件
    pkg/ 归档文件 平台相关目录：$GOOS_$GOARCH
    bin/ GOBIN已设置则无效
    
源码文件：
  命令源码、库源码
  测试源码 _test.go后缀

命令基础
go run -a -n -p -v -work -x
go build
go install
go get
```

```
语言特点：
  1. 静态类型、编译型语言
  2. 脚本化的语法，支持多种编程范式（函数式&面向对象）
  3. 原生给力的并发编程支持
语言优势：
  1. 脚本化的语法
  2. 速度比动态类型、解释型语言快
  3. 原生的支持并发编程，降低开发、维护成本，程序能更好的执行
语言劣势：
  1. 语法糖少
  2. 速度不及C
  3. 第三方库少
  
Linux下的设置：
  GOROOT：安装目录
    export GOROOT=/usr/local/go
  GOPATH：工作目录
    export GOPATH=~/golib:~/goproject
  GOBIN: 存放可执行文件的目录
    export GOBIN=~/gobin
  PATH：
    export PATH=$PATH:$GOROOT/bin:$GOBIN
    
工作目录结构：
  golib：
    src/ 源码文件
    pkg/ 归档文件 平台相关目录：$GOOS_$GOARCH
    bin/ GOBIN已设置则无效
    
源码文件：
  命令源码、库源码
  测试源码 _test.go后缀
  
代码包声明和导入

命令基础
go run -a -n -p -v -work -x
go build
go install
go get
```

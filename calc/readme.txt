我是用goClipse生成的project，所以会生成bin, pkg，若没有，需要手动创建了。

配置GOPTH
export GOPATH=/Users/ray/Documents/go/calc
source /Users/ray/Documents/go/calc


cd bin

go build calc

顺利的话,将在该目录下发现生成的一个叫做calc的可执行文件

./calc
    USAGE: calc command [arguments] ...
2
 The commands are:
addAddition of two values.
sqrtSquare root of a non-negative value. 2 

$./calcadd 23
Result: 5
$ ./calc sqrt 9
Result: 3



测试代码：
$ go test simplemath
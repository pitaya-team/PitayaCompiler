# Pitaya Compiler

# 火龙果编译器
语法分析引擎，转换程序给转成C语言源码，编译成可执行程序文件

支持 Otne、Tbox、Pitaya


## demo.pitaya / demo.otne / demo.tbox

```
import stdio;
func main (){
  printf("Hello World");
}
```


## 转换程序给转成C语言源码
```
#include <stdio.h>
void func(){
  printf("Hello World");
}
int main()
{
    func();
    return 0;
}
```


## 火龙果编译器，编译成可执行程序文件

```
pitaya demo.pitaya -o demo.exe
demo.exe
Hello World
```

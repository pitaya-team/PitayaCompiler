# Pitaya Compiler

# 火龙果编译器
语法分析引擎，转换程序给转成C语言源码，编译成可执行程序文件

支持 Otne、Tbox、Pitaya


## demo.pitaya / demo.otne / demo.tbox

```
import pitaya.console;
func main (){
  printf("Hello World");
}
```

## 火龙果编译器，编译成可执行程序文件

```
pitaya demo.pitaya -o demo.exe
demo.exe
Hello World
```

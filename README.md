# waKuReverse
逆向工作中用到的内工具和相关的经验分享
## IOS Reverse
### 流程
* 砸壳 **frida-ios-dump**
* 静态分析 **IDA**
* Hook **Frida**
* 动态分析 **LLDB**
### Frida
#### 常用的API
* 构建原生函数
```
var f = new NativeFunction(ptr(xxx), 'void', ['int'])
```
### LLDB
#### 常用的API
### IDA

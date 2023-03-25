# 脚本 
该动作可以执行一些`Python`脚本。

![action](./images/2022-12-03_125827.png 'size=90%')


是否支持子流程：**否**


运行参数：

![param](./images/2022-12-03_125933.png 'size=90%')

* [Code] `Python`脚本。如果使用全局变量，可以在脚本里边加入`global`。例如：
```python
global a
```
  

输出：

    无输出。


### 脚本调用

```python
import simple;

global a

a = 10

```

### 示例

[https://github.com/shelllet/WinUi/blob/main/control/code.simple](https://github.com/shelllet/WinUi/blob/main/control/code.simple)


{{% notice tip %}}
最低版本要求: WinUi++ 0.14-beta.6 
{{% /notice %}}
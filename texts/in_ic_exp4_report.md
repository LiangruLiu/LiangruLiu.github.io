# Win 安装 GPU 版 Darknet 遇到的一个问题

<big><big><big><big>Q&emsp;</big></big>:&emsp;&emsp;</big></big>
在链接[【Win 安装 GPU 版 Darknet】](https://zhuanlan.zhihu.com/p/45845454)中，
我用那个 dog truck bicycle 的案例，运行之后没有预测框，预测出来的就是原图，最后也没有百分比输出。但也没有报错。

<big><big><big><big>A&emsp;</big></big>:&emsp;&emsp;</big></big>
属性 -> 配置属性 -> C/C++ -> 预处理器 -> 去掉预处理定义里面的 CUDNN_HAL。t

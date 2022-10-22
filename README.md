# 人工智能实践与应用

第一次作业：设计一个神经网络模拟三维动力系统

参考了densenet的思路，用卷积神经网络和全连接层简单地拟合了一个常微分方程刻画的动力系统（lorenz系统），我已经pre-train好了一个基础的模型，感兴趣的uu可以继续finetune，，我认为还没有到达期望误差的下界（应该还不是全局最优解），但是自己的调参经验调到头了，貌似LFBGS还可以继续降losshhhh，期待有人帮我做出来。实验结果如下图：

![test1](https://user-images.githubusercontent.com/77565562/197332324-c5ea9777-84f3-484f-87ee-94d2ad1bc52f.svg)
![test1_3d](https://user-images.githubusercontent.com/77565562/197332331-bdc7b3fd-ceb5-4d48-8981-04bf73ed9638.svg)
---

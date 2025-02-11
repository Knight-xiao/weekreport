## 参数设置：
源代码的参数设置如下：
- 学习率 actor_lr = critic_lr = 0.0002
- 折扣因子 gamma = 0.98
- GAE因子 lambda = 0.9
- 熵的系数： 0.01

效果：evaluation_00.png展示了该参数设置下的机械臂关节角度，关节速度以及机械臂末端与目标位置间的距离。
![evaluation_00](./evaluation_00.png)


## 图片说明
PS:只写相对于源代码进行了修改的参数。
- evaluation_01.png：添加了学习率衰减器，衰减率为0.99，每20次训练衰减一次，机械臂振荡。
![evaluation_01](./evaluation_01.png)

- evaluation_02.png：折扣因子gamma=0.95，机械臂振荡
![evaluation_02](./evaluation_02.png)



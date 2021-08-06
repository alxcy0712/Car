# Car
base on stm32,openmv  基于stm32和openmv的智能小车
## 基本设计实现（图）
<img src="https://github.com/liuxiaochen712/Car/blob/main/whole.png"></img>

- 整车由后轮驱动，两个后轮均装备编码器，利用PID调节速度
- 整车由STM-32控制，带有一个拓展板
- 车前方由180度舵机控制转向
- 车上装备OpenMv H7Plus摄像头用于图像识别


<br></br>
## 摄像头
<img src="https://github.com/liuxiaochen712/Car/blob/main/camera.png"></img>

1. 实现的功能
- 在寻迹过程中完成对特殊情况的处理（十字路口）
- 完成对人脸口罩的识别
- 对手写数字的识别
2. 运用的技术
- TensorFlow框架的机器学习模型
- Edge Impluse网站辅助机器学习

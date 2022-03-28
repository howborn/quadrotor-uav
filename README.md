# 四旋翼无人机

![预览图](https://github.com/howborn/quadrotor-uav/blob/master/四旋翼.jpg)

之前在学校 DIY 的四旋翼无人机，现整理收集到 github。程序代码无法找到了，只剩下硬件电路和无人机的照片。

## 3D模型

![整体](https://github.com/howborn/quadrotor-uav/blob/master/1.3D/整体.png)

![背面](https://github.com/howborn/quadrotor-uav/blob/master/1.3D/背面.jpg)

## 硬件电路

无人机使用 STM32 微控制器作为主控中心，HMC5883L 作为空间角度姿态传感器，MPU6050 作为空间 3 轴加速度分量和角速度传感器，MS5611 作为大气压传感器（测量海拔高度），无人机和遥控器通过 2.4G 信号进行通信。

遥控器硬件电路资料已丢失。

![主控电路](https://github.com/howborn/quadrotor-uav/blob/master/4.Photos/主控电路.jpg)

![姿态感知电路](https://github.com/howborn/quadrotor-uav/blob/master/4.Photos/姿态感知电路.jpg)

![无线通信](https://github.com/howborn/quadrotor-uav/blob/master/4.Photos/无线通信.jpg)

![电机驱动电路](https://github.com/howborn/quadrotor-uav/blob/master/4.Photos/电机驱动电路.jpg)

## 软件源码

软件源码资料已丢失。
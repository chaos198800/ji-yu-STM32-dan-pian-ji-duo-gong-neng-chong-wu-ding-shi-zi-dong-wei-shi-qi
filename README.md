# 基于STM32单片机多功能宠物定时自动喂食器

## 项目简介

本项目基于STM32单片机开发了一款多功能宠物定时自动喂食器。该喂食器不仅具备定时喂食功能，还能实时监测环境温湿度，并在温度过高时发出警报。通过LCD1602显示屏，用户可以查看当前时间、温湿度以及定时设置。

## 主要功能

1. **定时喂食**：用户可以通过按键设置喂食的小时和分钟，当定时时间到达时，LED灯闪烁提醒，并启动喂食电机进行喂食。
2. **温湿度监测**：喂食器内置DHT11温湿度传感器，能够实时采集环境温湿度数据。
3. **高温报警**：当环境温度超过设定值时，蜂鸣器会发出警报，提醒用户注意高温环境。
4. **时间显示**：通过DS1302时钟模块，喂食器能够显示当前时间，并在LCD1602显示屏上显示。

## 硬件组成

- STM32单片机
- LCD1602显示屏
- DHT11温湿度传感器
- DS1302时钟模块
- 按键
- 蜂鸣器
- LED灯
- 电机

## 软件设计

本项目使用C语言编程，程序代码采用Keil5编写，并附有详细的中文注释，方便新手理解和学习。仿真部分使用Proteus软件进行，演示视频使用的是Proteus8.9版本。

## 使用说明

1. **程序打开方法**：下载资料包后，请先解压（建议解压到桌面上，文件路径太深会导致程序打开异常），解压后再用Keil5打开程序。
2. **仿真演示**：仿真文件采用Proteus打开，演示视频可在资料包中找到。

## 资源文件内容

- 程序源码（Keil5项目文件）
- Proteus仿真文件
- 演示视频
- 相关软件包（Keil5、Proteus等）

## 注意事项

- 请确保下载资料包后先解压，再进行程序的打开和仿真操作。
- 本项目遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接和本声明。

## 联系我们

如有任何问题或建议，欢迎通过以下方式联系我们：
- 邮箱：example@example.com
- 电话：123-456-7890

---

希望本项目能为您的宠物喂食带来便利，同时也为您的学习和研究提供参考。

## 下载链接

[基于STM32单片机多功能宠物定时自动喂食器](https://pan.quark.cn/s/3a7e80e13c46)
---
title: 安全须知
date: 2020-05-08
version: 4.0.0
keywords: [OSDK, 安全必读]
---
在使用DJI OSDK 提供的示例或使用基于OSDK 开发的应用程序前，请认真阅读本文档中的内容，避免因违规操作而损毁无人机或引发不必要的安全问题。     

## 免责声明
* 在使用OSDK 开发的应用程序前，请先查阅飞行地所在区域的法律和规定，**因使用OSDK 而引发的安全问题或法律纠纷均与DJI 无关，DJI 不承担一切因使用OSDK 而导致的任何法律风险和责任**。
* 在实际测试或执行飞行任务前，请您先在DJI Assistant 2 中模拟使用DJI OSDK 开发的应用程序。
* 在使用OSDK 开发的应用程序执行任务时，请遵循用户手册中的各项说明，确保无人机在执行任务时处于良好的飞行状态，减少安全隐患，降低安全事故发生的可能性。
* **DJI 不会以任何方式和理由获取第三方使用者的隐私数据。**开发者使用DJI OSDK 高级视觉功能的接口开发具有对象识别等功能的应用程序时，应当开发**保护用户隐私数据的功能，如数据加密和混淆等**，凡因使用DJI 的无人机造成用户隐私数据泄露的事件，DJI 将不负任何法律责任。

## 开发与测试
使用OSDK 开发应用程序时，为保护开发者免受意外，请注意如下事项：
* 在使用OSDK 开发应用程序或测试基于OSDK 开发的应用程序时，请取下无人机上的桨叶；
* 无人机电机在转动时，请勿靠近；
* 请勿向无人机电源输出接口输入大功率电流；
> **说明：** 使用USB 连接无人机和用户电脑时，无人机将会进入安全保护模式，在该模式下，用户无法使用遥控器或OSDK 控制无人机解锁或启动无人机的电机。

## 飞行前检查事项
为了防止因应用程序突发故障、突发事件及违规作业等情况损毁无人机或产生安全事件，请在执行应用程序前，**请务必检查如下配置信息**：   
* **检查应用程序中的关键配置项**
    1. 请正确设置机载计算机或第三方开发平台中程序的**波特率和端口名称**；
    2. 请正确设置用于激活的**APP ID**和**APP KEY**。
* **检查设备状态**
    1. 请确保无人机和遥控器电池电量超过50％；
    2. 请确认DJI Assistant 2 、应用程序和终端工具的波特率一致。
    >**注意：** 更改波特率请重新启动飞行平台、遥控器和计算平台。
* **检查设备连接**
    1. 请按照[设备连接](./device-connection.html)中的步骤和要求将机载计算机或第三方开发平台连接至无人机或多旋翼飞控系统；
    2. 无人机遥控器已打开（需打开遥控器的软件，确保该软件能够访问互联网），遥控器**必须**连接至无人机。
    3. 首次激活激活应用程序或更换应用程序中的信息，如APP ID和APP KEY 时，请连接DJI Assistant 2 并在联网状态下激活应用程序。

## 飞行环境
* 请勿在如大风、雨及雪等极端天气环境中使用DJI 的无人机 和使用OSDK 开发的应用程序
* 请勿在楼层密集和人流密集的环境中使用无人机
* 请勿在有高压线，通讯基站或发射塔等区域飞行，避免遥控器受到无线信号的干扰
* 受环境因素的影响，无人机在高海拔地区执行飞行任务时，无人机的性能将会受到影响，请谨慎飞行
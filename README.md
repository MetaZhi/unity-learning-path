# 『不走弯路』Unity学习路线（主程方向）

本学习路线由大智（vx：zhz11235）凭个人经验编写，仅供参考，欢迎找大智交流（💬vx：zhz11235）。

由于大智了解的教程有限，本路线中 **《教程推荐》** 栏目，如果你有更好的教程，欢迎推荐或自荐，免费或付费课程都可。

👍教程推荐方法：找大智交流（💬vx：zhz11235）或github中发issue。

本文持续更新地址：https://github.com/MetaZhi/unity-learning-path



## 黑铁 LV0

### 本级描述

- 没有接触过Unity

- 无编程基础

### 📈升级指南

#### 🤹需学习技能点

- Unity基本操作（制作场景）
- Unity中核心组件的使用（相机、灯光、基本UI）
- unity assetstore找到所需资源及package的导入

#### 🎯学习目标

- 制作出第一个小小游戏

#### 🎓教程推荐

- 🆓3D游戏：Roll a ball（https://www.bilibili.com/video/BV1jK4y1G7g4/，英音中字）
- 🆓2D游戏：Ping Pong（https://blog.csdn.net/fujian87232/article/details/115321853，图文）

#### 📝升级自测（LV0 ↗️ LV1）

> 利用Unity内置的几何体制作一个教室场景（或其他你熟悉的场景），可以第一或第三人称漫游（使用角色控制包）。



## 青铜 LV1 ⭐

### 本级描述

- 能跟着教程制作微型案例

- 还无法独立写代码

### 📈升级指南

#### 🎯学习目标

- C#入门，能看懂常用Unity代码

- 能模仿并按自己的需求修改代码

#### 🎓教程推荐

- 🆓C# https://learn.u3d.cn/tutorial/beginner-gameplay-scripting

#### 📝升级自测（LV1 ↗️ LV2）

实现和平精英中的吃药回血机制，不需要图形化界面，输出到Console中即可。实现以下功能：

> ##### 角色血量
>
> - 可以在Inspector中设置
>
> - 最大血量100
>
> ##### 能量
>
> - 初始能量0
>
> - 满能量100点
>
> - 每3秒掉1点能量
>
> ###### 能量回血机制
>
> - 能量在(0, 20]之间：每8秒回1点血
>
> - 能量在(20, 60]之间：每8秒回复2点生命值
>
> - 能量在(60, 90]之间：每8秒回复3点生命值
>
> - 能量在(90, 100]之间：每8秒回复4点生命值
>
> ##### 按下键盘1-6
>
> ###### 1 绷带
>
> 回复10血量，最高回到75
>
> ###### 2 急救包
>
> 回复**到**75的血量
>
> ###### 3 医疗箱
>
> 回复到**100**的血量
>
> ###### 4 红牛
>
> 回复40的能量
>
> ###### 5 止痛药
>
> 回复60的能量
>
> ###### 6 肾上腺素
>
> 回复100的能量
>
> ##### 按下键盘0
>
> 随机损失一定的血量，最低血量到1

---



## 白银 LV2 ⭐⭐

### 本级描述

- 能看懂常见Unity代码

- 跟着教程完整制作过微型案例

### 📈升级指南

#### 🎯学完目标

- 跟着教程完成小型案例
- 对大学生来说，能完成课程大作业
- 可以根据自己的需求修改部分功能

#### 🎓教程推荐

- 🆓盒子跑酷（英文，免费） https://www.youtube.com/playlist?list=PLPV2KyIb3jR5QFsefuO2RlAgWEz6EvVi6
- 🆓2D Flappy Bird（https://www.bilibili.com/video/BV1jK411V7V7/）

#### 📝升级自测（LV2 ↗️ LV3）

> 制作并发布Flappy Bird游戏给你的朋友玩。



## 黄金 LV3 ⭐⭐⭐

### 本级描述

- 熟悉Unity中常见模块

- 跟着教程制作过小型案例

### 📈升级指南

#### 🎯学习目标

- 掌握Unity游戏开发中的常用模块，如：
  - 物理
  - UI
  - 动画

#### 🎓教程推荐

- 🆓2D Ruby Adventure
  - 图文，免费：https://learn.u3d.cn/tutorial/unity-ruby-adventure

  - 视频 免费：https://www.bilibili.com/video/BV1tW4y177Ui
- 🆓2D平台游戏-Youtube（英文）：https://www.youtube.com/watch?v=oxiPWg8cdRM&t=14755s&pp=ygUOdW5pdHkgdHV0b3JpYWw%3D

#### 📝升级自测（LV3 ↗️ LV4）

> 可以模仿超级玛丽制作出前2关



## 铂金 LV4 ⭐⭐⭐⭐

### 本级描述

- 可以从0制作出原创微型项目

### 📈升级指南

#### 🤹需学习技能点

- 编辑器扩展
- 配置文件

#### 🎯学习目标

- Unity中型案例制作（本科毕业设计难度、求职作品）
  需要一定的原创性，要使用较多的技术点

- 能制作独立游戏

- Unity实习生

#### 🎓教程推荐

- 植物大战僵尸 https://www.bilibili.com/video/BV1fd4y1P7E9/
- 跑酷类游戏

  - 地铁跑酷 核心功能

  - 神庙逃亡

#### 📝升级自测（LV4 ↗️ LV5）

> 从0制作一款塔防游戏，发布到webgl或移动端
>
> - 可以搜索、参考教程
>



## 钻石 LV5 ⭐⭐⭐⭐⭐

### 本级描述

- 任职Unity实习生

- 可以从0制作出原创小型项目

### 📈升级指南

#### 🤹需学习技能点

- 性能优化入门
- 设计模式

#### 🎯学完结果

- Unity初级工程师

- 能独立接小型外包

#### 🎓教程推荐

- 📕《大话设计模式》书籍
- 🆓《Unity性能优化》系列课程 https://learn.u3d.cn/tutorial/unity-optimization-metaverse/

#### 📝升级自测（LV5 ↗️ LV6）

> 模仿绝地求生制作一个大场景（至少1kmx1km）的FPS单机游戏
>
> - 包含AI NPC敌人
> - 可以在中端机上流畅运行（优化）
>



## 大师 LV6 ⭐⭐⭐⭐⭐⭐

### 本级描述

- 任职Unity初级工程师

- 可以独立接小型外包

### 📈升级指南

#### 🤹需学习技能点

- 网络编程
- 架构
- 热更新
- Shader

#### 🎓教程推荐

- 🆓Unity 游戏框架搭建 决定版（试听） https://learn.u3d.cn/tutorial/framework_design_trail
- 💰Unity 游戏框架搭建 决定版（598元） https://learn.u3d.cn/tutorial/framework_design
- xLua教程（没找到能入选的教程，可以推荐或自荐给大智 vx：zhz11235）
  -   【版本老旧】Unity2017.2打鱼游戏 https://www.bilibili.com/video/BV1XJ411y7pB/

- 💰ILRuntime与代码热更新框架的搭建技巧（168元） https://learn.u3d.cn/tutorial/ilruntime

#### 🎯学完结果

- Unity中级工程师

- 能独立接中型外包

#### 📝升级自测（LV6 ↗️ LV7）

> 用Unity实现手机端通过局域网控制PC端项目的程序
> - 采用UDP嗅探局域网中的PC主机
> - 手机端通过屏幕滑动控制PC端光标移动
> - 手机端通过点击和双指点击控制PC端鼠标左键、右键的按下
>
> 【附加题】整理一个自己的Unity框架，包含常用的工具
> - 资源管理
> - 热更新
> - UI框架



## 宗师 LV7 ⭐⭐⭐⭐⭐⭐⭐

### 本级描述

- 任职Unity中级工程师

- 可以从0制作出原创中型项目

### 📈升级指南

#### 🤹需学习技能点

- 性能优化深入，理解Unity底层原理，（如果有机会）阅读源码
- 不同平台的渲染原理及优化策略
- 熟悉各种技术方案的优劣

#### 🎯学习目标

- 晋升Unity客户端主程

#### 🎓教程推荐

- 每年的Unite分享
- 苹果开发者大会
- 显卡硬件厂商提供的手册
  - [Arm GPU Best Practices Developer Guide](https://developer.arm.com/documentation/101897/0301/?lang=en)
  - [Mali GPU公开课 - Youtube](https://www.youtube.com/watch?v=tnR4mExVClY&list=PLKjl7IFAwc4QUTejaX2vpIwXstbgf8Ik7)
  - [Mali GPU性能工具Streamline手册](https://developer.arm.com/documentation/101816/0805/?lang=en)

- [GPUOpen.com](https://gpuopen.com/)

#### 📝升级自测（LV7 ↗️ LV8）

> 可以根据不同的项目类型及要求，研究并制定合适的技术路线



## 👑王者 LV8 ⭐⭐⭐⭐⭐⭐⭐⭐

### 本级描述

- 任职Unity客户端主程

### 📈升级方向

- 技术管理
- 技术向
  - 服务端（全栈）
  - TA
  - 引擎开发
- 自媒体
- 转行
- 创业



## 备注

本学习路线由大智（vx：zhz11235）凭个人经验编写，仅供参考，欢迎找大智交流（💬vx：zhz11235）。

由于大智了解的教程有限，本路线中 **《教程推荐》** 栏目，如果你有更好的教程，欢迎推荐或自荐，免费或付费课程都可。

👍教程推荐方法：找大智交流（💬vx：zhz11235）或github中发issue。

![image-20230424161457543](README.assets/image-20230424161457543.png)



本文持续更新地址：https://github.com/MetaZhi/unity-learning-path

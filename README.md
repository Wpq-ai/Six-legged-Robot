这个仓库主要是本科的毕业设计相关资料，其中论文文档文件夹为整个项目的介绍，其他的文件夹是相关的工具文件。这个项目是基于STM32的六足机器人控制系统设计，详细的介绍参考[论文文档文件夹](https://github.com/linyongxinhio/Six-legged-Robot/blob/master/0.%E8%AE%BA%E6%96%87%E6%96%87%E6%A1%A3/1.%E6%AF%95%E4%B8%9A%E8%AE%BA%E6%96%87.doc)。

摘要如下：

> 本设计主要是基于单片机的六足机器人控制系统设计，综合分析六足机器人的结构、步态和控制算法，结合云端服务器、WIFI技术、蓝牙技术、语音识别技术和手势识别技术进行多种控制模式的设计，并提出不同应用场景的不同构建方案。
>
> 本系统的硬件设计分为主控板和舵机控制板两部分。主控板主要负责各种控制模式的数据处理和显示，舵机控制板主要负责舵机转动角度的控制，两板通过串口进行数据的交互。主控制板采用STM32F103VET6芯片，舵机控制板采用STM32F103R8T6芯片，两者都基于ARM的Cortex M3内核进行设计的。主控制板的硬件电路设计主要有启动电路、晶振电路、下载电路、复位电路、稳压电路以及各个模块接口电路。在Altium Designer16软件中进行原理图的绘制和PCB的绘制，打样后进行焊接并完成整体的测试。
>
> 本系统的上位机主要是手机APP，其开发环境是Android Studio，采用C#作为云端开放平台语言，JAVA语言作为移动客户端设计语言，通过JAVA语言的编写实现手机客户端的数据接收和发送，最终实现基于云端和蓝牙的控制系统上位机板块的设计。本系统下位机的软件设计是在Keil5编程环境下进行的，参考STM32F1的手册和各个模块的数据手册进行程序的编写，最终实现云端控制、蓝牙控制、语音控制和手势控制这四种控制系统设计。
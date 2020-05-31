# cpu_4bit
数字电子技术理论课大作业，小组成员：ly,yrz,hzf,wsc,lhr

参考项目为TD4-4BIT-CPU by wuxx

实际上叫4位CPU不妥，应该叫做能实现一些和8086类似功能的数据处理器

仿真软件: Multisim 14.0

仿真文件：cpu_4bit.ms14

指令集：  Instruction.pdf

电路图：  cpu_4bit.pdf

说明： 1.电路支持两种代码写入模式，一种是由开关二极管及下拉电阻构成的ROM阵列，另一种是通过RAM写入，但此输入模式不稳定。文件中预设的输入模式是ROM阵列。

      2.电路时钟信号有两种模式，一种是自动信号（两种频率），另一种是用手动信号。
      
      3.蓝色线是数据总线，黑色线是控制信号线，紫色线是指令指针计数器，绿色线是时钟信号及复位端，红色为其他。
      
      4.由于逻辑键值（数字信号源，开关）有重复，所以仿真文件中的全部控制信号请通过鼠标电点击来控制。

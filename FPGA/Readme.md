# 说明
  这里是Verilog实现CNN加速器代码的文件夹，使用的是ZYNQ7100（CPU+VU9P暂不考虑开源），会提供相关的仿真文件，计划从2020.04.01日更，大致章节如下
  * CPU与FPGA之间的数据交互
  
    * AXI DMA的使用
  * CPU与FPGA之间的指令交互
  * FPGA内部的数据传输
  * 计算结构的设计
    
    * 卷积层
    * 池化层
    * ReLu
    * 全连接层
    * 上采样
# 软件版本
  Vivado 2019.2
# MTGV2 QEI ABZ 例程

## 概述

MTGV2 QEI ABZ 例程演示了使用QEI ABZ类型编码器作为数据输入，经过MTGV2的滤波器进行处理，以及经过轨迹预测模块对其进行时间补偿的功能。例程输出QEI的原始数据和经过MTGV2处理后的数据，并输出两者之间的差值。

## 硬件设置

无特殊设置

## 运行现象

当工程正确运行后，串口终端会输出如下信息：
mtg qei example
time, QEI_REV, QEI_POS, MTGV2_REV, MTGV2_POS, MTGV2_VEL, MTGV2_ACC,MTGV2_REV_POS-QEI_REV_POS

0.108948,2,0.126709,2,0.126818,417,0,0.000109
0.113917,2,0.223633,2,0.223768,420,0,0.000135
0.118819,2,0.319580,2,0.319734,421,0,0.000154
0.123719,2,0.415772,2,0.415840,421,0,0.000069
0.128620,2,0.511719,2,0.511772,420,0,0.000054
0.133520,2,0.606934,2,0.607103,418,0,0.000170
0.138421,2,0.702637,2,0.702758,419,0,0.000121
0.143321,2,0.798340,2,0.798567,419,0,0.000227
0.148222,2,0.894775,2,0.894863,417,0,0.000088
0.153123,2,0.990234,2,0.990382,418,0,0.000148
0.158023,3,0.085205,3,0.085410,417,0,0.000205
0.162924,3,0.180664,3,0.180894,420,0,0.000230
0.167825,3,0.276855,3,0.276845,419,0,-0.000011
0.172812,3,0.374512,3,0.374673,422,0,0.000162
0.177713,3,0.470703,3,0.470737,419,0,0.000034
0.182613,3,0.566162,3,0.566257,419,0,0.000095
0.187513,3,0.661865,3,0.662009,422,0,0.000144
0.192414,3,0.757813,3,0.758032,420,0,0.000220
0.197314,3,0.853760,3,0.853958,419,0,0.000198
0.202215,3,0.949707,3,0.949708,418,0,0.000001
0.207115,4,0.044678,4,0.044839,418,0,0.000161
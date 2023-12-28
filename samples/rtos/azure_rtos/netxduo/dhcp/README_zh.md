# Netx Duo Dhcp

## 概述

这个例程演示了netx的dhcp功能。

## 硬件设置

无特殊设置

## 工程配置

- 以太网端口配置：参考 [以太网通用工程设置](../../../../lwip/doc/Ethernet_Common_Project_Settings_zh.md)


## 运行现象

当工程正确运行后,链接状态会被周期性的打印到终端上,直到链接状态为Up.DHCP的信息也会打印到终端上。
```console
NetXDuo is running␍␍␊
DHCP In Progress...␍␍␊
Enet phy init passed !␍␊
Link Status: Down␍␊
Link Status: Up␍␊
Link Speed:  100Mbps␍␊
Link Duplex: Full duplex␍␊
IP address: 192.168.50.76␍␍␊
Mask: 255.255.255.0␍␍
```
---
layout: post
title: "How-to-ping-from-vmware-to-host-using-ubuntur"
date: 2024-06-29
---

# STM32MPU Development




## 使用VMware Uubntu虚拟机如何ping通宿主机

要使用VMware Ubuntu虚拟机和主机通信，需要保证两者在同一个局域网下。

1、通常，VMware通过VMnet0与宿主机连接。在VMware中选择Edit->Virtual Network Editor->Change Settings->VMnet0->Bridged to

<p align="center">
  <img src="https://dwgan.top/PicGo/img/image-20241203162302053.png" style="zoom: 33%;" />
</p>



<p align="center">
  <img src="https://dwgan.top/PicGo/img/image-20241203162410872.png" style="zoom: 33%;" />
</p>



2、桥接到你实际要用的网卡上，打开任务管理器，可以看到对应的网卡名称。点击OK，打开虚拟机

<p align="center">
  <img src="https://dwgan.top/PicGo/img/image-20241203162524414.png" style="zoom: 33%;" />
</p>



3、尝试ping宿主机，成功

<p align="center">
  <img src="https://dwgan.top/PicGo/img/image-20241203163743132.png" style="zoom: 33%;" />
</p>

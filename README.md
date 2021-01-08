# B460M-MORTAR

## iMac: 20,1  And OPENCORE: 6.1

[感谢远景大佬 dust26 ](http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1861472) ，我只是大自然的搬运工。



## 支持的版本

版本：Catalina [10.15.7 ](https://blog.daliansky.net/macOS-Catalina-10.15.6-19G73-Release-version-with-Clover-5119-original-image-Double-EFI-Version-UEFI-and-MBR.html)及更高，Big Sur 11



## 我的配置 

|   部件   |        型号         |
| :------: | :-----------------: |
|   主板   |  MSI B460M-MORTAR   |
|  处理器  |   INTEL i5 10400    |
|   显卡   | Radeon RX 550 4 GB  |
|   硬盘   |  WDC PC SN720 256G  |
|   内存   | 64 GB 2667 MHz DDR4 |
| 无线网卡 |     BCM94360CS2     |



## 安装说明：Windows下

1. `TransMac` 恢复到U盘。

2. 用 `DiskGenius` 删除U盘中`EFI`分区的所有文件。将该项目的所有文件复制进去。

3. BIOS 设置。

   ![](https://images.gitee.com/uploads/images/2020/0716/201858_0703b82f_1789893.png "屏幕截图.png")

4. U盘启动。

5. 安装成功后，有线网络配置。

   ![](https://images.gitee.com/uploads/images/2020/0706/113528_a37a8a62_1789893.png "屏幕截图.png")




## 更新 2020-11-06 版本.

**2020年11月6**号更新一个最新版efi基于oc0.6.3正式版，机型使用最新的iMac20,1，更新了所有插件到最新版，声卡id使用了APPLEALC最新版微星主板定制的ID 11，适配度更高，精简了一些插件，config文件里加入了适配5000系列显卡的（需要自己改名）,最新添加了适用于集成显卡的config文件（只适用于主板dp接口），**只适用于最新版10.15.7系统**，big sur系统理论上也能用但我自己没测试，风险自己承担

## 更新 2020-12-13 版本.

**2020年12月7日**小更新一下核显部分代码，适配最新版whatevergreen，实测fcpx预览更流畅（big sur系统也已经测试没问题了）,同时更新所有插件到最新版
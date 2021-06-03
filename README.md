# minisforum-H31-Hackintosh

## 电脑配置

|   规格   |                           详细信息                           |
| :------: | :----------------------------------------------------------: |
| 电脑型号 |                        minisforum H31                        |
| 操作系统 |                  macOS Big Sur 11.4 `20F71`                  |
|  处理器  |                     英特尔 酷睿 i7-9700                      |
|   内存   |                        16 GB 2666MHz                         |
|  硬盘1   |             KINGSTON OM8PDP3256B-A01[NVMe 2280]              |
| 硬盘2/3  |              可接SATA 2.5寸硬盘/SSD[SATA 2242]               |
|   显卡   |                    Intel UHD Graphics 630                    |
|  显示器  |                              无                              |
|   声卡   |                   Realtek ALC892 `alcid=7`                   |
|   网卡   | m.2 NGFF插槽，已更换为[BCM94360Z4](https://blog.daliansky.net/uploads/WeChatandShop.png) |

## 更新日志

- 6-3-2021
- 第一次提交

### 设置`BIOS`

- 安全菜单：

  - 安全启动 -> `关闭`  (*Disable Secure Boot*)

- 高级菜单：

  - CPU菜单：`CFG Lock` -> `关闭` (*Disabling CFG Lock*)【相关BIOS请进群获取】

- 设备：

  - 显示设备
    - 预指派内存大小：`64MB` (*DVMT* pre-allocated memory)

  - ATA设备菜单：
    - `配置SATA为` -> `AHCI`

- 其它参数默认即可



## 白嫖指北手册

三码生成教程：https://mp.weixin.qq.com/s/GCMv-oMGKvZFLNMEuUPPfA

## 截屏

![Hackintool](./screenshots/Hackintool.png)

![Hackintool_Miscs](./screenshots/Hackintool_Misc.png)

![Hackintool_Audio](./screenshots/Audio.png)

![Hackintool_USBPorts](./screenshots/Hackintool_USB.png)

## 其它信息

minisforum H31黑苹果交流群：[869792897](https://qm.qq.com/cgi-bin/qm/qr?k=TdIS59sEdBCjbz8NbdrQ2IyPG6bMza3_&jump_from=webapi)

minisforum H31购买链接：[黑果小兵的部落阁](https://hackintosher.taobao.com/) 

## 感谢名单：

- [Apple](https://apple.com/) for macOS;
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/icelake.html) For great and detailed guides.

- [jozews321](https://github.com/jozews321) For the injection information in the U820 device properties


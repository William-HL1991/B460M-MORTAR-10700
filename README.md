forked from ![abner-xu/efi](https://github.com/abner-xu/efi)
# 微星B460M+10700+RX5500XT
> 申明：配置并非本人原创，本人也是初学者，全部配置文件收集于远景论坛

## 硬件配置

|  配置   | 型号  |
|  ----  | ----  |
| CPU  | I7-10700 |
| 散热 | 恩杰M22 |
| 主板  | B460M 迫击炮 |
| 内存  | 金士顿雷电灯条3200 16G*2 |
| 固态1  | 三星970EOV Plus 500G(macos) |
| 固态2  | 三星PM981a 256G(windows) |
| 机械硬盘 | 希捷1TB |
| 显卡  | 微星魔龙RX5500XT |
| wifi  | FV-T919 bcm94360cd  |
| 电源  | 追风者AMP金牌全模组550W |
| 机箱 | 追风者410 |


## 主板配置
主板版本 7C82v11 更新主板BISO ：https://cn.msi.com/Motherboard/support/MAG-B460M-MORTAR#down-bios

- Fast Boot：关闭
- Secure Boot：关闭（默认关闭的）
- CFG lock（关闭重要）
- Intel SGX 如果有，关闭，默认关闭的
- VT-x 开启
- Above 4G decoding 开启（重要）
- Hyper-Threading 开启（默认都开的）
- EHCI/XHCI Hand-off 开启（默认都开的）
- 显存: 64MB

USB唤醒设置：

![唤醒](https://raw.githubusercontent.com/William-HL1991/BlogAlbum/master/B460M-MORTAR-10700/HX.png)

# win和mac双系统时间不一致问题
win修改注册表
```shell
Reg add HKLM\SYSTEM\CurrentControlSet\Control\TimeZoneInformation /v RealTimeIsUniversal /t REG_DWORD /d 1
```

## 系统预览
![概览](https://raw.githubusercontent.com/William-HL1991/BlogAlbum/master/B460M-MORTAR-10700/XT.png)
![电源](https://raw.githubusercontent.com/William-HL1991/BlogAlbum/master/B460M-MORTAR-10700/DY.png)
![核显加速](https://raw.githubusercontent.com/William-HL1991/BlogAlbum/master/B460M-MORTAR-10700/VideoProc.png)
![显卡](https://raw.githubusercontent.com/William-HL1991/BlogAlbum/master/B460M-MORTAR-10700/XK.png)
![airdrop](https://raw.githubusercontent.com/William-HL1991/BlogAlbum/master/B460M-MORTAR-10700/AirDrop.png)
![imessage](https://raw.githubusercontent.com/William-HL1991/BlogAlbum/master/B460M-MORTAR-10700/hand-off.png)


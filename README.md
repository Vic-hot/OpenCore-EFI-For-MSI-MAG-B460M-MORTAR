### 简介
更新日期：2025.6.10

当前OC版本：1.0.6

当前系统版本：15.7.2

本EFI适用于微星B460M迫击炮，其他主板仅供参考

### 主机配置
CPU：Intel Core i5-10500

主板：微星 B460M MORTAR WIFI

内存：三星 16GB DDR4 3200

核显：Intel UHD630（仅加速）

独显：HP RX580 4G

有线网卡：RTL8125（板载）

无线网卡：Intel AX200（蓝牙功能正常，WiFi功能未使用未打补丁）

固态：SKhynix 256G nvme

### 功能测试
-✅ 睡眠/唤醒

-✅ 所有USB端口

-✅ 核显硬件加速

-✅ 声卡输出

-✅ 蓝牙

-✅ 板载有线网卡

-✅ 板载无线网卡（需要手动patch，仅支持接力不支持隔空投送、随航）

### BIOS 设置
- Settings -> 安全 -> 安全引导 -> 安全启动：关闭
- Settings -> 唤醒设置 -> USB设备从S3/S4/S5唤醒：允许
- Settings -> 唤醒设置 -> PS/2鼠标从S3/S4/S5唤醒：允许
- Settings -> 唤醒设置 -> USB键盘从S3/S4/S5唤醒：任意键
- Settings -> 高级 -> 内建显示器配置 -> 集成显卡多显示器：允许（否则核显硬件解码失效，只使用核显的可以忽略）
- Settings -> 高级 -> PCIe -> PCI子系统设置 -> Re-Size BAR Support ：禁止
- OC -> CPU 特征 -> Intel 虚拟化技术：允许
- OC -> CPU 特征 -> Intel VT-D 技术：禁止（驱动 WIFI 需开启）
- OC -> CPU 特征 -> CFG锁定：禁止


请自行填写三码！请自行填写三码！请自行填写三码！

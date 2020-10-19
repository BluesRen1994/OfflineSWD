# SWD离线烧写器
本项目使用STM32F103RET6作为主控，基于ST官方CMSIS-DAP项目进行修改，实现可脱机、可去读保护烧写（因项目暂时只有F103系列脱机烧写需求，所以暂时只添加了F103的烧写算法）。
#### <br>
## 项目功能
#### 1.使用8M FLASH，可使用虚拟U盘向FLASH放置HEX文件或BIN文件进行烧写（BIN较快）
#### 2.可去除目标板的读保护，直接烧写（烧写后可能需要手动重启）
#### 3.支持手动切换模式，使离线烧写器支持DAP仿真
#### 4.安装驱动后可支持虚拟USB转TTL
#### 5.可离线使用串口调试功能（仅支持英文及常用数字符号）
#### <br>
## 使用教程
#### 1.长按SELECT键开机可进入DAP仿真模式，屏幕上显示DAP-CONNECT
#### 2.直接插入电脑USB端口可向离线烧写器放入相关烧写文件，并可使用虚拟串口功能
#### 3.连接目标板开机，选择文件后选择FLASH后即可进行烧写
#### 4.选择“>>”，进入DEBUG MODE后选择ENTER即可进行离线串口调试
#### <br>
## 其他
#### 项目包含开源CMSIS-DAP中的相关文件，请自行包含以下目录（...\Arm\Packs\ARM\CMSIS\5.6.0\CMSIS及...\Arm\Packs\ARM\CMSIS\5.6.0\CMSIS\Include）
## 项目意见
#### 如果项目有问题或者有新功能需求，欢迎向作者提交意见！
#### 联系方式 QQ/微信：624644898

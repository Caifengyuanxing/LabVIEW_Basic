# LabVIEW_Basic
LabVIEW


1.下位机STM32F4，LWIP以太网协议传输到上位机，传输的数据是压缩的JPEG格式，上位机用LabVIEW做的，接收320  240 大小的还顺畅，更大的可能有点卡，有待提高

2.多种数据先存入表格控件中，定时结构每秒记录一次数据，利用时间字符串进行比较，条件结构实现每小时存储成一份文件

3.利用USB手柄直接插在电脑上，可以直接在vi中进行检测到，通过按键，可实现连续发送或者每按下按钮发送一次

4.在LabVIEW环境中调用百度地图

5.表格写入不进行覆盖，一种是直接用局部变量，另一种用移位寄存器，显然后者效率更高

6.利用设置文件写入位置控件


# DHT11_drive-Raspberry-Pi-PythonDHT11 
湿度温度传感器 驱动

使用方法： 接线 DHT11的三个引脚(如果是四个引脚NC不连接) VCC接5V GND接地 数据D接任意树莓派GPIO口
并将数据D接的树莓派GPIO口BCM编号设置为下面的pin 
然后你可以直接运行本文件得到数值，也可以使用import dht11_drive导入模块
导入后使用 dht11_drive.dht11() 函数获取湿度与温度 返回值是一个元组

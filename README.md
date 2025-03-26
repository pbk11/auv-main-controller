# auv-main-controller 基于全志H3（soc）的自主式水下航行器控制系统                 

* 基于全志H3外设，增设通讯管理IC，拓展RS485、UART串口等多样接口驱动姿态传感器、深度传感器等外设。

* 通过LM5069栅极驱动背靠背mos管，实现小型化电源开关，有效管理电池供电。


* 使用sepic拓扑，实现高边隔离dcdc转换，输出12V，最大功率50W供给jetson orin使用。使用COT（恒定时间导通模式）mp2338，输出5V、3.3V，纹波小于40mV。

* 集成基于RTL8305的板载交换机，完成线路阻抗匹配设计，单口最高通讯速率可达96Mbps。
https://github.com/pbk11/auv-main-controller/blob/main/img/3D%20BOTTOM.png
https://github.com/pbk11/auv-main-controller/blob/main/img/3D%20BOTTOM.png

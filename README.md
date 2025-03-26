# auv-main-controller 基于全志H3（soc）的自主式水下航行器控制系统                 

●基于全志H3外设，增设通讯管理IC，拓展RS485、UART串口等多样接口驱动姿态传感器、深度传感器等外设。

●通过LM5069栅极驱动背靠背mos管，实现小型化电源开关，有效管理电池供电。

●使用sepic拓扑，实现高边隔离dcdc转换，输出12V，最大功率50W供给jetson orin使用。使用COT（恒定时间导通模式）mp2338，输出5V、3.3V，纹波小于40mV。

●集成基于RTL8305的板载交换机，完成线路阻抗匹配设计，单口最高通讯速率可达96Mbps。48h+运行测试下，维持低丢包率。
![image](https://github.com/user-attachments/assets/cf79f257-5242-446d-9f42-996bb6912718)
![image](https://github.com/user-attachments/assets/9adf3938-d3a0-457d-a849-cd9791d5828a)
![image](https://github.com/user-attachments/assets/e47c52e7-0fc5-43f0-b1fd-35470b47cdd3)
![image](https://github.com/user-attachments/assets/2e5afc1e-c2b1-40d1-94ea-80ee3a81890c)

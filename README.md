# bl0910-for-esphome
10 channel power meter by BL0910 with esphome
依据贝岭BL0910芯片设计；
ESP8266使用ESP-01S；
默认使用UART通讯，TX/RX需要上拉电阻；
预留SEL、CS、SCLK引脚，通过对应的电阻进行选择，可改变UART通讯速率/使用SPI通讯；

![image](https://github.com/MiaoJiawei/bl0910-for-esphome/blob/main/circuit%20board/2D_%E5%8F%8D%E9%9D%A2%E8%B4%9F%E8%BD%BD_2024-11-02.png)
![image](https://github.com/MiaoJiawei/bl0910-for-esphome/blob/main/circuit%20board/2D_%E5%8F%8D%E9%9D%A2%E8%B4%9F%E8%BD%BD_2024-11-02-2.png)
![image](https://github.com/MiaoJiawei/bl0910-for-esphome/blob/main/circuit%20board/3D_%E5%8F%8D%E9%9D%A2%E8%B4%9F%E8%BD%BD_2024-11-02.png)

引用链接：
https://bbs.hassbian.com/thread-19938-1-1.html
https://bbs.hassbian.com/thread-24269-1-1.html

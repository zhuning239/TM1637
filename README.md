# 四位数码管 (TM1637)
makecode 四位数码管 (TM1637) microbit 软件包

带1-6（普通4）7段LED的LED数字显示模块，它可以显示数字。里面有TM1637芯片，用一个2线接口控制；

作者: 朱林
时间: 2018/4

![image](https://github.com/zhuning239/TM1637/blob/master/icon.png)

## 使用方式

打开 makecode 编辑器，在项目中选择添加软件包，然后在地址栏输入下面网址：  

https://github.com/zhuning239/TM1637  

搜索后就可以添加并使用本软件包了。

![image](https://github.com/zhuning239/TM1637/blob/master/4-LED.jpg)

## API

- **create(clk: DigitalPin, dio: DigitalPin, intensity: number, count: number)**  
create a TM1637 object.  
  - clk, any DigitalPin  
  - dio, any DigitalPin  
  - intensity, set display brightness, range [0-8]  
  - count, LED count, range [1-5]  

- **on()**  
turn on the display.  

- **off()**  
turn off the display.  

- **clear()**  
clear content of the display.  

- **showbit(num: number, bit: number)**  
show a digit number in given position.  

- **showNumber(num: number)**  
show a interger number in display.  

- **showHex(num: number)**  
show a hex number.  

- **showDP(bit: number, show: boolean)**  
show or hide dot piont in give bit  
bit is dot piont position, [0 - count]  
show, True will show DP, other will hide it  

- **intensity(dat: number)**  
set display intensity.  

## 演示

![image](https://github.com/zhuning239/TM1637/blob/master/demo.jpg)

## 授权方式  

MIT

湖南创乐博智能科技有限公司 

## 支持硬件 

* for PXT/microbit


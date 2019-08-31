# Project Title 

2019FIRA_FC_CODE

## Description

该代码为参加2019年FIRA 无人机竞速钻框时，五人家使用的飞控代码，是对匿名脱空者飞控代码的修改版，修改以后实现了代码和遥控器的同时控制及切换，可以及时在代码控制出现意外时，转换成遥控控制。

[2019FIRA无人机竞速钻款完整代码链接](https://github.com/Unrivaled2/2019FIRA_QUADROTOR)

## Getting Started

### Prerequisites

飞控：匿名拓空者
遥控器：乐迪F110S

## Installing

将该源码刷进飞控即可，将SWA开关拨到上方，遥控控制，要SWA开关拨到下方，程序控制

非乐迪遥控器：
原理是修改第五通道的值，1500为程序控制，2000为代码控制，使用其它遥控器，只需要设置修改第五通道值的开关即可

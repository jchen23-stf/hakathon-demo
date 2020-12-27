# 一站式视障用户乘坐公交解决方案
我们此次的产品从上车到下车目的是一站式协助视障人士乘坐出租车。我们的解决方案由涵盖软硬件 - 硬件方面我们制作了一个红外发射接受器协助用户在接近公交车时（5-10米）找到车门，软件方面我们制作了一个界面简洁的公交导览图，使得用户可以使用操作系统自带的voice over功能快速获得公交信息。

## 红外协助上车系统
此系统由在车门上的发射器和佩戴在用户身上的接收器构成。发射器安装在车门顶端，当用户身体转到发射器方向时，系统自带的扬声器将会提醒用户方向正确，可以往车门方向前进。同时车内的发射器会提示司机有视障人士准备上车，让司机准备。

## 软件协助系统
用户可以在首页的搜索框输入终点，后台将会通过API向高德地图后台发送路线规划请求，收到数据解析后将会呈现在我们的用户界面上。与传统地图软件不同的是，我们的前端设计抛弃了线性的浏览设计，以目录式的信息方便我们的用户使用voice-over快速获取信息。用户只需要划动数下就可以获取包括起始站，终点站，距离站数等信息。同时我们在主界面设有快捷键，用户可以一键公交导航至家，办公室，医院等地点。

![](/信息无障碍13+15/interface/)

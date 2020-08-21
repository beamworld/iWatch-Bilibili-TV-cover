# iWatch-Bilibili-TV-cover
​	本项目为手表iWatch的Bilibili小电视外壳，目前适用于桌面放置使用。功能如下：

1. 三个按键引出；
2. 耳机通孔引出；
3. Micro USB充电孔引出；
4. 屏幕开孔；

​	**上美图~**

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Bilibili-TV_AD.9.png?raw=true" style="zoom:50%;" />

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Bilibili-TV_AD.5.png?raw=true" style="zoom:50%;" />

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Bilibili-TV_AD.19.jpg?raw=true" style="zoom:50%;" />

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Bilibili-TV_AD.18.jpg?raw=true" style="zoom:50%;" />

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Bilibili-TV_AD.20.jpg?raw=true" style="zoom:50%;" />



​	又增加了一款手表外壳（Thin-cover），可以佩戴在手上。功能如下：

1. 三个按键引出；
2. 耳机通孔引出；
3. Micro USB充电孔引出；
4. 屏幕开孔；
5. 露出表带安装孔；便于安装表带；
6. 露出充电指示灯和照明灯；
7. 超薄机壳，厚度13mm。

​	**上美图~**

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Thin_cover_AD.3.jpg?raw=true" style="zoom:50%;" />

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Thin_cover_AD.4.jpg?raw=true" style="zoom:50%;" />

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Thin_cover_AD.2.jpg?raw=true" style="zoom:50%;" />

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Thin_cover_AD.7.jpg?raw=true" style="zoom:50%;" />

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Thin_cover_AD.15.jpg?raw=true" style="zoom:50%;" />

<img src="https://github.com/beamworld/iWatch-Bilibili-TV-cover/blob/master/output/render/iWatch_Thin_cover_AD.13.jpg?raw=true" style="zoom:50%;" />

## 更新日志

`2020.08.18`

- [x] 测量并绘制iWatch。
- [x] 绘制元器件。
- [x] 组装渲染。
- [x] 获得CXC发来的AD导出STEP。

`2020.08.19`

- [x] 使用STEP重绘板型。
- [x] 组装渲染。
- [x] 绘制part1，part2，part3。
- [x] 修复屏幕露白边问题。
- [x] 修复孔位不对齐问题。
- [x] 修复iWatch-main-board和iWatch-screen-board同时打开会导致板型重载问题。
- [x] 后盖加入Bilibili标识。
- [x] 螺丝改为沉孔设计。
- [x] 整体加厚以保证安全。
- [x] 四边改为等宽增加美观。
- [x] 加入小电视美腿。
- [x] 增大MicroUSB开孔。
- [x] Keyshot渲染出图。
- [x] 加深按键开槽，解决按键太紧问题。
- [x] 加长电视腿，期望解决站不住问题。
- [x] 增大螺丝孔以抵消PLA的热膨胀。
- [x] 加厚前面板，以解决面板太薄露出黑色阴影。

`2020.08.20`

- [x] 增大后盖螺丝孔至2.6以适配更多打印机。
- [x] 新增手戴超薄机壳。

`2020.08.21`

- [x] 加深按键孔。
- [x] 增长按键。
- [x] 内部加入上下倒角，修复因太薄打印出现断开问题。



## Bilibili-cover 3D打印使用方法

### 第一步：

​	直接使用切片软件将[STL模型](https://github.com/beamworld/iWatch-Bilibili-TV-cover/tree/master/output/stl)切片为Gcode，然后再3D打印机上打印即可。需要打印的文件和数量如下。

|        模型名称        | 打印数量 |   用途   |
| :--------------------: | :------: | :------: |
|   Bilibili_part1.STL   |    1     |  主外壳  |
| Bilibili_part2_cap.STL |    3     | 三个按键 |
|   Bilibili_part3.STL   |    1     |   后盖   |

**注意：1.Bilibili_part1.STL小电视天线部分需要打印支撑，否者你会获得一个烂电视或者破盒子。**

​			**2.打印时不要打印任何类型的平台附着，会很很难刮。**



### 第二步：

​	采购螺丝`M2x6盘头十字`四个用于安装后盖。或者你能借到，或者你能把什么拆了都行。



### 第三步：

1. 先把三个按键放到电视上对应孔中。
2. 放入iWatch。
3. 垫上一款减震棉在后盖和电池之间，减震棉你可以在你iWatch的快递盒子里找到，或者你再拆点什么。
4. 拧上4颗螺丝，拧的时候慢慢来，一开始可能不好进入，多蹭蹭~。（螺丝孔使用的是公差配合设计，所以不要整天把螺丝拆下来拧上去，会越来越松！）
5. 享受你的小电视吧。

**#有时间的话会搞一个安装教程----------------------------------------------------明年。**



## 工程指引

**#有时间的话会搞----------------------------------------------------明年。**



## Thin-cover 3D打印使用方法

### 第一步：

​	直接使用切片软件将[STL模型](https://github.com/beamworld/iWatch-Bilibili-TV-cover/tree/master/output/stl)切片为Gcode，然后再3D打印机上打印即可。需要打印的文件和数量如下。

|         模型名称         | 打印数量 |   用途   |
| :----------------------: | :------: | :------: |
|   Thin_cover_part1.STL   |    1     |  主外壳  |
| Thin_cover_part2_cap.STL |    3     | 三个按键 |
|   Thin_cover_part3.STL   |    1     |   后盖   |

**注意：1.打印时不要打印任何类型的平台附着，会很很难刮。**



### 第二步：

​	采购螺丝`M1.2x3盘头十字`四个用于安装后盖。或者你能借到，或者你能把什么拆了都行。



### 第三步：

1. 先把三个按键放到机壳上对应孔中。
2. 放入iWatch。
3. 垫上一款减震棉在后盖和电池之间，减震棉你可以在你iWatch的快递盒子里找到，或者你再拆点什么。
4. 拧上4颗螺丝，拧的时候慢慢来，一开始可能不好进入，多蹭蹭~。（螺丝孔使用的是公差配合设计，所以不要整天把螺丝拆下来拧上去，会越来越松！）
5. 像平常一样安装表带。
6. 享受你的新表壳吧吧。

**#有时间的话会搞一个安装教程----------------------------------------------------明年。**



## 机械开发注意

1. PCB模型各边不是垂直，不确定是绘制PCB时就是如此还是后期导出所致。
2. 由STEP导出的模型转换为sldasm后，iWatch-main-board和iWatch-screen-board同时打开会导致板型重载为先打开的一个，不确定导致问题的原因，但通过导出sldpart解决。



## 友情链接

暂无其他相关开源

**#有时间的话会搞一个Bilibili相关固件给iWatch------------------------------------------明年。**




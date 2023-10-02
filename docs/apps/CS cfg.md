---
article: false
title: CS cfg代码
icon: list
order: 6
---

## CS config(.cfg)文件内容记录

### 准星代码

一个查询代码含义的网站：https://totalcsgo.com/commands

```
cl_crosshair_drawoutline 0; // 准星外围的边线 （0 不显示）

cl_crosshairalpha 255; // 准星透明度 （255 不透明 0 全透）

// cl_crosshaircolor 1; // 我在游戏设置界面没有找到，注释掉用下面的RGB代替
// 0 红 1 绿 2 黄 3 深蓝 4 浅蓝色(青色)

cl_crosshaircolor_b 255; // 蓝色的色值（0-255）

cl_crosshaircolor_g 0; // 绿色的色值（0-255）

cl_crosshaircolor_r 0; // 红色的色值 （0-255）

cl_crosshairdot 0; // 中心点显示（0 不显示 1 显示）

cl_crosshairgap -3; // 准星之间的空隙大小

cl_crosshairsize 2; // 准星长度

cl_crosshairstyle 4; // 准星类型 4是经典静态

// 0 - 默认的 CS:GO 动态十字准线
// 1 - 默认十字准线的静态变体
// 2 - 经典静态十字准线，两侧各有一个动态圆点
// 3 - 经典动态十字准线
// 4 - 经典静态十字准线
// 5 - 经典静态和动态十字准线

cl_crosshairthickness 0; // 准星粗细

cl_crosshair_sniper_width 1; // 此命令设置使用狙击步枪瞄准镜时十字准线宽度的宽度（以像素为单位）。
```


## Slik

base building CSS UI library

Slik 是我和同事 [YiJun](https://github.com/DemonCloud) 在业余时间里编写维护的css项目，它提供最基础的css组件样式，可以方便配合Vue，React, [Ax](https://github.com/DemonCloud/Ax)来编写不同的UI组件。其中的设计理念是最大程度上减少JS的编写，让CSS来自动标志状态的改变。Slik已经被应用在商品库管理系统中，并且集成编写了一套 Vue + [Ax](https://github.com/DemonCloud/Ax) + jQuery(Utils Base Creator) 的组件。

Slik全部采用Less编写，**不过, Less模块化, 组件化方案不开源, 只提供一个压缩打包文件**

## 预览

![Preview](http://7j1zwt.com1.z0.glb.clouddn.com/Slik%20Preview.png)

## 组件GIF演示图

**注意！ 这是在完全没有产品和设计的情况下，由我和yijun共同讨论得出来的组件交互方式**
**这里展示的组件均由 Vue + Ax + Slik 编写而成**

select 组件

![select](http://7j1zwt.com1.z0.glb.clouddn.com/Untitled.gif)

cascader 级联

![cascader](http://7j1zwt.com1.z0.glb.clouddn.com/Untitled1.gif)

transfer 匹配搜索

![transfer](http://7j1zwt.com1.z0.glb.clouddn.com/Untitled2.gif)

switch 开关

![switch](http://7j1zwt.com1.z0.glb.clouddn.com/Untitled4.gif)

checkbox 复选框

![checkbox](http://7j1zwt.com1.z0.glb.clouddn.com/Untitled5.gif)

radio 单选

![radio](http://7j1zwt.com1.z0.glb.clouddn.com/Untitled6.gif)


**组件之间无关联，但是点击非自身时其他外置组件也会关闭**

![img](http://7j1zwt.com1.z0.glb.clouddn.com/Untitled3.gif)


# 50projects10days
10天完成50个前端基础的练手项目

原项目地址：https://github.com/bradtraversy/50projects50days

[toc]

## Scroll Animation

### html

1. 绘制标题以及各个盒子

### Script

1. 为 windows 添加scroll监听事件，监听滚动事件
2. 通过 windows.innerHeight 获取窗口高度，并且计算出应该呈现出来的box的高度
3. 遍历各个box，通过getBoundingClientRect()获取box与顶部的高度，并对需要呈现的box添加show class

### CSS

1. 对于每个box默认，transform: translateX进行位移
2. 并且通过伪类nth-of-type(even)实现奇偶不同方向位移
3. .show类 再覆盖掉默认位移属性

## Split Landing Page

### CSS

1. :root声明全局变量
2. 通过伪类::before 添加上一个图层能够使得背景更加好看
3. @media 媒体响应

### Script

1. 为左右两边添加hover监听事件，当触发监听事件时，为两边添加新的class

## Form Wave

### Html

1. 在input的最后添加上required

### Script

1. 通过JS操作将label的每一个字母转换为span，并且复制上transition-delay实现更好的效果

### CSS

1. 伪类控制动画

## Sound Board

### Html

1. audio标签实现音乐播放，并且有一些控制播放的接口

## faq-collapse

### CSS

1. font绘制图片，以及伪类绘制
2. 通过display实现一种collapse

## Random Choice Picker

### JS

1. 通过JS监听键盘事件，实现标签添加
2. 通过定时器实现随机选择

## Animate Navigation

### CSS

1. linear-gradient，线性插值实现渐变背景色
2. 

## Drink Water

### JS

1. 通过JS进行点击事件的控制，通过JS从而控制class从而通过CSS切换状态

### CSS

1. 常规通过transition: 进行动画控制

## Movie App

### JS

1. fetch拉取数据
2. 通过后端封装API进行搜索

### CSS

1. 当没有hover属性通过position让元素消失于div中，通过:hover transition

## Background Slider

### CSS

1. ::before 伪类实现蒙版效果

## Theme Clock

### JS

1. 定时器， date对象获取时间

### CSS

1. rotate属性实现旋转
2. border-radius旋转

## Button Ripple Effect

### HTML

1. 通过在button下添加一个circle实现效果

### JS

1. click通过点击位置更新circle位置

### CSS

1. 通过circle的动画实现波动效果

## Drag N Drop

### CSS

1. border-style: dashed 将边框设置为虚线效果

## Drawing App

### CSS

1. flex中，margin-left: auto可以实现居于最右

### JS

1. 通过canvas.getContext方法获取画布对象，之后使用画布API进行绘制。

## Kinetic Loader

### CSS

1. 新的绘制三角形的方法，border四边透明，然后控制border-bottom底边设置颜色绘制
2. animation 设置动画， infinite动画无尽播放

## Position Navbar

### HTML

1. 语义化标签

### CSS

1. 通过fixed实现sticky效果

## Double Vertical Slider

### JS

1. JS通过序列设置div的transform

### CSS

1. 通过CSS实现div的transition

## Toast Notification

### JS

1. 通过监听点击事件，点击后生成div实例。
2. 并且通过setTimeout定时销毁已经声明的实例

## Hoverboard

### JS

1. 添加Mouseenter与 Mouseout的事件监听

### CSS

1. box-shadow: x偏移量 y偏移量 阴影半径 扩散半径 颜色
2. display的换行新方式，指定父组件的max-width，并且display设置为flex，子组件只需要指定宽度即可
   不用进行flex的设置

## Pokedex

一种效果不错的卡片展示方式

### CSS

1. linear-gradient()

## Password Strength Background

### CSS

1. filter设置滤镜

## Verify Your Account

### JS

1. 通过focus()函数使得下一个输入框被激活

### CSS

1. 在输入框为输入、focus以及有输入值后的情况下分别设置不同的css，使得用户体验更好

## Live User Filter

### JS

1. 实现根据用户输入内容进行过滤

### CSS

1. 通过为元素添加class进行过滤，display:none，不会进行渲染（opacity:0, visibility: hidden都会渲染出来只是不会显示）

## Custom Range Slider

### JS

1. JS计算label的位置，并且进行更新
2. 有用的API：nextElementSibling\getComputedStyle(Dom对象).getPropertyValue(CSS属性名)

### CSS

1. 针对不同浏览器内核的处理方式

## Netflix Mobile Navigation

### HTML

1. 通过div堆叠的方式实现一个非常好的展示效果，很有层次感

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

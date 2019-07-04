---
layout: page
title: CSS3 弹性盒子(Flex Box)
categories:
     - 学习笔记
---

## 弹性盒子是 CSS3 的一种新的布局模式。

## CSS3 弹性盒（ Flexible Box 或 flexbox），是一种当页面需要适应不同的屏幕大小以及设备类型时确保元素拥有恰当的行为的布局方式。引入弹性盒布局模型的目的是提供一种更加有效的方式来对一个容器中的子元素进行排列、对齐和分配空白空间。

### CSS3 弹性盒子内容
### 弹性盒子由弹性容器(Flex container)和弹性子元素(Flex item)组成。

- 我们来看下具体的代码

```
<body>
<style> 
.flex-container {
    display: -webkit-flex;
    display: flex;
    width: 400px;
    height: 250px;
    background-color: black;
}

.flex-item {
    background-color: blue;
    width: 100px;
    height: 100px;
    margin: 10px;
}
</style>

<div class="flex-container">
  <div class="flex-item">flex item A</div>
  <div class="flex-item">flex item B</div>
  <div class="flex-item">flex item C</div>  
</div>

</body>
```

- 具体效果如下：

<body>
<style> 
	
.flex-container {
    display: -webkit-flex;
    display: flex;
    width: 400px;
    height: 250px;
    background-color: black;
}

.flex-item {
    background-color: blue;
    width: 100px;
    height: 100px;
    margin: 10px;
}
</style>

<div class="flex-container">
<div class="flex-item">flex item A</div>
<div class="flex-item">flex item B</div>
<div class="flex-item">flex item C</div>  
</div>

</body>

#### 其中的“flex-container”即最外面的黑色框，而“flex-item”就是黑色框中间的方块。
#### 所以要调整“background-color”“width”“height”要在相应的位置修改。

### 下面来做一下别的调整。

<body>
<style> 
	
	
.flex-container2 {
    display: -webkit-flex;
    display: flex;
    width: 200px;
    height: 250px;
    background-color: black;
}

.flex-item2 {
    background-color: blue;
    width: 100px;
    height: 100px;
    margin: 10px;
}
</style>

<div class="flex-container2">
  <div class="flex-item2">flex item A</div>
  <div class="flex-item2">flex item B</div>
  <div class="flex-item2">flex item C</div>  
</div>


</body>

-修改的代码为：
```
.flex-container2 {width: 200px;}
```

- 之所以修改成“flex-container2”是为了区别于前一个“flex-container”
- 当我将“width: 400px;” 修改为 “:width 200px;” 后，可以看到“flex-item”的宽变小了，但是“flex-itemA”“flex-itemB”“flex-itemC”之间的距离却没有变，这就是弹性盒子的一个特点。
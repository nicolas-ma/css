# css指南

## 基础引导

### 三种加载方式

````javascript
1. <link rel="stylesheet" type="text/css" href="mystyle.css">
2. <style> </style>
3. 用不到
````


### background

css background properties

**background**

> background-color: light blue;

**background-image**

> background-image: url("paper.gif")

**background-repeat**

> background-image: url("gradient_bg.png");
>
>  background-repeat: repeat-x;
>
>  background-repeat: repeat-y;
>
>  background-repeat: no-repeat;

**background-position**

> background-position: right top;
>
> 标准坐标系：x:左正 y:上正

**固定图形**
>  background-attachment: fixed;

**缩写**
>  background: #ffffff url("img_tree.png") no-repeat right top;

### Border
**border-style**
> solid
>
> dotted
>
> dashed

**border-width**
> border-width:5px;

**border-color
> border-color: red;

**分离border属性**
>border-top-style: dotted;
>
>border-right-style: solid;
>
>border-bottom-style: dotted;
>
>border-left-style: solid;

**border属性简写**
> border: 5px solid red;

**border-radius**
>border-radius: 5px;



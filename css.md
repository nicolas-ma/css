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

### Margin

**分离属性**

> - `margin-top`
> - `margin-right`
> - `margin-bottom`
> - `margin-left`

**元素设置在容器中居中**（一定要设置width）

> div {
> ​    **width: 300px;**
> ​    margin: auto;
> ​    border: 1px solid red;
> }

**继承父元素的margin属性inherit**

> div.container {
> ​    border: 1px solid red;
> ​    margin-left: 100px;
> }
>
> p.one {
> ​    margin-left: inherit;
> }

**margin距离重叠**

- 上下距离选最大的
- 左右距离直接叠加


# css指南

## 基础引导

### 三种加载方式

````javascript
1. <link rel="stylesheet" type="text/css" href="mystyle.css">
2. <style> </style>
3. 用不到
http://www.xixiuqiangwei.com/caocao747/7/1703/2324332.html
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


### padding

**分离属性**

>- `padding-top`
>- `padding-right`
>- `padding-bottom`
>- `padding-left`

盒子的宽高为width+ padding，height+ padding（加上padding的属性）



```
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys BA300B7755AFCFAE

sudo add-apt-repository 'deb https://typora.io ./linux/'
sudo apt-get update

sudo apt-get install typora
```

### text

**color**

**text-align**

**text-decoration**

````
text-decoration: none;
text-decoration: overline;上
text-decoration: line-through;中
text-decoration: underline;下
````

**text-transform**字体变形

````
 text-transform: uppercase;全大写
 text-transform: lowercase;全小写
 text-transform: capitalize;首字母大写
````

**text-indent**第一行间距

````
text-indent: 50px;
     In my younger and more vulnerable years my father gave me some advice that I've been turning over in my mind ever since. 'Whenever you feel like criticizing anyone,' he told me, 'just remember that all the people in this world haven't had the advantages that you've had.'
````

**letter-spacing**  字的距离

````
letter-spacing: 3px;
````

**line-height**行直接的间距

````
line-height: 0.8;
````

**word-spacing**字间距

**text-shadow**字体的阴影

````
text-shadow: 3px 2px red;
````

### Fonts

````
 font-family: "Times New Roman", Times, serif;
````

**font-style**

````
 font-style: normal;
 font-style: italic;
 font-style: oblique;
}
````

**font-size**

**font-weight**

````
font-weight: normal;
font-weight: bold;
````

### icons

````
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
````

### Links

```
a:link{}
a:visited{}
a:hover
a:active
```

### Lists

```
ul
  li
  li
//
ol有序
  li
  li
```



```
 list-style-type: circle/square/upper-roman/lower-alpha/none;
 list-style-image: url('sqpurple.gif');
  list-style-position: inside/outside;
```

```
remove默认配置
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}
```


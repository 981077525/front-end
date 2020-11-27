# CSS背景 background

1. 背景颜色（background - color）

   > 语法：

   ​	`   {background-color:属性值;}`

   > 颜色值：

 - 预定义

   > 如 red、blue、green、yellow等

 - 16进制颜色代码

   > \#rrggbb  由三原色组合而成的颜色。

- RGB代码

  > 如rgb(255,0,0)或者rgb(100%,10%,10%)

 2.背景图片(background - image)

` {		background - image:url(图片的地址);	}`

 3.背景图片平铺 (background - repeat)

| 属性值    | 描述         |
| --------- | ------------ |
| repeat    | 默认值，平铺 |
| no-repeat | 不平铺       |
| repeat-x  | 横向平铺     |
| repeat-y  | 纵向平铺     |

>  语法:

`{	background - repeat:属性值;}`

 4.背景图片定位(background-position)

| 参数     | 值                                               |
| -------- | ------------------------------------------------ |
| length   | 百分数\|由浮点数和单位标识符组成的长度值，如10px |
| position | 方位名词：top、left、right、bottom、center       |

 5.背景附着(background - attachment)

> 语法：

`{	background-attachment:属性值;	}`

| 参数   | 作用                                             |
| ------ | ------------------------------------------------ |
| scroll | 背景图像是随对象内容滚动，相对于用户界面是滚动的 |
| fixed  | 背景图像不随对象内容滚动，相对于用户界面是固定的 |

 6.背景透明 - css3  (background:rgba(0,0,0,0.3))

> 语法：

` { 	background:rgba(0,0,0,0.3)	}`

r :red(红)

g:green(绿色)

b:blue(蓝色)

a:alpha(透明的) ---->a就是alpha也就是透明的颜色一般情况下取0-1的值，如0.3，但通常情况下会省略这里的0直接写.3
```
• css通过样式表与HTML文件进行关联，主要分为内联和外联两种：
	• 内联：内联就是把样式直接写进内容，如：
	• <p style="color: sienna; margin-left: 20px">
This is a paragraph
</p>
	• 内联样式表：位于HTML文档的<head>中，使用<style>标签
	• 外联样式表：是单独的css文件，使用<link>标签，如：
	<link rel="stylesheet" type="text/css" href="mystyle.css" />



选择器
css语法由选择器和声明组成。如：
	h1{color:red;font-size:14px;}
	此处的h1就是选择器；声明由属性和值组成，若值为若干单词时，要加引号；声明之间用分号隔开
可以对选择器使用分组，在一个分组中的选择器，分享相同的声明。选择器用逗号分开。如：
	h1,h2,h3,h4,h5,h6 {
  color: green;
  }
	此时h1,h2,h3,h4,h5,h6共享颜色为绿色的声明
派生选择器：通过依据元素在其位置的上下文关系来定义样式。如：
	li strong {
    font-style: italic;
    font-weight: normal;
  }

	<p><strong>我是粗体字，不是斜体字，因为我不在列表当中，所以这个规则对我不起作用</strong></p>
	<ol>
<li><strong>我是斜体字。这是因为 strong 元素位于 li 元素内。</strong></li>
<li>我是正常的字体。</li>
</ol>
id选择器：可以为标有特定id的元素指定样式，使用#来定义。如：
	#red{color:red;}
	就是定义id为red的元素，颜色为红色
	id选择器通常与派生选择器组合使用
类选择器：与id选择器类似，使用.来定义。如：
	.center {text-align: center}
	就是定义center类的文字全部中心对齐
属性选择器：可以为拥有指定属性的HTML设置样式。如：
	[title]
{
color:red;
}
	是将带有title属性的所有元素设置为红色
	[title=W3School]
{
border:5px solid blue;
}
	是将title属性中，设置值为W3School的元素样式
	[title~=hello]
	{
	color:red;
	}
	</style>
	</head>
	设置title属性中，值中含有hello样式的元素样式
后代选择器
	后代选择器又称为包含选择器
	具备指定条件的元素才能执行规则
子元素选择器
	子元素选择器（Child selectors）只能选择作为某元素子元素的元素。
	范围比后代选择器更小
相邻兄弟元素
	可选择紧接在另一元素后的元素，且二者有相同父元素


背景
背景色使用background-color设置，如：p {background-color: gray;}

背景图像使用background-image设置。如：body {background-image: url(/i/eg_bg_04.gif);}
背景图像平铺使用background-repeat，如：
body
  {
  background-image: url(/i/eg_bg_03.gif);
  background-repeat: repeat-y;
  }
就是让这个背景图在Y轴方向平铺

背景定位是使用background-position设置图像在背景中的位置。如：
body
  {
    background-image:url('/i/eg_bg_03.gif');
    background-repeat:no-repeat;
    background-position:center;
  }
是设置背景图片居中放置



文本
缩进文本：
使用 text-indent 属性，所有元素的第一行都可以缩进一个给定的长度，甚至该长度可以是负值。如：
	p {text-indent: 5em;}
	是设置所有段落首行缩进5em，这个值也可以设置为负值，百分制

水平对齐：
text-align 是一个基本的属性，它会影响一个元素中的文本行互相之间的对齐方式。值 left、right 和 center 会导致元素中的文本分别左对齐、右对齐和居中，justify会让两端都放在父元素的内边界上，然后，调整单词和字母的间隔

字间隔：
word-spacing 属性可以改变字（单词）之间的标准间隔。

字母间隔
letter-spacing 属性与 word-spacing 的区别在于，字母间隔修改的是字符或字母之间的间隔。

字符转换
text-transform 属性处理文本的大小写。这个属性有 4 个值：
	• none              不做改动
	• uppercase   转化成全大写
	• lowercase    转化成全小写
	• capitalize      每个首字母大写




指定字体：在font-family:后设置字体名


字体风格font-style用于设置斜体文本
• normal - 文本正常显示
• italic - 文本斜体显示
• oblique - 文本倾斜显示文本装饰


text-decoration 用于装饰文字，该属性有 5 个值：
• none                关掉装饰
• underline       添加下划线
• overline         添加上划线
• line-through   中部贯彻线
• blink                  让文本闪烁

处理空白符
white-space 属性会影响到用户代理对源文档中的空格、换行和 tab 字符的处理。
使用white-space: normal;会将空格合并
字体
使用 font-family 属性 定义文本的字体系列。
设置通用字体font-family: sans-serif;






字体变形font-variant设置小型大写字母。
font-variant:small-caps;

font-weight 属性设置文本的粗细。
normal         默认值
bold             设置为粗体
整百数值   设置粗细等级


字体大小font-size设置文本的大小。




链接

链接有四种状态：
a:link    未被访问
a:visited  已访问
a:hover  鼠标徘徊
a:active   被点击时




列表
修改列表的标志类型，如使用list-style-type:square;就是将标志设置成方块

将标志设置成图像，使用list-style-image:url(图片url)

也可直接简写成list-style


表格
设置表格边框使用border属性。如：
table, th, td
  {
  border: 1px solid blue;
  }

使用border-collapse将边框折叠为单一边框

表格宽度和高度使用width和height设置。
table{width:100%}
th{height:50px}
就是将表格宽度设置为100%，将th元素高度设置为50px

表格文本对齐
text-align属性设置水平对齐方式
vertical-align属性设置垂直对齐方式

表格内边距
使用padding属性

表格颜色
table, td, th
  {
  border:1px solid green;
  }
th
  {
  background-color:green;
  color:white;
  }
是设置表格的边框颜色和背景颜色文字颜色



轮廓
是绘制于元素周围的一条线，位于边框边缘的外围，可起到突出元素的作用。
如：
p.two
{
border:red solid thin;
outline-style:dotted;
outline-width:3px;
}
就是设置类名为two的p标签，他的边框为红色细实线，轮廓为点状线，宽度3px。



框模型


内边距
内边距由padding属性控制

边框
边框是围绕元素内容和内边距的一条或多条线。
由border属性设置，可设置样式、宽度和颜色

外边距
由margin属性设置
外边距是内容和内容之间的距离，所以和邻近内容的外边框是合并的


定位
定位（positioning）属性允许你对元素进行定位。
通过pisition属性，我们可以选择4种不同类型的定位，这会影响元素框生成的方式
• static：元素框正常生成。
• relative：元素框偏移某个距离。元素人保持其未定位前的形状，原版所占的空间仍保留。
• absolute：元素框从文档流完全删除，并相对于其包含块定位。
• fixed：元素框的表现类似于将 position 设置为 absolute，不过其包含块是视窗本身。


相对定位relative
如果对一个元素进行相对定位，他讲出现在他所在的位置上。

绝对定位absolute ？
绝对定位是元素的位置与文档流无关，因此不占空间。

浮动float
浮动的框可以向左或向右移动，知道他外边用碰到包含框或另一个浮动看的边缘为止。
因为它是浮动的，所以，高度比其他元素要高

clear属性？？


水平对齐

使用margin属性来水平对齐
可通过将左右外边距设置为"auto"，来对齐块元素。

使用position属性进行左和右对齐？
对齐元素的方法之一是使用绝对定位

使用float属性来进行左和右对齐

尺寸
• height           设置元素的高度
• line-height    设置行高
• max-height   设置元素的最大高度
• max-width    设置元素的最大宽度
• min-height    设置元素的最小高度
• min-width     设置元素的最小宽度
• width            设置元素的宽度




分类属性
？
clear 设置一个元素的侧面是否允许其他的浮动元素。
cursor 规定当指向某元素之上时显示的指针类型。
display 设置是否及如何显示元素。
float 定义元素在哪个方向浮动。
position 把元素放置到一个静态的、相对的、绝对的、或固定的位置中。
visibility 设置元素是否可见或不可见。



图片透明
使用opacity属性


媒介类型
all 用于所有的媒介设备。
aural 用于语音和音频合成器。
braille 用于盲人用点字法触觉回馈设备。
embossed 用于分页的盲人用点字法打印机。
handheld 用于小的手持的设备。
print 用于打印机。
projection 用于方案展示，比如幻灯片。
screen 用于电脑显示器。
tty 用于使用固定密度字母栅格的媒介，比如电传打字机和终端。
tv 用于电视机类型的设备。




css3边框
• border-radius 圆角边框
div
{
border:2px solid;
border-radius:25px;
}
就是设置div的边框为2px宽的实线，圆角值为25px
• box-shadow 边框阴影
div
{
box-shadow: 10px 10px 5px #888888;
}
就是设置阴影的水平垂直偏移距离，阴影模糊程度，和阴影颜色
• border-image 边框图片
div
{
border-image:url(border.png) 30 30 round;
}
设置边框用此url做图片，设置偏移度和宽度，并且是重复铺满


背景
• background-size
缩放背景图片的尺寸
• background-origin
规定背景图片的定位区域，如：
div
{
background:url(bg_flower.gif);
background-repeat:no-repeat;
background-size:100% 100%;
-webkit-background-origin:content-box; /* Safari */
background-origin:content-box;
}
就是规定背景图片是放在content-box里的
 
 
css3文本效果
• text-shadow
添加文字的阴影效果，能够规定水平阴影、垂直阴影、模糊距离，以及阴影的颜色
• word-wrap
如word-wrap:break-word;强制对长单词进行拆分，强制换行



css3字体

使用服务端字体
<style> 
@font-face
{
font-family: 字体名（可自定）;
src: local(“本地字体名“），
        url(‘字体url’),
}

div
{
font-family:字体名（可自定）;
}
</style>


设置粗体字体
font-weight:bold;


2d转换
2d转换方法
translate()  移动目标。   
rotate()  旋转目标。 单位用deg
scale()  缩放目标。  
skew()  旋转目标。
matrix() 将前面的方法组合在一起使用，需要六个参数，包含数学函数，允许您：旋转、缩放、移动以及倾斜元素。


3d转换方法
rotateX()  
rotateY()


过渡
使用 transition 属性。如：
div
{
width:100px;
height:100px;
background:yellow;
transition:width 2s;
}

div:hover
{
width:300px;
}
就是应用于宽度属性的过渡效果，时长为 2 秒



css3动画
使用@keyframe定义动画名，使用animation动画属性来设置动画，如：
<!DOCTYPE html>
<html>
<head>
<style>
div
{
width:100px;
height:100px;
background:red;
animation:myfirst 5s;
}

@keyframes myfirst
{
from {background:red;}
to {background:yellow;}
}
</style>
</head>
<body>

<div></div>

</body>
</html>
就是设定动画名为myfirst，从红色变成黄色需要五秒



分列

column-count:列数                         把文本分隔为指定列数

column-gap:距离                          设置列之间的间隔

column-rule:宽度 样式 颜色        设置列之间的宽度，样式和颜色规则



```

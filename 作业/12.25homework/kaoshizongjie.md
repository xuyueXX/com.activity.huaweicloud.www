一、单选题

1.关于HTML语义化，以下哪个说法是正确的（D）？
 
A: 语义化的HTML有利于机器的阅读，如PDA手持设备、搜索引擎爬虫；但不利于人的阅读
 
B: Table 属于过时的标签，遇到数据列表时，需尽量使用 div 来模拟表格
 
C: 语义化是HTML5带来的新概念，此前版本的HTML无法做到语义化
 
D: header、article、address都属于语义化明确的标签

2.制作移动端页面, 以下哪种布局方式不合适(C )
 
A: A.响应式Responsive（使用@media媒体查询，给不同尺寸和介质的设备切换不同的样式）
 
B: B.伸缩Flexbox（使用CSS3 Flex系列属性进行相对布局）
 
C: C.固定Fixed（使用px和pt这样的绝对单位进行固定布局）
 
D: D.流动Fluid（使用%百分比进行相对布局）

3.下面选项中关于box-sizing:border-box的计算正确的是哪项（D）？
 
A: 盒子实际宽度 = padding + content
 
B: 盒子实际宽度 = padding + margin
 
C: 盒子实际宽度 = content + padding + border +margin
 
D: 盒子实际宽度 = content + padding + border

4.如果想设置下列” The first paragraph”标签的背景色为红色，正确的是（B）
<h1>This is a heading</h1>
<p>The first paragraph.</p>
<p>The second paragraph.</p>
<p>The third paragraph.</p>
<p>The fourth paragraph.</p>
 
A: p:nth-child(1){background:red};
 
B: p:nth-child(2){background:red};
 
C: p:nth-last-child(n){background:red};
 
D: p:nth-child(2n){background:red};

5.使用CSS的flexbox布局，不能实现以下哪一个效果（D）？
 
A: 多列布局，随容器宽度等宽弹性伸缩
 
B: 多列布局，平均分配宽度
 
C: 多列布局，左列宽度像素数确定，中、右列随容器宽度等宽弹性伸缩
 
D: 多列布局， 不占有位置

6.以下位于<head>间的代码片段是做什么用的 <meta name="viewport" content="width=device-width, initial-scale=1"> （D）？
 
A: 使得页面编码合乎移动端要求
 
B: 表示支持响应式设计
 
C: 添加后才能正常的缩放
 
D: 表示针对移动端进行适当的适配

7.以下哪个不是伪类选择器（C）
 
A: E:first-child;
 
B: E:last-child;
 
C: E:before;
 
D: E:nth-child(n);

8.伪元素选择器before&after必须包含的属性是（C）
 
A: position;
 
B: display;
 
C: content;
 
D: background;

9.CSS3中设置边框阴影的属性是（A）
 
A: box-shadow;
 
B: text-shadaow;
 
C: text-align;
 
D: text-direction;

10.在调用动画中animation-delay属性的作用是（B）
 
A:  设置动画动画执行速度;
 
B:  设置动画延迟;
 
C:  设置动画名称;
 
D:  设置动画执行次数;

11.指定一个盒子为伸缩盒子需要设置的属性是（C）
 
A: display:block;
 
B: display:none;
 
C: display:flex;
 
D: display:inline;

12.sass中 变量的命令使用什么符号开头（A）
 
A: $;
 
B: @;
 
C: &;
 
D: *;

13.一个a标签，想实现一个圆，那么以下样式书写正确的是（C）
 
A: a{display：block;width:20px;height:20px;border:5px solid #f00;border-radius:10px;}
 
B: a{display：block;width:20px;height:20px;border:5px solid #f00;border-radius:5px;}
 
C: a{display：block;width:20px;height:20px;border:5px solid #f00;border-radius:50%;
}
 
D: a{display：block;width:20px;height:20px;border:5px solid #f00;border-radius:14px;}

14.	下面关于背景样式，说法不正确的是（A）

 
A: 默认情况下， 背景图片是不平铺的
 
B: color设置的是文本颜色， background-color设置的是背景颜色
 
C: CSS Sprite技术是借助background-position属性来实现的
 
D: 我们可以使用”background-repeat:repeat-x”,来实现背景图片在x轴方向平铺

15.在移动端如果想要设置用户不可进行缩放，以下代码中正确的是哪一个？（D）
 
A: <meta name="viewport" content="width=device-width,initial-scale=1" >
 
B: <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=2.0" >
 
C: <meta name="viewport" content="width=device-width,initial-scale=1,minimum-scale=1.0" >
 
D: <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no" >
16.下面哪个单位，取决于html标签的font-size属性的值？（B）
 
A: em
 
B: rem
 
C: px
 
D: pt

17.关于定位，错误的是：（C）
 
A: z-index后面的数字越大在层叠样式中越居上，如：z-index:5在z-index:1上面
 
B: z-index数字后面不加单位，如：z-index:100;
 
C: 如果z-index的数值相同，先书写的在上面
 
D: 只有绝对定位，固定定位，相对定位，有此属性

18.移动端页面布局中,以下描述不正确的是:（C）
 
A:  父盒子设为Flex以后，子元素的float属性将失效。
 
B:  flex-direction属性决定主轴的方向（即项目的排列方向）。
 
C:  justify-content属性定义了项目在侧轴上的对齐方式。
 
D:  space-around：项目之间的间隔比项目与边框的间隔大一倍。

19.视口中, 能够控制最大缩放的属性是（D）
 
A: width;
 
B: user-scalable;
 
C: initial-scale;
 
D: maximun-scale;

20.关于伪元素的选项错误的是（B）？
 
A: ::before、::after是行内元素
 
B: 不使用content属性，也可以显示
 
C: 不可以使用JS控制
 
D: 最初伪元素的语法是使用“:”（一个冒号），在CSS3中伪元素使用“::”（两个冒号）


二 、多选题
下列哪些是CSS3的新特性【多选】（ABCDE）？
 
A: 3D变换
 
B: 渐变
 
C: 2D变换（平移，缩放，旋转）
 
D: 媒体查询(新增媒体属性比如min-width)
 
E: CSS动画

2.以下关于less的使用正确的是:（ABC）
 
A:  Less 是一门 CSS 预处理语言，它扩展了 CSS 语言，增加了变量、函数等特性，使 CSS 更易维护和扩展;
 
B:  如果需要直接引用写好的less文件, 只要在less样式表之前引入less.js文件即可;
 
C:  Less中可以直接进行数值运算;
 
D:  @import 的位置可随意放置;

3.以下媒体查询的描述说明正确的是【多选】（ABC）？
 
A: min-width：在pc端和移动端能正常的响应，效果一致
 
B: 如果是判断的是 min-width，那么范围区间应该从小到大写
 
C: 如果是判断的是 max-width，那么范围区间就应该从大到小写
 
D: 如果是判断的是 mid-width，那么范围区间就应该从中间位置写


4.rem与em的相关描述正确的是:（BCD）

 
A:  rem与em都是相对单位，我们使用它们的目的是为了适应各种手机屏幕;
 
B: rem和em都是是根据元素字体大小来进行计算的;
 
C: em是相对于父级元素的单位，会随父级元素的属性（font-size）变化而变化;
 
D:  rem是相对于根目录（HTML元素）的，所以它会随HTML元素的属性（font-size）变化而变化;


5.下面哪个媒体查询无法实现:（ABCD）
 
A:  @media screen and(max-width:500px){ };
 
B:  @media screenand (max-width:500px){ };
 
C:  @media screen and (max-width:500px;){ };
 
D:  @ media screen and (max-width:500px){ };


三、简答题
1.	css三种引入方式，举例说明？
1.	行内式
<div style="color: red;"></div>

2.	内嵌式
div{
color: red;
}

3.	外链式
<link rel="stylesheet" href="css样式文件路径">


2.	怎么让一个不定宽高的盒子在另一个盒子中水平垂直居中（写2种方式）

方式一margin：auto：
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    margin: auto;

方式二translate：
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);


方式三flex：
    /* 给父盒子添加 */
    display: flex;
    justify-content: center;
    align-items: center;


3.	精灵图的使用方法？
1.	定宽高，存放所需的精灵图
2.	添加background-image: url("精灵图路径"); 引入精灵图
3.	调整位置选择需要的精灵图：background-position: -x -y;
4.	如果需要再调整精灵图大小使用：background-size: ;


4.	em和rem的区别是什么？
1.	em相对的是当前元素文本字体大小计算，如没有则相对浏览器默认的font-size值计算
2.	rem相对的是根元素html的字体大小进行计算的

5.	CSS中 link 和@import 的区别是什么？
a. link属于HTML标签，而@import是CSS提供的，且只能加载 CSS
b. 页面被加载时，link会同时被加载，而@import引用的CSS会等到页面被加载完后再加载
c. @import只在IE5以上才能识别，而link是HTML标签，无兼容问题
d. link引入方式的权重 高于@import的权重


6.	rgba()和opacity的透明效果有什么不同？
a.	opacity作用于元素，以及元素内的所有内容的透明度，rgba()只作用于元素的颜色或其背景色。

b. 设置rgba透明的元素的子元素不会继承透明效果

7.	<img>标签上title属性与alt属性的区别是什么？
1.	title属性：鼠标移到图片上显示"标题内容"
2.	alt属性：当<img>加载不出来的时候，alt属性内容会替代<img>显示



8.	CSS元素的三种显示模式？
1.	行内元素：inline
2.	块元素：block
3.	行内块元素：inline-block


9.	行内元素有哪些？块级元素有哪些？行内块元素有哪些？
行内元素：
span、a、b (加粗)、strong、s (删除线)、del、i (斜体)、em、、、、、、、

块级元素：
h1~h6、p、div、ul、ol、li、、、、、、

行内块元素：
input、img、table、textarea、


10.	请至少写出5个H5的新标签？
 任意写5个就可以：
<header></header>    // 头部 
<nav></nav>          // 导航
<main></main>        // 主体
<aside></aside>      // 侧边
<footer></footer>    // 底部


11.	怎么定义动画？怎么使用动画？
定义：
@keyframes 动画名字 {
"定义需要的动画"
}
使用：
给需要的元素添加animation: 动画名 动画完成所需时间 动画速度 延迟、、、 

具体代码：
定义动画1：from、to动画
@keyframes 动画名 {
            from {
                开始状态;
            }
            to {
                结束状态
            }
        }
定义动画2：百分比动画
@keyframes 动画名 {
            0% {
                开始状态
            }
            ···
            50% {
                过程n状态
            }
            ···
            100% {
                结束状态
            }
        }
使用：
/* 规定的动画名 */
            animation-name: name;
            /* 动画所需时长 */
            animation-duration: 时间;
            /* 动画运动曲线 */
            animation-timing-function: linear;
            /* 动画延迟时间（多久后开始动画） */
            animation-delay: 时间;
            /* 动画播放次数 */
            animation-iteration-count: infinite;

连写：animation: 动画名 运动所需时长 ···;没有顺序要求，也可缺省书写，但是动画名和所需时长必写，当同时出现动画时长和动画延迟时左数第一个会被识别为时长


12.	说明CSS渐变有哪些？分别是什么？怎么使用？
线性渐变：linear-gradient: 方向 初始色 结束色
background-image: linear-gradient(to  渐变的最终方向, 初始颜色 最终颜色);

径向(圆形)渐变：radial-gradient: 主轴 次轴 at 原点x 原点y 初始色 结束色
* background-image: radial-gradient(圆心X 圆心Y at 渐变的X的起点 渐变的Y轴的起点, 渐变之的距离（可省略） 圆心中间的颜色, 扩散的颜色); */
Background-image: radial-gradient(50px 50px at center center, hotpink 0%, skyblue 50%);



13.	CSS选择器优先级从大到小排序？
!important(权重无穷大) > 行内样式 > ID选择器 > 类选择器 = 伪类选择器 > 标签选择器 >继承(子承父)或*(通配符)

 
14.	怎么用css实现多行文字超出显示为省略号？
 overflow: hidden;
 /* 文字末尾换行 */
 word-wrap: break-all;
 /* 文字溢出省略号 */
 text-overflow: hidden;
 /* 控制显示行数  你想要第几行出现省略号*/
  -webkit-line-clamp: 2;
/* 文字显示方式 默认为水平显示 */
  -webkit-box-orient: vertical;
 /* 盒子转弹性盒子 */
 display: -webkit-box;


15.	实现左边固定200px,右边自适应的方法（2种方式）
说明：这是其中的2种，你可以通过别的方式实现也算：
方式一flex法：
html代码
16.	  <div class="left"></div>
17.	  <div class="right"></div>

css代码
18.	    html,
19.	    body {
20.	      display: flex;
21.	      width: 100%;
22.	      height: 100%;
23.	      margin: 0;
24.	      padding: 0;
25.	    }
26.	
27.	    .left {
28.	      width: 200px;
29.	      height: 100%;
30.	      background-color: red;
31.	    }
32.	
33.	    .right {
34.	      flex: 1;
35.	      background-color: blue;
36.	    }

方式二浮动法：
Html代码
37.	  <div class="left"></div>
38.	  <div class="right"></div>

css代码
39.	    html,
40.	    body {
41.	      width: 100%;
42.	      height: 100%;
43.	      margin: 0;
44.	      padding: 0;
45.	      position: relative;
46.	    }
47.	
48.	    .left {
49.	      float: left;
50.	      width: 200px;
51.	      height: 100%;
52.	      background-color: red;
53.	    }
54.	
55.	    .right {
56.	      height: 100%;
57.	      /* 挤开左边盒子 */
58.	      margin-left: 200px;
59.	      background-color: blue;
60.	    }


16.实现左边固定200px,中间自适应，右边固定200px的方法(2种方式实现)？
方式一浮动法：
html代码：
61.	  <div class="left"></div>
62.	  <div class="right"></div>
63.	  <div class="center"></div>

css代码：
64.	  html,
65.	  body {
66.	    width: 100%;
67.	    height: 100px;
68.	    /* 重置样式 */
69.	    margin: 0;
70.	    padding: 0;
71.	  }
72.	
73.	  /* 左浮动 */
74.	  .left {
75.	    float: left;
76.	    width: 100px;
77.	    height: 100%;
78.	    background-color: red;
79.	  }
80.	
81.	  /* 中间自适应 */
82.	  .center {
83.	    height: 100%;
84.	    background-color: pink;
85.	    /* 挤开左右 */
86.	    margin-left: 100px;
87.	    margin-right: 100px;
88.	  }
89.	
90.	  /* 右浮动 */
91.	  .right {
92.	    float: right;
93.	    width: 100px;
94.	    height: 100%;
95.	    background-color: blue;
96.	  }
97.	

方式二定位法：
html代码：
98.	  <div class="left"></div>
99.	  <div class="center"></div>
100.	  <div class="right"></div>

css代码：
101.	  html,
102.	  body {
103.	position: relative;
104.	    width: 100%;
105.	    height: 100px;
106.	    /* 重置样式 */
107.	    margin: 0;
108.	    padding: 0;
109.	  }
110.	
111.	  /* 左定位 */
112.	  .left {
113.	    position: absolute;
114.	    top: 0;
115.	    left: 0;
116.	    width: 100px;
117.	    height: 100%;
118.	    background-color: red;
119.	  }
120.	
121.	  /* 中间自适应 */
122.	  .center {
123.	    height: 100%;
124.	    background-color: pink;
125.	    /* 挤开左右 */
126.	    margin-left: 100px;
127.	    margin-right: 100px;
128.	  }
129.	
130.	  /* 右定位 */
131.	  .right {
132.	    position: absolute;
133.	    top: 0;
134.	    right: 0;
135.	    width: 100px;
136.	    height: 100%;
137.	    background-color: blue;
138.	  }


方式三flex法：
html代码：
139.	  <div class="left"></div>
140.	  <div class="center"></div>
141.	  <div class="right"></div>


css代码
142.	  html,
143.	  body {
144.	    /* 伸缩盒子 */
145.	    display: flex;
146.	    width: 100%;
147.	    height: 100px;
148.	    /* 重置样式 */
149.	    margin: 0;
150.	    padding: 0;
151.	  }
152.	
153.	  .left {
154.	    width: 100px;
155.	    height: 100%;
156.	    background-color: red;
157.	  }
158.	
159.	  .center {
160.	    /* 剩余空间占比 */
161.	    flex: 1;
162.	    background-color: pink;
163.	  }
164.	
165.	  .right {
166.	    width: 100px;
167.	    height: 100%;
168.	    background-color: blue;
169.	  }


17.说你对Sass的理解，和一些常用的语法有什么？Sass和Less的有什么区别？
（找个题是开放性的，这个仅供参考，自己根据自己的理解去写，扩散思维）
理解：Sass是一门css预处理语言，扩展css语言，添加了变量，函数等特性，让css更容易维护和扩展。
常用语法：①嵌套 ②&  ③变量  ④混合器 ⑤继承、、
区别：1）在语法定义方面，比方说定义变量方面，Less通过@定义变量，Sass通过$定义变量，像混合器方面，Less是通过.minxin的方式定义，Sass是通过@minxin的方式
2）Sass支持条件语句，可以使用if{}else{},for{}循环等等，而Less不支持

18.CSS选择器有哪些？哪些样式可以继承？
选择器有：
①	标签选择器
②	类选择器
③	ID选择器
④	通配符选择器
⑤	后代选择器
⑥	子代选择器
⑦	并集选择器
⑧	伪类选择器
。。。等等
继承：
以font-、text-、line-开头的元素还有color元素等可以被继承（background-color不会被继承） 

易成龙提供拓展：https://www.cnblogs.com/thinkingthigh/p/9662404.html




19.css3的新属性有哪些？(举例说明5个，中英文都写)
下面的必须牢记5个

1. 圆角
border-radius	
2.阴影
1）文本阴影：text-shadow
2）盒子阴影：border-shadow
3.渐变
1）线性渐变：background-image: linear-gradient(方向,起始色,结束色);
2）圆形渐变：background-image: radial-gradient(主轴 次轴 at 圆点X 圆点Y, 起始色，结束色);
4.过渡
transition: ; 
5.2D转换
transform
6.转换原点
Transform-origin
7.3D变换
perspective
8.3D呈现
transform-style
9.动画
1）定义动画 @keyframes 动画名(identifier){ }
2）调用动画 animation
10.伸缩盒子（弹性盒子）
display: flex;
11.媒体查询
min-width、min-height、max-midth、max-height、、


20. 请列举6种表单元素？
表单元素有：
①	form（表单域）
②	input（表单控件）
③	button（按钮）
④	textarea（文本域）
⑤	select（下拉列表）
⑥	option（下拉列表选项）	
下面的供参考：
⑦	fieldset（表单线框）
⑧	legend（线框标题）
⑨	label（关联标签）

//  组合6个表单就可以，下面都是常用的,只要能写出6个就可以
<input type="text">        // 文本框
<input type="radio">       // 单选框
<input type="checkbox">    // 复选框
<input type="password">    //  密码框
<form action=""></form>    // 表单
<textarea  cols="" rows=""></textarea>   // 文本框
<select name="" id=""></select>     // 下拉框



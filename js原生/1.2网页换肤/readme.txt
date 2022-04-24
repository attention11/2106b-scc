个人思考的方向：
1，先处理各个元素正常情况下，对应的htlml结构和css样式
2，使用js处理的时候，参考第一节课“功能附加”的固定模式，即使用for循环控制待访问的功能部件，使用object.index=i和object.onclick function()来创建具体功能实现
---------------------------------------

------------------------------------------
遇到的问题：
【未解决】
不能直接在onload中重新设置一个默认样式，不然，切换其他样式时，这个默认样式的那妞
2，三个按钮的背景色一直不变：
3.书写格式的混乱以后需要注意
4,text-indent:-9999px;负值有什么用，为什么使用这么小的负值
5，没能理解为什么#skin所属列表要用到红绿黑三个字？？？
6，#skin li.current{!important}属性有无必要？？
7，关于overflow:hidden;zoom:1;用于清浮动和clear有何区别，清浮动方法都有哪些，作何用处
【慎用？？】和触发ie的haslayout【需要深入】,无法被继承，那是否可以这么理解：如果外层盒子使用，那么内层盒子都要做此处理？？？？？？？？、
8,line-height的使用，【需要深入】
9,for(var x in oSkin) oSkin[x].className = "current";和            
for(var x in oSkin) oSkin[x].className = "";
this.className = "current";不一样
【已解决】
1，提示：Uncaught ReferenceError: Invalid left-hand side in assignment：
---是因为&&右边的表达式未加上（）
2，原文样式表中因涉及到外部样式表的引用，故，原文的代码正常打开，显示会报错：
Failed to load resource: the server responded with a status of 404 (Not Found)
---可以根据上下文重新自己将外部样式表补全。
3，无序列表使用了a标签，但是标签内的内容却没有显示默认的下划线，但通过开发者工具查看，其默认样式中，是有text-decoration:underline;？？？这是为何
---是因为自己操作失误，粗心没有将内容放进a标签。【引以为戒】

4，关于html,body {height:100%}，要怎么理解
---如果不这么设定，浏览器会默认html，body的高度由子元素div的内容支撑。
设定之后，html和body的高度便不会在变，而div的高度则默认继续由其子元素的内容支撑直到出现为其设定对应宽高。嗯，后续的东西还可以深挖，暂时可以将其理解为html和body不分彼此；


1，页面加载是的默认样式怎么调用？
---根据原文答案，可以看出，对方是以引入外部样式表而为。【智障的我。。。】
-----------------------------------------------------------------------
备注：
1，浮动的元素，其左上角起始位与父元素content左上角同位。

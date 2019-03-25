# diyizhou 1第5天
### 标签分类
## 1块元素 display:block;
|标签名|描述|
|-|-|
|div|大容器|
|p|段落|
|ol>|有序列表|
|ul>li|无序列表|
|h1~h6|标签标题|
|table|表格|
|form|form表格|
特性：
-独占一行，文本排列方式从上到下
可以设置高度和宽度：padding.margin.border
在不设置宽度和高度的情况下，宽度继承父元素的宽度，高度由自身内容决定
- 标签之间可以嵌套，p标签除外，p标签不能嵌套p标签
## 行内元素
|标签名|描述|
|--|--|
|span|小容器|
|a|超链接|
|b|加粗|
|strong|加粗，有强调作用|
|i|斜体|
|em|斜体，有强调作用|
|sub|下标|
|sup|上标|
|ins|插入|
|del|删除|
|small|定义小号字|
特性 
- 不独占一行，左右排列
- 不可以设置宽度和高度，
- 宽度高度自身内容决定
- 行内元素不能嵌套块元素，a除外
##行内块元素
|标签名|描述|
|--|--|
|img|图片|
|input|input表单|
|textarea|文本域|
|select|下拉列表|
|option|下拉列表项|
|button|按钮|
特性：
- 独占一行，左右排列
- 可以设置高度和宽度：
- .margin.border
- 在不设置宽度和高度的情况下，宽度和高度由自身内容决定。
- 基线对齐问题->文本分割付（有空格和回车生成）
- 间隙问题的解决方法
	- 清掉回车或者空格
	- 将父元素的字体大小设置为0`font-size：0`
	基线对齐问题
	基线对问题 
    vertical-aline: baseline 基准线对齐       vertical-aline: top 上对齐 
    vertical-aline: bottom 下对齐
     vertical-aline: middle 居中对齐
### display属性
display:block 块元素
display:inline  行内元素
display:inline-block 行内块元素
display:none 隐藏
### 盒模型
- 盒子：盒子壁（border）+盒子内容(width+height)+夹层/内边剧(padding)
- padding 内边距
>边框与内容的距离

  

```
   padding: 10px 20px 30px 40px  
            /* 设置四个值时 内边距分别是上 右 下 左 */
   padding: 10px 20px 30px
            /* 设置个值时 内边距分别是上 左右 下  */
padding: 10px 20px   /* 设置两个值时 内边距分别是上下 左右   */
  padding: 10px     /* 设置一个值时 内边距分别是上下左右   */
```
### border
  /* 边框 border-widsh 边框大小 */
            /* 边框 border-style 边框样式*/
            /* 边框 border-color *边框颜色/
边框样式：
- dashed
- soilid
- dotted

盒模型
- 边框+外边距+


## margin常见的问题
- 值传递问题
- >当两个为父子关系式，给儿子设置的margin-top后，他会连带父元素一块下来哦

解决方法
	- 给父元素加边框    弊端：额外增加了边框
	- 给父元素设置`overflow:hidden`溢出部分隐藏
	- 给父元素加padding-top来替代 给子元素加margin-top
- margin双边距问题
>当两个盒子为兄弟的关系时，给哥哥元素设置margin-bottom,同时给弟弟元素设置margin-top后，margin的值不是他们两个相加之和，而是取最大值
- 解决方法
	- 只给一个盒子设置margin-top/maigin-battom
### 	盒模型计算公式/盒子的计算公式
- relwidth=widtn+左右内边距+左右边框  盒子宽度
- relH=height+上下内边框+上下边框 盒子高度
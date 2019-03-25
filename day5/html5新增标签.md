                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               ## 第三周 第一天
### html5新增标签
|标签名|描述|
|--|--|
|header|头部|
|nav|导航|
|section|定义文档中的结|
|aside|侧边栏|
|footer|尾部|
|article|文章|
|figure|定义独立流内容|
|figercaption|定义内容标题|
|audio|音频|
|video|视屏|	
- audi和video是行内块的块元素
	- src  引入外部的文件
	- contrels 控制隐藏
	- autoplaly 播放
	- loop 循环
## input新增type类型
|type属性值|描述|
|--|--|

|number|数字|

- number 
	- step表示步长

## css3新增属性
- 椭圆或者圆的实现方法 border- radius：- 阴影 `box-shadow`

```
box-shadow：10px 10px 10px 10px pink(颜色)；
第一个值和第二个值必须填写
第一个值：水平方向上的阴影，值为正时，阴影在右侧，值为负时，阴影在左侧。
第二个值：垂直方向上的阴影，值为正时，阴影在下面，值为负时，阴影在上面。
第三个值表示阴影的模糊度 模糊值不能为负
第四个值表示阴影大小，当值大于零时 阴影面积大于盒子 小于0时阴影小于盒子 为零时 面积一样
第五个值为阴影颜色不设置时，默认为黑色。
第六个值默认外阴影 如果想设置内阴影 用inset
```
- 文本阴影：text-shadow
	- 语法：`  text-shadow: 10px  10px  10px  #ccc`

第一个值：水平方向上的阴影，值为正时，阴影在右侧，值为负时，阴影在左侧。
第二个值：垂直方向上的阴影，值为正时，阴影在下面，值为负时，阴影在上面。
第三个值表示阴影的模糊度 模糊值不能为负
 box-sizing:content-box; 为默认值为正常和模型
width:不包含盒子的边框和内边距 他的宽度为内容 的宽度

box- sizing :border-box
width:包含盒子的边框和内边距 内容会变小
## 三栏布局
- 左右定宽，中间自适应
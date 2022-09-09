# 什么是CSS
CSS (Capcading Style Sheets 的缩写)，翻译为“层叠样式表”或者“级联样式表”，简称样式表。
用来它主要是用来给 HTML 网页来设置外观或者样式。
# 语法规则
CSS 代码是由选择器和一对括号组成
大括号里面是有一条一条的声明语句组成
每一条语句都要使用英文状态下面的分号
每一条语句是有“属性：值”组成
CSS 中的属性值一般不加引号。
在 CSS 中如果属性值为数值型数据的时候，一般情况下需要加单位，单位一般都是 px（像素）
在 CSS 中不能出现 HTML 标签。

h1{color:red;font-size:14px;}

# 书写方式
嵌入：嵌入在html文件中，通过Style标签。[例子](0CSS%E5%85%A5%E9%97%A8.html)
外联：写一个以.css为扩展名的文件，在HTML中用<Link>引入
行内：写在html标签中

感觉外联模式比较多，html标签专注于格式，CSS专注于样式。
# 注释
CSS的注释有点像C++
/*内容*/
# 基本选择器
选择器通过一定规则选择固定的html标签。
基本选择器有四种
| 选择器 |格式| 含义| 举例|
|-----|------|--|--|
|通用选择器|*{属性：值；}|通用选择器，将匹配HTML所有标签。不建议使用。IE6不支持，给大型网站增加负担|*{margin:0px;}|
|标签选择器|标签名{属性:值;}|标签选择器，匹配对应的HTML标签|p{font-size:14px;}|
|类选择器|.class属性值{属性:值；}|类选择器，给拥有指定的CLASS属性值的元素设置样式|.box{width:800px;}|
|Id选择器|#id属性值{属性:值;}|Id选择器可以为标有特定ID的HTML元素指定特定的样式，只能使用一次。ID选择器以”#”来定义。|#title{font-size:14px;}

# 尺寸属性
height:高度
width:宽度

# 文本属性
color: #ff0000 或 red 或 rgb(3,5,8):给文本设置颜色。
text-align:left(居左)、right(居右)、center(居中）:设置文本的水平对齐方向。
text-decoration：none(去掉文本修饰线)、设置文本修饰线。underline(下划线),、overline(上划线)、line-through(删除线)：设置文本修饰线
text-transforme：capitalize、uppercase 、lowercase：大小写转换或者首字母大写
Line-height： 固定值或百分比：设置行高
text-indent：px 或者 em：设置首行缩进允许负值。
letter-spacing：px：设置字符间距
word-spacing：px：设置单词间距
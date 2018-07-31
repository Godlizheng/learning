A brief introduction to README.md on GitHub.
===============================


#### 1.Headline (first class title).
Add an equals sign below the text, and the text above becomes a headline.The number of equal numbers is not limited,but it must be more than 0.

#### 2.The title of (Title Two).
You underline the text, the text above becomes a middle heading. The number of underlines is unlimited, and the middle heading is one level lower than the heading.

#### 3.Title 1 to 6.
The size of the text decreases in turn, starting with the'#', the number of'#'is the number of titles, and the'#' and title names are written side by side.

#### 4.Insert the dot symbol.
The editor uses a *, followed by a space after asterisk, otherwise asterisk.

#### 5.


初学者关于README.md文件编辑介绍。
===============================


#### 1.大标题（一级标题）。
在文本下面加等于号，那么上方的文字就变成了大标题，等于号的个数无限制，但一定要大于0。


#### 2.中标题（二级标题）。
在文本下面加下划线，那么上方的文本就变成了中标题，下划线个数无限制，中标题比大标题低一级。


#### 二级圆点、三级圆点。
多加一个Tab，即第二行一个Tab，第三行两个Tab
* 列表一
    * 列表二
        *列表三
 

#### 缩进：
>缩进一
>>缩进二
>>>缩进三
>>>>缩进四
>>>>>缩进五
 

#### 插入链接
[百度](http://baidu.com)
 

#### 插入网络图片：
![](网络图片链接地址)，即叹号!+方括号[]+括号()，如果不加叹号!就会变成普通文本，方括号里可以加入一些 标识性的信息

![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")  
 
 
#### 插入GITHub仓库里的图片.
![](图片链接地址)，即叹号!+方括号[]+括号()，URL写法：http://github.com/自己的用户名/项目名/raw/分支名/存放图片的文件夹/文件夹里的图片名字


#### 给图片加上超链接.
即点击一个图片进入指定网页，方括号里写自己起的标识名称，上下两行标识要一致。

[![baidu]](http://baidu.com)  
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo"  
 
 
#### 插入代码片段.
在代码上下行用```标记，注意`符号是tab键上面那个，要实现语法高亮，则在```后面加上编程语言的名称

```Java
public static void main(String[] args){}
```

```javascript
document.getElementById("ts").innerHTML="Hello"
```

#### 换行.
使用标签<br>


#### 单行文本.
前面使用两个Tab


#### 多行文本.
每行行首加两个Tab


#### 部分文字高亮.
使用``包围，这个符号不是单引号，而是Tab上方，数字1左边那个按键的符号


#### 文字超链接格式.
[要显示的文字](链接的地址"鼠标悬停显示")，在URL之后用双引号括起来一个字符串，即鼠标悬停显示的文本，可不写

 

备注：如何添加README文件？
在创建项目的时候在README那处打钩.

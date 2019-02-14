[冒险主页][src]

**声明**: 该文章大部分引用了 [riku][src1] 和 [guodongxiaren][src2]的示例.

  [src]: https://github.com/TwilightTian/adventure
  [src1]: https://github.com/riku/Markdown-Syntax-CN/blob/master/syntax.md
  [src2]: https://github.com/guodongxiaren/README/blob/master/README.md
  [img1]: https://github.com/TwilightTian/adventure/blob/master/Mission-1/MarkDown/cat.jpg

## 目录
  * [标题](#标题)
  * [图片](#图片)
  * [链接](#链接)
  ** [文字超链接](#文字超链接)
 
### 标题
--------
Markdown 支持两种标题的语法，类 [Setext] 和类 [atx] 形式。

类 Setext 形式是用底线的形式，利用 `=` （最高阶标题）和 `-` （第二阶标题），例如：

    This is an H1
    =============

    This is an H2
    -------------
    
显示效果如下:

   This is an H1
   =============

   This is an H2
   -------------

任何数量的 `=` 和 `-` 都可以有效果。


类 Atx 形式则是在行首插入 1 到 6 个 `#` ，对应到标题 1 到 6 阶，例如：

    # 这是 H1

    ## 这是 H2

    ###### 这是 H6

显示效果如下:

   # 这是 H1

   ## 这是 H2

   ###### 这是 H6

你可以选择性地「闭合」类 atx 样式的标题，这纯粹只是美观用的，若是觉得这样看起来比较舒适，你就可以在行尾加上 `#`，而行尾的 `#` 数量也不用和开头一样（行首的井字符数量决定标题的阶数）：

    # 这是 H1 #

    ## 这是 H2 ##

    ### 这是 H3 ######

### 图片
-------
基本格式：
```
![alt](URL title)
```
alt和title即对应HTML中的alt和title属性（都可省略）：
- alt表示图片显示失败时的替换文本
- title表示鼠标悬停在图片时的显示文本（注意这里要加引号）

URL即图片的url地址，如果引用本仓库中的图片，直接使用**相对路径**就可了，如果引用其他github仓库中的图片要注意格式，即：`仓库地址/raw/分支名/图片路径`，如：
```
https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif
```

|#|语法|效果|
|---|---|----
|1|`![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")`|![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
|2|`![][img1]`|![][img1]

注意例2的写法使用了**URL标识符**的形式，在[链接](#链接)一节有介绍。
>在文末有img1的定义：
```
[img1]: https://github.com/TwilightTian/adventure/blob/master/Mission-1/MarkDown/cat.jpg
```

### 链接
--------
#### 文字超链接

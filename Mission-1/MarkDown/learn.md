**声明**: 该文章大部分引用了 [riku][src1] 和 [guodongxiaren][src2]的示例.

  [src1]: http://gitcafe.com/riku/Markdown-Syntax-CN/blob/master/syntax.md
  [src2]: https://github.com/guodongxiaren/README/blob/master/README.md


## 目录
  * [标题](#标题)
  
### 标题
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

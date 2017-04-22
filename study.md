
学习链接地址 <http://xianbai.me/learn-md/article/about/readme.html>

# 标题

# H1

## H2
----


#### H4

# H5

# 引用

> 引用内容

>多行引用  
>可以在每行前加`>`

>如果仅在第一行使用 `>`
后面相邻的行即使省略`>`，也会变成引用内容


>如果引用内容需要换行,  
>可以在行尾添加两个空格
>
>或者在引用内容中加一个空行

>也可以在引用中
>>使用嵌套的引用

>在引用中可以使用其他任何 *Markdown* 语法


# 无序列表

* 可以使用 `*` 作为标记
+ 也可以使用 `+`
- 或者是 `-`

# 有序列表
1. 有序列表以数字和 `.` 开始;
2. 数字的序列并不会影响生成的列表序号
10. 但仍然推荐按照自然顺序 (1.2.3...) 编写

# 嵌套的列表
1. 第一层
    + 1-1
    + 1-2
2. 无序列表和有序列表可以随意相互嵌套
    1. 2-1
    2. 2-2

05\. 可以使用：数字 `\.` 来取消显示为列表

# 代码

    <html>  // Tab开头
        <title>Markdown</title>
    </html> // 四个空格开头


行内代码 `<html><title>Markdown</title></html>`

多行代码

```
#include <stdio.h>

int main()
{
    printf("Hello World\n");
}
```

代码高亮

```c
#include <stdio.h>

int main()
{
    printf("Hello World\n");
}
```

```php
<?php
printf("Hello World\n");
?>
```




# 分隔线

可以在一行中使用三个或者更多 `*`、`-`或者`_`来添加分隔线
***
上面是分隔线

----
上面是分隔线

_____
上面是分隔线

多个字符之间可以有空格(空白符)，但不能有其他字符
* * *
上面是分隔线

- - - 
上面分隔线

# 链接

I like [Google](https://www.google.com)

1. 普通链接  
[Google](https://www.google.com '谷歌')

2. 指向本地文件的链接(相对路径，相对当前markdown文件的路径)    
[4.jpg](../..//tmp/image/4.jpg)

3. 包含'title'的链接  
[Google](https://www.google.com '谷歌')

4. 自动链接  
使用<>包括的url或者邮箱地址会被自动转换为超链接  

<https://www.google.com>  
<stamhe@qq.com>



# 图片

1. 行内式  
![美女](../../tmp/image/4.jpg)

2. 参考式  
[美女]: ../../tmp/image/4.jpg  

3. 指定图片的大小  
<img src="../../tmp/image/4.jpg" alt="美女" title="美女title" width="50" height="50" />


# 强调

这是用来演示斜体的文本 *演示* 的 _文本_

这是用来演示加粗的文本 **演示** 的 __文本__

这是删除线 ~~删除线~~


# 表格

|name                   |age    |
|:-------:              |-----: |
|HeQuan                 |23     |
|StamHe                 |32     |
|He                     |2      |
|Stam                   |100    |
|[Google](http://g.cn)  |30     |


# 任务列表

- [ ] Eat
- [x] Code
    - [x] Html
    - [x] CSS
    - [x] Javascript
- [ ] Sleep
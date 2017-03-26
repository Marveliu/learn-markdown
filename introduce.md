
# head
## head2
### head3
#### head4
##### head5
###### head6

# blockquotes
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

> 当然也可以这样
进行简写

> 空行需要来添加>
>> 同样也是可以支持嵌套的嵌套一些别的格式
>1. hello

# list

* hello
* world
+ hello
+ world
- hello
- world
> 不同的格式之间会有空行

1. hello
2. world

> 列表项目可以包含多个段落，每个项目下的段落都必须缩进 4 个空格或是 1 个制表符：

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.

> 如果要放代码区块的话，该区块就需要缩进两次，也就是 8 个空格或是 2 个制表符：
* code block
        
        
        hello


# 分割线

***
* * *
----

# 区段元素

## 链接
> 行内式

This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

>参考式

This is [an example][id] reference-style link.

[id]: http://example.com/  "Optional Title Here"

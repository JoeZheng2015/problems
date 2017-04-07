# 使用 flex 布局去除行内元素间的空隙

[示例](https://joezheng2015.github.io/problems/trim-whitespace/)([源代码](https://github.com/JoeZheng2015/problems/blob/master/trim-whitespace/index.html))

inline-block 标签间有空白换行或回车符时，渲染出来的元素间会有空隙，亲测有多种方法可以消除空隙

## flex
只要为 inline-block 的父元素增加 `display: flex` 即可

## word-spacing, margin
word-spacing 是指定单词间空白的，只要为 inline-block 的父元素指定合适 word-spacing 即可。但是需要计算出一个空隙的宽度，有些复杂

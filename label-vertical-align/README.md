# 移动端文本小于12px的垂直居中问题

[示例](https://joezheng2015.github.io/problems/src/label-vertical-align/)[源代码](https://github.com/JoeZheng2015/web-problems/blob/master/src/label-vertical-align/index.html)

现象：小于 12px 的字通过 line-height 无法居中，会偏上，特别是在安卓手机上

解决办法：字体放大 2 倍，再 scale(0.5)
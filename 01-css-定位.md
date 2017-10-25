定位
==
一切皆为框
---
块级元素: div h1 p , 显示内容为一块内容, 即块框.

行内元素: span strong b , 显示内容为一行中, 即行内框.

设置display属性为block, 可以将行内元素表现得象块级元素一样.

css 定位机制
--
三种定位机制: 普通流/浮动/绝对定位
- 默认普通流中定位, 普通流中的元素的位置由元素在html中的位置决定.
- 块级框由上到下一个地排列, 框之间的垂直距离是由框的垂直外边决定.
- 行内框在一行中水平排列, 可以使用水平内边距/边框/外边距调整间距, 但是, 设置垂直内边距/边框/外边距不影响行内框的高度. 设置行高可以增加框高度.


css position属性
--
- static 默认正常位置
- relative 相对正常位置 进行定位
- absolute 相对 **除static以外** 第一个父元素进行定位
- fixed 相对窗口 进行定位
- inherit 继承父元素定位属性

注意: top/right/bottom/left 定位属性对static定位方式无效, 可以对relative/absolute/fixed定位方式有效.

css 定位相关属性
--
- left/right/top/bottom
- overflow
- clip
- z-index

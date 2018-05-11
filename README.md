[ife_2018](https://github.com/ycitsme/ife_2018)


日期 | 时间 | 名称 | demo代码 | demo展示 | 备注 
--- |--- | --- | --- | --- | ---
2018-05-02 | 20:13-22:27 | 第一天：为什么有那么多人要做前端？| <a href = "day1.html">day1</a> | [day1](https://ycitsme.github.io/ife_2018/day1.html) |介绍了一些好看的视觉效果不错的前端页面，让学员能够以之为目标努力。
2018-05-06 | 20:06-20:16 | 第七天到第八天：学习布局 | / |  / | 什么都没做。
2018-05-08 | 16:52-17:55 19:15-23:30 | 第七天到第八天：学习布局 | / | / | 学习[MDN定位](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/CSS_layout/%E5%AE%9A%E4%BD%8D),使用[w3c](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_default)作为在线html编辑器。
2018-05-10 | 11:23-12:15 12:30-13:30 15:10-18:30 18:50-21:10 21:50-23:40 23:40-23:58（写备注等收尾工作）| 第七天到第八天：学习布局 | [day7&8_float](day7&8_float.html) [day7&8_position](day7&8_position.html) [day7&8_flex](day7&8_flex.html) |[day7&8_float](https://ycitsme.github.io/ife_2018/day7&8_float.html) [day7&8_position](https://ycitsme.github.io/ife_2018/day7&8_position.html) [day7&8_flex](https://ycitsme.github.io/ife_2018/day7&8_flex.html) |学习float:[浮动](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/CSS_layout/Floats)；position:[定位实例练习](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/CSS_layout/Practical_positioning_examples)（页面布局框架也来自这里）；flex:[弹性盒子](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/CSS_layout/Flexbox)。关于float和position中的宽度自适应计算和Position inline-block实现部分参考[七种实现左侧固定，右侧自适应两栏布局的方法](https://segmentfault.com/a/1190000010698609)。
2018-05-11 | 13:50-17:02 17:02-17:31（写备注）| 第七天到第八天：学习布局 页面设计作业 | [day7&8_design](day7&8_design.html) | [day7&8_design](https://ycitsme.github.io/ife_2018/day7&8_design.html) | 完成页面设计做页，页面分成5个部分，头部、广告、导航、主体、尾部。头部的左侧logo和右侧链接可以分别使用左浮动和右浮动来实现，最后要在头部内清除浮动。广告部分使用绝对定位将广告分页列表定位到右下侧，然后列表中的元素设置成inline-block，指定宽度、文本居中、设置边框。导航部分和广告部分的广告分页列表相似，使用绝对定位，然后将列表中的元素设置成inline，这里不设置成inline-block是因为[inline-block的元素之间的空格会使元素之间产生间隙](http://zh.learnlayout.com/inline-block-layout.html) ，副作用是无法设置宽高，但是可以使用padding来代替。主体部分是可以使用flex，每行一个section，对于每一行，统一设置高度，并且使用flex:1 200px来设置均分且最小宽度为200px，同时设置flex-wrap:wrap使得当一行宽度已经超过960px时自动换行。最后一行的尾部直接指定宽高，设置背景色，然后用text-align:center使文本水平居中，设置padding-top，使得文字距离顶部有一定距离即可。目前bug:1.当页面缩小时，向右拖动页面，页面的头部和广告部分消失。2.导航中被激活的下边框并没有完全消失。3.主体中的文字没有竖直居中。



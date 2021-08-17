# 5000choyen
适用hoshino的5000兆円欲しい! style图片生成器插件

在[SAGIRI-kawaii](https://github.com/SAGIRI-kawaii)大佬的 Graia-Saya [插件](https://github.com/SAGIRI-kawaii/saya_plugins_collection/tree/master/modules/5000zhao)基础上修改而来的适用hoshino的5000兆円欲しい! style图片生成器插件。

## 配置

5000choyen文件夹放进module文件夹，__bot__.py增加配置这类入门操作就不说了）

重点：需要自己寻找想用的字体文件，并配置generator.py下upper_font_path（上半句字体）和downer_font_path（下半句字体）变量！

--------

字体上想贴近原版风格的话上半句选粗黑体类，下半句选粗宋体类；~~我调试用的默认字体是经典粗黑简和方正粗宋简体~~，字体文件以防万一就没放进来（版权流氓惹不起.jpg），可以自己找下，也可以自己换喜欢的用

P.S. 不同字体就算设置相同字号draw.text画出来的实际大小也不一样，默认参数是按照我用的字体调整的，换别的字体会有一定的偏差，有需要的话可以根据自己实际使用的字体按需调整相应参数。

字号可以调整[这里](https://github.com/pcrbot/5000choyen/blob/b603868178d727f5c3d2dff716642326cba04af9/generator.py#L133)的"\_round(height/3)"参数，字体颜色渐变范围可以调整[这几个位置](https://github.com/pcrbot/5000choyen/blob/b603868178d727f5c3d2dff716642326cba04af9/generator.py#L83)的size参数。

几个颜色渐变范围，尤其是黑色部分的占比会很影响视觉效果，建议根据自己的字体调整到自己觉得效果最好的程度）

顺便用默认字体默认参数大概是这个效果，仅供参考：
![@HX104L(TYO@NQY$UXR8E8C](https://user-images.githubusercontent.com/55473115/129693767-67712df7-8dbf-465b-ab22-4b7029af5660.PNG)

## 用法

使用方法：发送“5000兆元 (上半句)|(下半句)”

## 关于#Gboard实现#五笔输入的探讨
## 一、起因：
本来使用#Trime，奈何一直没有好的主题，也不能和系统主题统一，好不容易在Github上找到了一个主题，却偶尔输入卡顿。加上有时有发送gif的需求。故探索五笔怎么在Gboard安卓中实现。使用中还是会碰到很多问题，希望大佬指点一二

## 二、Gborad实现五笔打字的方式：
- 1、先下载五笔词库[releases](https://github.com/vic-sys/Gboard-wubi/releases)，或自己使用深蓝输入法转换工具制作
- 2、Gboard设置——词典——个人词典——中文简体——右上角导入

## 三、使用中的问题
- 1、一级简码的那二十几个字，受重码影响等于废了
- 2、没有拼音反查和自动上屏，但好处是不用切换拼音直接打拼音
- 3、偶尔间歇性的失忆（打出编码后没有调用五笔词条），特别是Gboard更新后的一两天里
- 4、不支持滑行输入

## 四、感谢
- wzyboys   https://wzyboy.im/post/1251.html
- 深蓝词库转换   https://github.com/studyzy/imewlconverter


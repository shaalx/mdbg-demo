#	Vim

***

##	vim语法

*	[https://linux.cn/article-6610-1.html](https://linux.cn/article-6610-1.html)

##	vim 切换

_2015-11-28_


***

##	USAGE

*	**reference to [https://www.shiyanlou.com/courses/running/16](https://www.shiyanlou.com/courses/running/16)**

##	普通模式

按Esc进入普通模式，在该模式下使用方向键或者h,j,k,l键可以移动游标。


按键 			|	说明
--------------------|----------
h 			|	左
l 			|	右（小写L）
j 			|	下
k 			|	上
w 			|	移动到下一个单词
b 			|	移动到上一个单词

##	插入模式

命令 		|	说明
-------------|-------------
i 		|	在当前光标处进行编辑
I 		|	在行首插入
A 		|	在行末插入
a 		|	在光标后插入编辑
o 		|	在当前行后插入一个新行
O 		|	在当前行前插入一个新行
cw 		|	替换从光标所在位置后到一个单词结尾的字符


##	删除

命令 		|	说明
--------------|-------------
x 		|	删除游标所在的字符
X 		|	删除游标所在前一个字符
Delete 	|	同x
dd 		|	删除整行
dw 		|	删除一个单词（不适用中文）
d$或D 	|	删除至行尾
d^ 		|	删除至行首
dG 		|	删除到文档结尾处
d1G 		|	删至文档首部
2dd		|	表示一次删除2行

##	命令行模式下退出vim

**从普通模式输入:进入命令行模式，输入wq回车，保存并退出编辑**

命令 				|	说明
---------------------------|------------
:q! 				|	强制退出，不保存
:q 				|	退出
:wq! 				|	强制保存并退出
:w <文件路径> 		|	另存为
:saveas 文件路径 	|	另存为
:x 				|	保存并退出
:wq 				|	保存并退出

_2015-12-04_


命令 		|	说明
--------------|-------------
u 		|	撤销操作
$ 		|	跳至文末
Delete 	|	同x
dd 		|	删除整行
dw 		|	删除一个单词（不适用中文）
d$或D 	|	删除至行尾
d^ 		|	删除至行首
dG 		|	删除到文档结尾处
d1G 		|	删至文档首部
2dd		|	表示一次删除2行

_2016-7-20_
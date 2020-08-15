# 关于Java的学习汇报
在两个星期前我开始了Java的学习，就我目前的学习进度，我所学到的内容可以分为三部分：了解Java的发展历史、学习Java中的“汉字”、学会Java的“造句”。>在两个星期前我开始了Java的学习，就我目前的学习进度，我所学到的内容可以分为三部分：了解Java的发展历史、学习Java中的“汉字”、学会Java的“造句”。
         ##对于java历史的了解。
	 
- 在看了有关Java的介绍资料后一个深刻的体会是Java的跨平台性。这也是我在读到詹姆斯-高斯林为Green项目设计语言时最好奇的一点，为什么java写的程序可以在不同的操作系统上运行？通过百度等手段，我大体了解到java的厉害并不是它语言的厉害，它的语法规则主要是照搬了c++，吸取了里面的面向对象思想，但c++是不具备跨平台功能。它厉害在于它有一个十分厉害的虚拟机，可以针对每种操作系统的规则进行翻译。
         ##学习java中的“汉字”。
	 
- 在这个版块中我开始用文档进行编程、学会了数据类型，和基本的运算符号。在这个版块中我遇到了如下的几个问题。（1）我们编写的源代码和工具不在同一文件中，这时候我在字节码文件所在的文件夹下面输入javac是不能对文件进行翻译的。（2）用System.out.println();输出的时候如果括号里面既有中文又有英文，会显示编码GDK的不可映射字符，当我只有英文的时候正常，只有中文的时候无法识别。（3）float x=1.4;编译会报错。（4）为什么运行的时候不用输入后缀名（5）为什么 int x=1; x=x++;最后结果x会等于1；即使循环100次后结果仍然为1.
这些问题，我通过百度、问知乎、翻书都得到了答案。明白了代码中含有中文字母（注释也算）用cmd运行java程序的时候，系统默认的编码格式是gdk，而包含中文字符的代码一般是UNICODE，所以直接运行含中文的代码很容易出错
也知道了，编译出来的字节码文件会被搬运到内存去所以不用加.class，也知道了在JVM开拓的内存会被分为三大块：栈内存、堆内存、方法区等等。
	## 学习java的语法结构。

- 学习java的语法结构过程我依旧是循序渐进地从头到尾的看了一遍，即使这些和c语言十分的相近。在语法结构的学习中我发现了很多新的东西，比如break加上标签后可以一口气跳出外层循环，continue也可以借助标签跳出指定的循环，还学到了新的foreach语句，这些新知识像一颗颗珍珠给我惊喜。

- Java的前期学习十分的枯燥，但我为了不让自己骄傲，自满还是硬着头皮把前期的知识视频，书籍都看了一遍并用word文档录了知识的点和自己存在疑问的地方，虽然学得很慢但我对很多原理上的问题有了更深的了解。

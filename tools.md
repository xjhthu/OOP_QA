# This page lists the useful programming tools for C++ programming, preferably with description of the tool or with an example illustrating how to use the tool. 

## PuTTY

It is a tool to connect remote client, with which we can easily manage our remote systems.

With its long history, its stability is guaranteed.

[Official Website](https://www.chiark.greenend.org.uk/~sgtatham/putty/)

## Typora


*Author*: Biru Yang     *Date*: 2020.6.24


Typora是一款支持**实时预览**的**Markdown文本编辑器**，目前使用免费。

Typora的官网是这样定义它的产品的：“A truly minimal markdown editor”。

其使用方式与其它Markdown编辑器完全相同，在编写Markdown文件的同时就可以在同一个窗口看到该文件编译后的效果。

它有以下特点：

+ **真正**的实时编辑。

+ 提供大量的人性化设置选择：

  + 可选择Markdown语法风格；
+ 智能标点；
  + 打字机模式、专注模式、源代码模式等方便的输入模式；
+ 空格和换行主要采用CommonMark作为标注规范；
  
+ 可输入emoji表情/方便地插入图片。

+ 原生支持LaTeX。

由于其使用与其它Markdown编辑器基本相似，故在此不做更多的说明。

其更详细的特性和下载地址见其官网：[Typora官网](https://typora.io/)

这篇文章给出了其良好使用特性的详细中文介绍：[Typora完全使用详解](https://sspai.com/post/54912)


## Understand


*Author*: Biru Yang     *Date*: 2020.6.24


Understand是一款代码浏览分析工具，其官网为[scitools.com](https://scitools.com/)。我在阅读liquidfun项目时使用了该工具。

国内相关从业人员大多使用source insight，但Understand的功能其实比source insight强大。

其功能主要如下：

+ 代码检查：检查代码是否符合MISRA-C 2004, MISRA-C++ 2008等国际标准（也可自定义检查标准）。

+ 代码编辑；

+ 依赖关系浏览器：快速浏览文件及结构依赖关系，导出依赖关系图标。

+ 即时搜索：从代码中即时搜索关键字，方便代码阅读。

+ 生成多种图表：

  + 声明关系图

  + 继承关系图

  + 控制流图

  + 依赖关系图

  + UML类图

  + etc.

其支持Windows(32位/64位)/Linux(32位/64位)等多种操作系统，支持阅读的语言包括：

> Ada, C/C++, C#, FORTRAN, Java, JOVIAL, Pascal, PL/M, VHDL, Cobol, Web Languages(PHP, HTML, CSS, Javascript, XML and etc.)

## Github Desktop
This tool helps you fork branches, edit repositories and submit pull requests on the desktop.
Website: https://desktop.github.com.

## Sublime Text
Sublime Text is a light and effective text editor which is commonly used with Github Desktop.
An interesting feature of Sublime Text is that it can open executable files as hexadecimal numbers and edit them directly.
Website: www.sublimetext.com.

## MarkdownPad 2
This tool allows you to write texts in markdown format and preview the texts in the window.
website: http://markdownpad.com.

## Visual Studio Code

Visual Studio Code（以下简称vscode）是一个轻量且强大的跨平台开源代码编辑器（IDE），支持Windows，OSX和Linux。内置JavaScript、TypeScript和Node.js支持，而且拥有丰富的插件生态系统，可通过安装插件来支持 

Website:https://code.visualstudio.com

## Vim

Vim is a text editor developed from VI. Code completion, compilation, error jump and other convenient programming functions are particularly rich, widely used among programmers, along with Emacs as a uniX-like system users favorite text editor.

## GNU Make
Make is an essential tool for writing a large program. It can find makefile files and efficiently compile linked source files.

## IDA
IDA是Interactive Disassembler Professional的缩写，指交互式反汇编器。可以用于分析不知道源码的C可执行程序，不仅可以得到等效源码、汇编代码，还能分析栈和堆的分配方式，如函数地址和变量地址。

## CLion

A **cross-platform** IDE for C and C++

CLion是Jetbrains公司旗下新推出的一款专为开发C/C++所设计的跨平台IDE。它是以IntelliJ为基础设计的，同时包含了代码辅助、代码生成、安全重构、快速文档、实时代码分析、集成调试器等许多智能功能以提高开发效率。

**对学生完全免费**，提供官方简体中文插件。

Website: https://www.jetbrains.com/clion/

## vTune
VTune Profiler (formerly VTune Amplifier) is a performance analysis tool for x86 based machines running Linux or Microsoft Windows operating systems. Many features work on both Intel and AMD hardware, but advanced hardware-based sampling requires an Intel-manufactured CPU.(It is very powerful)

## StarUML
StatUML是一款开放源码的UML开发工具，支持创建UML类图，生成类图和其它类型的统一建模语言图表。

其特点如下：

* 支持绘制：用例图、类图、序列图、状态图、活动图、通信图、构件图、部署图等多种UML图
* 完全免费：不仅免费下载，而且代码都是开源的
* 可以将生成图导出为：PDF、JPG、JPEG、BMP、EMF等多种格式的文件
* 语法检验：StarUML遵守UML的语法规则，不支持违反语法的动作。
* 正反向工程：可以依据类图的内容生成Java、C++、C#代码，也能够读取Java、C++、C#代码反向生成类图。

总的来说这是一款简单、易上手、功能全面的UML开发工具，可以用它来图例化大作业文档中的许多设计。

官网网址：https://staruml.io/

入门教程：https://blog.csdn.net/csdn_20150804/article/details/105004375

## openFrameworks

openFrameworks（以下简称 oF） 是一个开源的、跨平台的 C++ 工具包。旨在开发实时项目，重点是生成和处理图形和声音。如今，这是一个很受欢迎的实验平台，用于生成和声音艺术，以及创作互动装置和视听表演。

oF 的强大之处在于，它不仅是一个通用的胶水（glue），同时它还封装了多种常用的库，包括：

- OpenGL、GLEW、GLUT、libtess2、cairo - 用于处理图形；
- rtAudio、PortAudio、OpenAL、Kiss FFT、FMOD - 用于音频的输入、输出和分析；
- FreeType - 用于字体显示；
- FreeImage - 用于图像存储和载入；
- Quicktime、GStreamer、videoInput - 用于视频播放和截取；
- Poco - 用于开发网络应用；
- OpenCV - 用于计算机视觉；
- Assimp - 用于读入 3D 模型。

这些库虽然遵循着不同的规则和用法，但 oF 在它们基础上提供了一个通用的接口，使得使用它们变得很容易。

除此之外，oF 的另一亮点在于它具有很好的跨平台特性。目前它支持 5 种操作系统（Windows、OSX、Linux、iOS、Android）以及 4 种 集成开发环境（XCode、Code::Blocks、Visual Studio、Eclipse）。

## pb_ds

[link](https://gcc.gnu.org/onlinedocs/libstdc++/ext/pb_ds/)

This is a library of policy-based elementary data structures: associative containers and priority queues.

It is designed for high-performance, flexibility, semantic safety, and conformance to the corresponding containers in std and std::tr1 (except for some points where it differs by design).

It is like STL, but have a lot of more powerful tools with better efficiency than STL. (such as HashTable, Balance Tree...)

## Intelligent Comparison

Beyond Compare is focused. Beyond Compare allows you to quickly and easily compare your files and folders. By using simple, powerful commands you can focus on the differences you're interested in and ignore those you're not. You can then merge the changes, synchronize your files, and generate reports for your records.

[Homepage](https://www.scootersoftware.com/features.php)

## Ubuntu Pastebin
You can share your code with others conveniently with it.
Website: https://paste.ubuntu.com/

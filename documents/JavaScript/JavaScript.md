# JavaScript

JavaScript（简称 JS）是一种直译式、描述性客户端脚本语言，是一种弱类型、动态类型语言。可以嵌入 HTML 代码中由客户端浏览器运行。

JavaScript ML 超文本标记语言、Java Applet（Java 小程序）一起实现在一个 Web 页面中链接多个对象，与 Web 客户交互作用，从而开发出客户端的应用程序等。

## JavaScript 特点

- JavaScript 不像 C、C++、Java 这些语言要先编译后才能运行。
- JavaScript 是在程序运行过程中逐行地解释。
- JavaScript 是一种基于对象的语言，这意味着 JavaScript 能运用其已经创建的对象。故，许多功能可以来自于脚本环境中对象的方法与脚本的相互作用。
- JavaScript 是一种基于 Java 基本语句和控制流之上的简单而紧凑的设计。其次，JavaScript 变量类型采用的是弱类型，并未使用严格的数据类型。
- JavaScript 具有非常高的安全性。JavaScript 不被允许访问本地的硬盘，且不能将数据存入服务器，不允许对网络文档进行修改和删除，只能通过浏览器实现信息浏览或动态交互。简言之，JavaScript 将只存在于它自已的小小世界——Web。但当把 JavaScript 的一个设计目标设定为 “Web 安全性” 时，就需要牺牲 JavaScript 的一些功能。
- JavaScript 是动态的，可以直接对用户或客户输入做出响应，无须经过 Web 服务程序，不需要任何网络来回传输资料。JavaScript 语言可以设计出很多特效，也可以响应用户的事件、与用户进行互动、增加网站的安全性，是动态网页设计的一个最佳选择。
- JavaScript 具有跨平台性。JavaScript 依赖于浏览器本身，与操作环境无关。

## JavaScript 与 HTML 与 CSS 与 DIV 布局

HTML（Hyper Text Markup Language）超文本标记语言，为 Web 前端。

网页的本质就是超文本标记语言，使用 HTML，再结合其他的编程技术（如 JavaScript），就可以制作出酷炫的网页。

在 HTML 开发中，JavaScript 脚本语言的使用，可以给网页增加动态功能。

JavaScript 是通过嵌入或调入在标准的 HTML 语言中实现的，可以弥补 HTML 语言的缺陷，是折中 Java 和 HTML 的选择。



CSS（Cascading Style Sheets）层叠样式表，是一种分离网页内容和网页样式的标记语言，为 HTML 提供了样式描述，通过定义 CSS 可以让网页变得非常美观。

CSS 文件链接方式，有 3 种：

- 第一种：内联样式。将样式表写在标签内部，作为标签的属性值（style 属性中的值，就是 CSS 代码）。
- 第二种：链入内部 CSS：将样式表写在 style 标签中。
- 第三种：链接外部 CSS：将样式表写在 CSS 文件中（后缀为 .css 的文件），在 HTML 中，通过 link 标签去引入。



DIV 标签是对整个页面进行布局，结合 CSS 即可设计出酷炫完美的网页。

DIV 标签作为容器，可以对网页进行分块渲染，属性非常多，例如高度、宽度、背景色、边框、内边距、外边距等。

每个 DIV 标签中都可包含其他对象，如文本信息、图像信息、表格信息等。



## JavaScript 与 Java 

JavaScript 是一种基于 Java 基本语句和控制流之上的简单而紧凑的设计。

### 基于对象和面向对象

JavaScript 与 Java 在语法上很类似，但其本质有着根本的区别，Java 是一种比 JavaScript 列加复杂的程序语言。

Java 是一种真正的面向对象的语言，即使是开发简单的程序，也必须设计对象。JavaScript 是一种脚本语言，是一种基于对象（object based）事件驱动（event driven）的编程语言。因而 JavaScript 本身可提供非常的内部对象给设计人员使用。



### 解释和编译

两种语言在浏览器中的执行方式不一样。

Java 的源代码在传递到客户端执行之前，必须经过编译。因而客户端上必须具有相应平台上的仿真器或解释器，从而通过编译器或解释器实现独立于某个特定平台编译代码。

JavaScript 是一种解释性编程语言，其源代码在发往客户端执行之前，不需要经过编译，所以只需要将文件格式的字符代码，发送给客户端，由浏览器解释执行即可。



### 强变量和弱变量

Java 采用强类型变更检查，即所有变量在编译之前必须声明。例，Integer x;  x =1234;  String y;  y = "4321"; 

JavaScript 变量类型采用的是弱类型，并未使用严格的数据类型。即变量在使用前无须做声明，解释器在运行时会检查其数据类型。例，x=1234;  y = "4321";  前者说明 x 为数值型变量，y 为字符型变量。



### 代码格式不一样

Java 是一种与 HTML 无关的格式。

JavaScript 的代码是一种文本字符格式，可以直接嵌入 HTML 文件中，并动态装载。

在 HTML 文件中，这两种编程语言的标识不同。Java 使用 <applet>...</applet>。JavaScript 使用<Script>...</Script>。

### 静态联编和动态联编

Java 采用静态联编，即 Java 的对象引用必须在编译时进行，以使编译器能够实现强类型检查。

JavaScript 采用动态联编，即 JavaScript 的对象引用在运行时进行检查，若不经编译，则无法实现对象引用的检查。

## JavaScript 链接方式

JavaScript 有 3 种链接方式：

- 第一种：内联。将 JS 代码定义在标签中。
- 第二种：内部嵌入。
  - 在页面中嵌入 script 标签，并设置 type 属性为 ”text/javascript“ 。
  - 通常将嵌入的 script 标签定义在<head></head>中，也可以将其定义在代码中。
- 第三中：外部链接。
  - 在 <script> 标签中，还可以定义 src 属性，src 属性表示引入 JS 文件的路径。

由于一个网页中，需要引入多个 JS 文件，因此外部链接是开发中，最常用的方式。

# JavaScript 模块

## DOM 文档对象模型

DOM 是 JavaScript 最重要的组成部件。

DOM 将整个页面规划成由节点层级构成的文档，描述了一个层次的节点树，通过 DOM 可以访问 HTML 文档中的所有元素。

# JavaScript 注意事项

- JavaScript 区分大小写。
- JavaScript 每条语句以分号 ”;“ 结束。





# Ajax



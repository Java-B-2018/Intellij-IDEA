# lab1
学习Intellij IDEA的安装以及使用


# 什么是 Intellij IDEA
IntelliJ是一款综合的Java 编程环境，被许多开发人员和行业专家誉为市场上最好的IDE，我们可以在Intellij这个集成环境中进行Java代码的而编写、编译而不需要使用命令行


IntelliJ IDEA将会是大家大学四年的主力开发工具，大部分的代码都会使用IntelliJ开发。

除了本课程外，同学们还将在这些课程中使用IntelliJ的开发：

+ 大一下学期的```Web应用基础```
+ 大二上学期的```算法与数据结构```
+ 大三的```计算机图形学```，```高级Web```
+ 选修课，如```智能移动平台应用开发```等


## Intellij 版本

Intellij 分为两个版本：

+ **Ultimate版**：旗舰版（专业版），具备Java，Web，Android等平台的开发功能，次此版本是**收费**的，但可以使用复旦学邮注册教育账号而获得**免费使用的资格**

+ **Community版**：免费版，包含基本的Java开发功能


# 安装Intellij IDEA

本Lab以Intellij IDEA Ultimate版为例，演示Intellij的安装过程

## 注册教育账号

1. 打开网址：[https://www.jetbrains.com/shop/eform/students](https://www.jetbrains.com/shop/eform/students)

2. 使用自己的学邮（18xxxxxxxxx@fudan.edu.cn）注册一个账号


## 下载

 进入Intellij IDEA 下载页，根据自己的操作系统<b>(Windows/macOS/Linux)</b>下载Ultimate版并安装：[https://www.jetbrains.com/idea/download/](https://www.jetbrains.com/idea/download/)

 ![download](https://raw.githubusercontent.com/Java-B-2018/lab1/master/images/download.png)
 
***安装过程中遇到Installation Options这一步时，建议按照如下提示勾选：***

+ 在```Create Desktop Shutcut```这一栏，选择```64-bit launcher```（如果是32位操作系统则勾选```32-bit launcher```）

+ 在```Create Associations```这一栏，勾选```.java```

+ **不勾选** ```Download and install JRE x86 by JetBrains```

(插入图片)



# 准备工作

+ 在桌面上打开安装好的Intellij IDEA，会弹出第一次设置，选择```Do not import settings```

(插入图片)


+ 将协议内容的滚动条拖到最底部，再点击```Accept```按钮

(插入图片)


+ 在激活账号中填入之前注册的学生账号

(插入图片)


+ 接下来的所有设置步骤**一律直接点击下一步即可**


# 使用Intellij IDEA编写第一个Java程序


## 创建工程


+ 打开Intellij，点击```Create New Project```

![open](https://raw.githubusercontent.com/Java-B-2018/lab1/master/images/open.png)

+ 在弹出窗口右上角的```Project SDK```一栏，选择```New ...```，新建SDK并选择到电脑上JDK的目录。若```Project SDK```这一栏会出现```1.8```的选项则代表成功

![new](https://raw.githubusercontent.com/Java-B-2018/lab1/master/images/new.png)

+ 点击```Next >```，```Next >```，输入工程名与工程路径，再点击```Finish```

![info](https://raw.githubusercontent.com/Java-B-2018/lab1/master/images/info.png)


## 创建Java类

+ 在左侧栏找到```src```，右键并选择```New```——```Java Class```

![create](https://raw.githubusercontent.com/Java-B-2018/lab1/master/images/create.png)

+ 填写Java类名称并确定

![name](https://raw.githubusercontent.com/Java-B-2018/lab1/master/images/name.png)

## 编写代码与运行

+ 将右侧的初始代码改成自己的代码

![code](https://raw.githubusercontent.com/Java-B-2018/lab1/master/images/code.png)

+ 编写完成之后，点击左侧的绿色箭头，点击```Run 类名.main()```，即可在下方看到运行结果

![run](https://raw.githubusercontent.com/Java-B-2018/lab1/master/images/run.png)


![console](https://raw.githubusercontent.com/Java-B-2018/lab1/master/images/console.png)

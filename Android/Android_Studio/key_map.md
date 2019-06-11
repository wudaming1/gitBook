# 常用快捷键
在Android Studio中搜索某个快捷操作的快捷键及描述的关键字整理
1. hierarchy:层级相关，包括显示方法层级、显示类的继承关系层级
2. quick:预览(F1:显示注释文档，F2:显示方法定义)和快速操作相关
3. vcs:版本控制相关(ex：control + `:显示版本控制选项对话框)
4. move:整体移动，整体选中等
5. Analyze:静态分析工程结构和debug动态分析数据传递

## 查看相关
1. control + h:显示类的继承层级关系，焦点在某个类名时使用![control+H](/assets/Android_Studio/15224053584687.jpg)
2. control + option(alt) + h:显示方法调用层级，焦点在某个方法名时使用![control + option(alt) + h](/assets/Android_Studio/15224055481153.jpg)
3. shift + command + h:显示方法的继承实现层级，焦点在某个父类的非私有方法名时使用![](/assets/Android_Studio/15224055658064.jpg)
4. command+F12：显示文件结构，焦点在某个类文件时使用![](/assets/Android_Studio/15224055914971.jpg)
5. command + P:查看参数信息，焦点在方法调用处的方法签名上(从方法名开始到最后一个参数结束)使用![](/assets/Android_Studio/15224056699992.jpg)

## 编辑相关
1. shift + enter:在行中间效果shift + enter，等同在行末尾进行enter换行操作。![](/assets/Android_Studio/15224056876197.jpg)
2. option(alt) + shift + ↑/↓:上下移动当前行![](/assets/Android_Studio/15224056949548.jpg)
3. option(alt) + shift + ←/→:在父容器中左右移动单个元素![](/assets/Android_Studio/15224057079732.jpg)
4. command + shift + ↑/↓:上下移动选中块，移动行的加强版![](/assets/Android_Studio/15224057180798.jpg)
5. command + D :复制行或者选中块![](/assets/Android_Studio/15224057503173.jpg)
6. command + J :插入模板，模板的配置在 多行编辑：按住option(alt)键，鼠标拖动选框即可多行编辑![](/assets/Android_Studio/15224057639719.jpg)
7. command + option(alt) + M:提取方法（Extract Method） 描述：提取一段代码块，生成一个新的方法。当你发现某个方法里面过于复杂，需要将某一段代码提取成单独的方法时，该技巧是很有用的。 
调用：Menu → Refactor → Extract → Method <![](/assets/Android_Studio/15224058078687.jpg)
选中某段代码command + option(alt) + M --》![](/assets/Android_Studio/15224058145988.gif)


## 调试相关（debug）
1. 条件断点：通过右键断点，可以对一个断点加入条件。只有当满足条件时，才会进入到断点中。调试神技，只对自己关心的情况进行调试，不浪费时间。![](/assets/Android_Studio/15224058418841.gif)

2. 查看变量值：按住Alt点击想要查看的变量或者语句。如果想查看更多，则可以按Alt+f8调出Evaluate Expression窗口来自行输入自定义的语句。![](/assets/Android_Studio/15224058485546.gif)

3. 分析堆栈信息:Find Actions(ctrl+shift+a)输入”analyze stacktrace”即可查看堆栈信息。![](/assets/Android_Studio/15224058583921.gif)

4. 分析某个值得来源：Find Actions(ctrl+shift+a)输入”Analyze Data Flow to Here”，可以查看某个变量某个参数其值是如何一路赋值过来的。对于分析代码非常有用。![](/assets/Android_Studio/15224058652500.gif)

5. 点断表达式分析：option(alt) + F8,已断点时的各种条件来执行表达式，分析表达式结果  在debug时（不是debug无效）option(alt) + F8进行分析![](/assets/Android_Studio/15224058743895.jpg)

6. 断点日志：首先我们在想要输出信息的地方下一个断点；然后右键这个断点，在出现的设置框里面把这个断点的 suspend 属性设置为 False ，这样虽然叫做“断点”，但是并不会真正断下来，然后如图设置![](/assets/Android_Studio/15224059530613.jpg)
 开启debug后即可在Android studio下面的debug栏中Console查询日志，logcat里面是看不见的
![](/assets/Android_Studio/15224061858395.jpg)

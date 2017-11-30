首先需要安装JDK。一步一步来就行。注意选择安装路径，或者是默认路径即可。接下来进行Java环境变量配置。右击"计算机"，选择"属性"，在弹出的窗口中选择"高级系统设置"在弹出的"系统属性"窗口中的"高级"选项卡下，选择"环境变量"在弹出的"环境变量"窗口中，在"系统变量(S)"中设置3项属性，分别为：JAVA_HOME,PATH,CLASSPATH(大小写无所谓)，若已存在则点击"编辑"，不存在则点击"新建"。
新建(JAVA_HOME)
  变量名：JAVA_HOME
  变量值：E:\Program Files (x86)\Java\jdk1.7.0(该目录为JDK安装的路径，此路径下包括lib,bin,jre等文件夹)
编辑(CLASSPATH)，若没有该变量则需新建；CLASSPATH为java加载类(class or lib)路径，只有类在classpath中，java命令才能识别
变量名：CLASSPATH
变量值：%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar;(注：该变量值置于CLASSPATH即可；其中，变量值最后要加";")
 编辑(PATH),若没有该变量则需新建；PATH使得系统可在任何路径下识别JAVA命令。
变量名：PATH
变量值：.;%JAVA_HOME%\bin; (注：该变量值置于现有PATH值的前面)
检测是否安装成功：打开cmd，输入java——enter。出现Java的一些说明。安装成功。安装Eclipse。将下载的文件解压，打开Eclipse.exe,直接可以运行。注意：JDK版本要和Eclipse一样。要不然不能打开：出现“Failed to load the JNI shared library”。那就要重新下载相对应的版本。JDK版本要和Eclipse版本一样
电脑要配好了java环境。这是你能打开的前提。如果你已配好，接下来进入到你所要打开的jar文件所在的目录用cmd打开jar包同样可以运行。
打成一个.jar的文件，步骤如下： 
file->export->JARfile 
选择你要到处的项目 
选择你要导出的位置 
点击next 
点击next 
在面板最下面有一个select the class of the application entry point 
这个是选择该应用的进入点，也就是选择你的主类。 
点击finish 
不是在classes文件夹下，是在src文件夹下，src文件夹默认为源码（.JAVA）文件根目录，然后按包存放java文件。在这里面如果保存一个JAVA文件，eclipse就会自动将这个文件编译并保存class文件到classes文件夹下，同样按包存放。 
比如我在SRC文件夹下新建一个包com.test，在这个包类建一个类Test.java并保持，那么在classes文件夹下就会知道生成一个文件夹com，包含一个子文件夹test，test文件夹下就有一个名为Test.class的文件。 

配置、编译和安装该项目的说明信息，请在此填写和填写到代码仓库中。


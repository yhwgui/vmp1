python总的环境在E:\python_env1

然后用pycharm可以新建新的python工作空间，这样就可以切换不同的python版本和frida版本

这个就是一个工作空间：

![image-20221010152954343](pyhton环境问题总结.assets/image-20221010152954343.png)

这个是另一个工作空间：


![image-20221010153006642](pyhton环境问题总结.assets/image-20221010153006642.png)

然后要是想安装不同版本的frida就要找到该工作空间中的pip，在该工作空间利用pip中安装frida的不同版本

pip一般在这个路径;

![image-20221010153016364](pyhton环境问题总结.assets/image-20221010153016364.png)

然后直接在该路径下cmd打开，就可以使用pip为该工作空间安装对应的库，而不会影响环境变量中的frida版本，就可以做到不同版本之间的切换

然后在该工作空间中再找到frida的位置：

![image-20221010153026626](pyhton环境问题总结.assets/image-20221010153026626.png)

这就是该工作空间中安装的frida

![image-20221010153038403](pyhton环境问题总结.assets/image-20221010153038403.png)

E:\homework_python\venv\Scripts        frida工作空间

https://github.com/frida/frida/releases
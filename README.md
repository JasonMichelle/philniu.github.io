# Members: 
牛群杰 罗攀 陈福坤 李国胜
# Introduction
In the field of technology and image processing, hand/finger tracking is 
a high-resolution technique that is employed to know the consecutive position 
of the hands/fingers of the user and hence represent objects in 3D. In addition 
to that, the hand/finger tracking technique is used as a tool of the computer, 
acting as an external device in our computer, similar to a keyboard and 
a mouse.      
# Time Line
1.Creat github homepage
2.Android环境搭建      
# To Do List
1.分配任务，创建项目链接       
2.Android环境搭建
3.阅读参考文献，寻找合适算法，确定待实现方案   

# Reference
[1]. Fast and Robust Hand Tracking Using Detection-Guided Optimization, In CVPR, 2015.     
[2]. Accurate, Robust, and Flexible Real-time Hand Tracking, In CHI, 2015.      
[3]. Full DOF tracking of a hand interaction with an object by modeling occlusions and physical constraints, In ICCV, 2011.     

# Corresponding Video Links
http://v.youku.com/v_show/id_XNzk2NDM4NDIw.html?from=s1.8-1-1.2     
https://www.youtube.com/watch?v=FNQbGJyGAs8 (YouTube video)     
https://www.youtube.com/watch?v=xML2S6bvMwI(YouTube video)     
https://www.youtube.com/watch?v=eXktGa16yXk (YouTube video)     
https://www.youtube.com/watch?v=N3ffgj1bBGw (YouTube video)    

# Android环境搭建
随着移动互联网的火热发展和移动端迅速崛起，Android的应用开发和IOS应用开发是非常有必要了解学习的。
本文就是为了从最基本的开始介绍Android开发。在整个文档中，我会简单介绍环境搭建、最小案例演示、JNI开发和集成OpenCV。      
**工具**        
⒈JDK    
⒉Eclipse   
⒊Android SDK   
⒋Android NDK   
⒌OpenCV-2.4.11的AndroidSDK      

**1. JDK安装和Java环境配置**      
下载地址：http://www.oracle.com/technetwork/java/javase/downloads/index.html
环境配置，截图如下：   
JAVA_HOME   
![](https://github.com/philniu/philniu.github.io/blob/master/1.png)           
PATH     
![](https://github.com/philniu/philniu.github.io/blob/master/2.png)       
CLASSPATH    
![](https://github.com/philniu/philniu.github.io/blob/master/3.png)                       
Win+R，输入cmd，输入java 和 javac 检测环境是否配置成功。成功的话会出现很多输出      

**2. Eclipse下载安装**     
下载地址：http://www.eclipse.org/downloads/    
选择适用于Android开发的IDE      
然后像普通的windows软件一样的安装。图片就不截了。    

**3. Android相关下载**                
在这里，我不得不说一句。墙内的我们，学个开发就这么难吗？   
还有国内有个不错的论坛，所有android需要的都可以去那里下载：   
网址：http://www.apkbus.com/thread-252748-1-1.html    
还有就是，作为新手。我建议，直接下载我给的网址里面的一个名叫ADT Bundle的文件，也就是说不需要去进行第二步。下载完成以后，解压就可以直接使用。不过，这个集成好的里面的Android版本不是最新的，并且如果想更新的话也是相当的麻烦。个人建议不要更新。凑合用，等理解深刻了，完整的走一趟安装流程。     

**4. Android SDK和NDK配置**         
打开Eclipse，设置工作空间。      
Window—>Preference看如下截图：     
![](https://github.com/philniu/philniu.github.io/blob/master/4.png)                   
![](https://github.com/philniu/philniu.github.io/blob/master/5.png)                        

**5. 配置OpenCV-2.4.11**        
下载地址：http://opencv.org/downloads.html    
选择相应的版本。    
解压文件，然后把文件里面的一个名叫sdk的文件夹复制到工作空间。        
然后，导入这个sdk项目到Eclipse作为一个library。      
![](https://github.com/philniu/philniu.github.io/blob/master/6.png)              
![](https://github.com/philniu/philniu.github.io/blob/master/7.png)                 

**6. 创建一个简单地使用OPenCV的本地代码实现图片灰度化的项目。**                        
![](https://github.com/philniu/philniu.github.io/blob/master/8.png)                                                 

**7. 备注**                    
后续更新，敬请期待。                

       





﻿# OpenCV-Tensorflow
使用OpenCV+Tensorflow实现游戏中车辆的自动驾驶

说明：
Preliminary——接下来要做的代码
Train——用于生成训练数据
Tutorial——最开始的能简单的实现功能
MOD_test——现在正在改进的有问题代码


12-04
使用了新的屏幕抓取方式，提高了帧率，建立了training_data.npy，感觉优点难度，应该看一些关于神经网络训练的基础视频（推荐B站上莫凡的视频）
打算再补一补关于Python基础的书籍
今天就先这样吧
2018-12-04   21:25   下班

12-05
使用直方图反向投影bitwise_and()，选出路面范围，让车道更加明显，我觉的先识别这一块做好了，在训练的时候数据会更加准确，磨刀不费砍柴工，对不对~
接下来就是解决划线的问题，继续啃代码吧~
2018-12-05   22:20   下班

12-07
划线的问题还是没有解决，现在那两条线跳来跳去，头疼......
今天跑了一下代码，发现识别效果好了，但是图像的帧数变低了。这是由于在利用hsv做反向投影时，计算量增加了导致的，但是也没太大的影响
改天有时间再捋捋代码
2018-12-07  20:36    下班



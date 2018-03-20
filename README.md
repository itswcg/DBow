## DBow2 
Fork <https://github.com/dorian3d/DBoW2>  

#### 做了一些改动：
* 创建离线词典(txt格式)，能直接应用于ORB SLAM2
* 能直接用的DBow3，在[DBow3](https://github.com/itswcg/DBow/tree/DBow3)分支
* 详细说明：<https://itswcg.com/2018-03/orb-slam2-voc.html>

#### 使用
```
$ git clone git@github.com:itswcg/DBow.git
$ mkdir build
$ cd build
$ cmake ..
$ make
$ ./voc
```

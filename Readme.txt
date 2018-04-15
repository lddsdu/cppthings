关于动态链接库，静态链接库，动态运行库
现在是18.4.15,intel caffe给我带来了巨大的痛苦，现在还很不清楚linux下的动态，静态运行库
.so        .a
动态库      静态库

库文件一般放在/usr/lib /lib 目录下面
xxx.a      xxx.so.major.minor
静态	   动态   主版本 副版本

可以使用ldd（这个不是我名字的缩写么！！！） xxx.so.majo.minor来查看所依赖的库

直接编译得到   gcc hello.h hello.c main.c



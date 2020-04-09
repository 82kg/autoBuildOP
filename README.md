# 如何下载固件
1、点开Actions 
2、找到最新的一条点开即可下载。

![插件](https://raw.githubusercontent.com/82kg/autoBuildOP/master/3.png)

# 如何使用本项目的编译方法
1、编辑下workflows里的Build_OP_SSH.yml，改第一行的注释日期，commit一下，就开始编译了。
   commit的title 可以写本次编译的X86固件还是K2P固件，内容不用写

# 如何进入SSH 自定义make menuconfig

如下图，当运行到 SSH connection to Actions 时，控制台日志会输出 链接地址，用浏览器打开即可，编译进程会阻塞30分钟，直到你 exit;
打开链接后，屏幕一片黑？  只要  ctrl+c ，再 cd openwrt  进入编译目录后，即可 make menuconfig


![插件](https://raw.githubusercontent.com/82kg/autoBuildOP/master/ssh.png)

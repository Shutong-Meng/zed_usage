# zed_usage
How to use zed first time  

显卡GTX1050Ti  ubuntu16.04  

1.显卡驱动安装  
sudo add-apt-repository ppa:graphics-drivers/ppa && sudo apt update  
使用系统设置面板更换显卡驱动，确认更改，等待重启  
版本号:410.78  (亲测390不可)  

2.cuda9.0 runfile安装  
  第一个选no,后面选yes  

3.zed SDK 官网下载　run  
  /usr/local是默认安装路径  
  其中zed/tools下diagnostic可以检测问题，explorer可以看到画面  

4.clone官网ros包，工作空间下编译  
roslaunch zed_wrapper zed.launch 启动zed节点  
roslaunch zed_display_rviz display.launch 可视化


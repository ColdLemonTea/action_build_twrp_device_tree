# TWRP Device Tree生成工具
- 这个工具怎么用？
- 1.首先你要搞到你的设备任意一个可以开机系统的
- boot.img AB分区 
- recovery.img 除了AB分区以外的所有分区 

-----

- 2.将这个仓库fork到你的用户名下

-----

- 3.将recovery.img或boot.img上传至一个可以提供直链下载的位置，这里我推荐直接将img文件上传至Release，编辑tag为images

-----

- 4.点击Actions － Make TWRP Device from Release － run workflow，然后在那个文本框里输入你上传img的名字

-----

 - 5、填写完成后点击 'Run workflow' 开始运行

-----
## 编译结果
- 可以在 [Actions]artifacts 下载

## 看不懂想要图文教程?
- 看看隔壁那个用github编译twrp教程，与这个大同小异端
- https://github.com/Xpsoted/Action-Recovery-builder/blob/main/README.md

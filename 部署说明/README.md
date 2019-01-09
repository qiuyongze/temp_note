全部步骤：
0.
把网络dns 什么的都弄好 保证能上网 而且下载机和处理机互通
/etc/network/interfaces
dns-nameservers 8.8.8.8

1.
更换ubuntu源（笔记本位置：学习 linux）

2.
搭建nfs（笔记本位置：学习 linux） 笔记中是搭建一台的步骤，最后搭成架构nfs.png图的样子

3.
mount --bind目录（永久）（可省略 这一步是因为我挂载的目录磁盘不够了 所以做一个目录挂载，其实就是超链接） （笔记本位置：学习 linux）

4.
redis部署和跨机器测试（笔记本位置：学习 linux）

5.
数据库拷贝和导入（笔记本位置：学习 数据库）

6.
按照 目录结构.txt 把代码和东西都拷贝进去机器

7.python库安装
pip install pymysql multiprocessing pytz threadpool datetime redis 
pybgpstream安装（笔记位置：BGP pybgpstream安装）

8.所有机器运行/root下的reboot.py

9.启动网页（apache加laravel 这个不是我弄的，问秦师兄）




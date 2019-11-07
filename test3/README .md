1、在CentOS环境下安装Docker

验证docker是否安装成功并启动，得到如下输出

![](./images/12.png)

还可以查看一下Docker的版本信息

![](./images/13.png)

2、加载Docker的CentOS镜像

![](./images/14.png)

提交新的镜像并推送至Docker Hub

![](./images/15.png)

![](./images/16 .png)

3、拉取CentOS镜像后运行一个容器实例

![](./images/17.png)

在容器实例中安装WordPress并制作成镜像，在8081端口映射公网IP：106.54.15.12

访问时在公网IP地址后面加：8081  即可访问，一下为截图

![](./images/18.png)

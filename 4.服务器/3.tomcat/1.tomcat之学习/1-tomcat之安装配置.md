总操作流程：
- 1.[下载安装](#tomcat-01)
- 2.[配置](#tomcat-02)
- 3.[测试](#tomcat-03)

----------

# <a name="tomcat-01" href="#" >下载安装</a>

[![](https://img.shields.io/badge/apache--tomcat-8.0.3-green.svg "apache-tomcat 8.0.3")](https://pan.baidu.com/s/1baB4TzFkYR2TcnB-EydYHA)


上传linux

```shell
cd /usr/local

tar zxvf apache-tomcat-8.5.38.tar.gz

mv apache-tomcat-8.5.38 tomcat

```
# <a name="tomcat-02" href="#" >配置</a>

>1、配置变量环境
```shell
vim /etc/profile
```

```shell
#set tomcat environment
TOMCAT_HOME=/usr/local/tomcat
PATH=$PATH:$TOMCAT_HOME/bin:$TOMCAT_HOME/lib
export PATH TOMCAT_HOME
```

```shell
source /etc/profile #让修改生效

catalina.sh version #查看版本
```

# <a name="tomcat-03" href="#" >测试</a>
```shell
cd ~

cd /usr/local/tomcat/bin

./startup.sh

```

>其他命令
```shell
cd ~

cd /usr/local/tomcat/bin

./shutdown.sh #关闭

 ps -ef|grep java  # 查询状态
```
![](image/1-1.png)

本页目录：
- 1、[下载安装](#Oracle-01)
- 2、[修改配置](#Oracle-02)
- 3、[使用navicat premium链接](#Oracle-03)

***

# <a name="Oracle-01" href="#" >下载安装</a>

> 1、下载
[![](https://img.shields.io/badge/官网-下载-red.svg "官网 下载")](https://www.oracle.com/downloads/index.html#database)

![](image/1-1.png)

![](image/1-2.png)

![](image/1-3.png)

> 2、安装

![](image/1-4.png)

![](image/1-5.png)

```
密码：123456
```
![](image/1-6.png)

![](image/1-7.png)

![](image/1-8.png)

![](image/1-9.png)

![](image/1-10.png)

![](image/1-11.png)

![](image/1-12.png)

![](image/1-13.png)

![](image/1-14.png)

![](image/1-15.png)

![](image/1-16.png)

![](image/1-17.png)

# <a name="Oracle-02" href="#" >修改配置</a>

>修改tnsnames.ora文件

![](image/1-18.png)

> 修改listener.ora文件

![](image/1-19.png)

可以添加
```
    (SID_DESC =
      (GLOBAL_DBNAME = ORCL)
      (ORACLE_HOME = C:\Software\Oracle\product\11.2.0\dbhome_1)  
      (SID_NAME = ORCL)
      (ENVS = "EXTPROC_DLLS=ONLY:C:\Software\Oracle\product\11.2.0\dbhome_1\bin\oraclr11.dll")
    )
```

> 重置监听程序

![](image/1-20.png)

![](image/1-21.png)

![](image/1-22.png)

![](image/1-23.png)

![](image/1-24.png)

![](image/1-25.png)

![](image/1-26.png)

![](image/1-27.png)

![](image/1-28.png)

![](image/1-29.png)

![](image/1-30.png)


# <a name="Oracle-03" href="#" >使用navicat premium链接</a>

![](image/1-31.png)

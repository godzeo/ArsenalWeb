# 0x00 武器库

前后端分离项目：https://github.com/godzeo/ArsenalWeb

本项目是一个红队**武**器库平台，包含常用的一些红队功能，也会集合一些其他好用的工具到里面

> 正在开发中....

暂时不全部开源，因为还有很多bug和代码质量有点烂.....



> 开发

前后端分离项目：

后端：采用django+django-rest-framework,

前端采用vue+ElementUI

JWT认证,支持swagger



> 必要环境

Redis+npm+Python3.7



# 0x02 组件（功能）

- 红队最新漏洞共享 （markdown格式）
- 企业信息收集（前端界面简陋，数据源：企查查）
- 单个网站漏洞扫描 
- 漏洞扫描 （大规模资产漏扫扫描）
- 其他系统功能

TODO

- 缺少一个数据清洗

  





大规模资产漏扫扫描流程：

- 根域名收集 （可借助企业信息收集模块）

- 子域名收集 

- 被动信息收集（fofa，sodan）

- IP地址解析 

- 端口指纹扫描 （web-top 20）

- WEB服务探测  

- waf检测

- 重要应用指纹识别（指纹识别模块）

- 自建POC扫描（想兼容最新发现goby的poc格式-未完成）

- 漏洞扫描引擎（仅有第三方）

  

​    

注：过程要尽量减少bug，否则就会是指数级的任务爆炸



# 0x03 已完成展示



登陆

![image-20210507181700790](https://gitee.com/godzeo/blogimg/raw/master/img/20210507181735.png)



### 主菜单

![image-20210712121348583](https://gitee.com/godzeo/blogimg/raw/master/img/20210712121348.png)





### 企业信息收集模块

![image-20210712155401571](https://gitee.com/godzeo/blogimg/raw/master/img/20210712155401.png)

excl数据：

![image-20210712155432687](https://gitee.com/godzeo/blogimg/raw/master/img/20210712155432.png)



### 漏洞分享

![image-20210712155932031](https://gitee.com/godzeo/blogimg/raw/master/img/20210712155932.png)

![image-20210712160330176](https://gitee.com/godzeo/blogimg/raw/master/img/20210712160330.png)



### 漏洞扫描主域名模块

![image-20210622101727981](https://gitee.com/godzeo/blogimg/raw/master/img/20210622101728.png)

![image-20210622101946573](https://gitee.com/godzeo/blogimg/raw/master/img/20210622101946.png)

![image-20210710180245244](https://gitee.com/godzeo/blogimg/raw/master/img/20210710180245.png)



### 漏洞扫描子域名模块

![image-20210622101810164](https://gitee.com/godzeo/blogimg/raw/master/img/20210622101810.png)



### 全部漏洞信息

![image-20210622101856129](https://gitee.com/godzeo/blogimg/raw/master/img/20210622101856.png)





### 其他

![image-20210712155639774](https://gitee.com/godzeo/blogimg/raw/master/img/20210712155639.png)

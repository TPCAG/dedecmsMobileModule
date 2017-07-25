织梦dedecms 移动模块
============
@(PHP)[织梦]

[toc]

###### 在原版本基础上兼容了PHP7,同时将伪静态去除。
###### UTF-8动态版本。模板基于妹子UI控件~


* `PHPActionModule`文件夹代表动态版本，不含xml插件


![](http://img.my.csdn.net/uploads/201504/23/1429718923_4661.gif-thumb.jpg)

有问题上博客提问：http://helonghua.com/2015/03/23/dedecms-wap/

## 动态版本PHPActionModule

动态版本位于文件夹PHPActionModule
目录结构：

	-mobile.php
	-include/
	-templets/

**注意： 这里只提供了源代码，需要你自行创建插件。**

### 安装
1. clone源码
2. 上传`PHPActionModule`文件夹内内容至dedecms根目录
3.  登陆织梦后台
	模块-->模块生成向导-->参照图片填写并提交
    ![](https://i.loli.net/2017/07/25/59772cf827f3f.png)
4. 动态版本，不需要后台手动控制，我去掉了原版的rewrite
如果有伪静态之需要可以参照修改然后参照原版的配置规则，选择符合自己主机情况去配置。
---------------
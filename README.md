# 微信直播工具获取弹幕助手

## pip加速

`pip -v config list`如果没找到pip.ini文件，那么可以自己创建，步骤如下：
在pip.ini中加入如下代码

```shell
[global]
index-url=http://mirrors.aliyun.com/pypi/simple/
[install]
trusted-host=mirrors.aliyun.com
```

查看是否配置成功

```shell
pip -v config list
```

## 一次性安装requirements.txt里面所有的依赖包

```shell
pip install -r requirements.txt
```

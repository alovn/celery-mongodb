# celery-mongodb

此项目用于解决 celery 4.2.1 版本中，MongoDB 作为 backend 时，频繁对 MongoDB 创建连接的问题。

将mongodb.py文件替换到以下路径:
```
/usr/local/lib/python2.7/site-packages/celery/backends/mongodb.py
```
具体要依python、celery 安装的目录而定。
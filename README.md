# 安装依赖

Python版本：3.6.x+

异步框架aiohttp：

```bash
$ pip3 install aiohttp
```

前端模板引擎jinja2：

```bash
$ pip3 install jinja2
```

MySQL 5.x数据库

MySQL的Python异步驱动程序aiomysql：

```bash
$ pip3 install aiomysql
```

## 项目结构

```
awesome-python3-webapp/  <-- 根目录
|
+- backup/               <-- 备份目录
|
+- conf/                 <-- 配置文件
|
+- dist/                 <-- 打包目录
|
+- www/                  <-- Web目录，存放.py文件
|  |
|  +- static/            <-- 存放静态文件
|  |
|  +- templates/         <-- 存放模板文件
|
+- ios/                  <-- 存放iOS App工程
|
+- LICENSE               <-- 代码LICENSE
```


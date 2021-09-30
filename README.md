TFH Project
=========================
# 介绍
TFH Project是一个让Typecho在Heroku上使用的项目
# 如何工作？
使用app.json设置Typecho，composer.json和composer.lock配置运行环境
# 如何安装？
首先导入到heroku<br>
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)<br>
随后安装PostgerSQL插件创建数据库<br>
https://elements.heroku.com/addons/heroku-postgresql<br>
打开管理面板，然后打开导航栏中的 Settings，下面有 Config Vars 项，打开就会显示PostgerSQL 数据库的相关信息。类似下表
![](https://phyllisjohnson.herokuapp.com/TFH-README/1.png)

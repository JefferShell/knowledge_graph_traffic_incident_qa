## 项目简介

本项目是一个基于知识图谱的交通事故领域问答系统。该系统提供了用户友好界面和基于自然语言的查询功能，可以方便用户对于交通事故相关知识的获取。

**系统目标：**

- 以知识图谱形式存储交通事故相关数据。
- 利用自然语言处理技术进行问题分析和答案生成。
- 提供用户友好的界面，方便用户进行查询和分析。


## 主要功能

- 数据初始化：支持将CSV文件导入Neo4j数据库。
- 节点数据管理：提供基于业务逻辑的节点数据处理功能。
- 关系数据管理：提供建立和管理节点之间的关系数据的功能。
- Web交互界面：提供用户友好的界面进行数据的查看、查询和操作。
- 问答系统：基于自然语言识别技术，提供基于知识图谱的答案。


## 技术架构

本系统主要依赖以下技术：

- **后端框架：**Django
- **数据库：**Neo4j
- **自然语言处理库：**jieba


## 使用说明

1. 下载项目代码并解压缩。
2. 安装依赖项：`pip install -r requirements.txt`
3. 启动项目：`python manage.py runserver`
4. 访问项目界面：`http://127.0.0.1:8000`


## 联系方式

微信号：zt745324325
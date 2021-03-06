# [01.mongoDB的安装](01.mongoDB的安装.md)
- [1. 在主机安装和启动mongodb](01.mongoDB的安装.md/#1-在主机安装和启动mongodb)
  - [(1) 安装mongodb](01.mongoDB的安装.md/#1-安装mongodb)
  - [(2) 启动mongodb](01.mongoDB的安装.md/#2-启动mongodb)
  - [(3) 连接mongodb](01.mongoDB的安装.md/#3-连接mongodb)
  - [(4) 允许外网访问mongodb](01.mongoDB的安装.md/#4-允许外网访问mongodb)
  - [(5) 查看mongodb连接数](01.mongoDB的安装.md/#5-查看mongodb连接数)
- [2. 在docker安装mongodb](01.mongoDB的安装.md/#2-在docker安装mongodb)
  - [(1) 默认配置启动](01.mongoDB的安装.md/#1-默认配置启动)
  - [(2) 自定义配置文件启动](01.mongoDB的安装.md/#2-自定义配置文件启动)
  - [(3) docker-compose命令启动，同时启动mongodb管理界面服务](01.mongoDB的安装.md/#3-docker-compose命令启动同时启动mongodb管理界面服务)

# [02.mongoDB账号管理](02.mongoDB账号管理.md)
- [1. 创建管理员](02.mongoDB账号管理.md/#1-创建管理员)
- [2. 创建自定义用户](02.mongoDB账号管理.md/#2-创建自定义用户)
- [3. 查看已经创建的用户](02.mongoDB账号管理.md/#3-查看已经创建的用户)
- [4. 删除用户](02.mongoDB账号管理.md/#4-删除用户)

# [03.mongoDB增删改查操作](03.mongoDB增删改查操作.md)
- [1. 库和集合的基础命令](03.mongoDB增删改查操作.md/#1-库和集合的基础命令)
  - [1. 库级命令](03.mongoDB增删改查操作.md/#1-库级命令)
  - [2. 表(集合)级命令](03.mongoDB增删改查操作.md/#2-表集合级命令)
- [2. insert插入数据](03.mongoDB增删改查操作.md/#2-insert插入数据)
  - [1. 增加一个文档](03.mongoDB增删改查操作.md/#1-增加一个文档)
  - [2. 一次增加多个文档](03.mongoDB增删改查操作.md/#2-一次增加多个文档)
- [3. remove删除数据](03.mongoDB增删改查操作.md/#3-remove删除数据)
- [4. update修改数据](03.mongoDB增删改查操作.md/#4-update修改数据)
  - [1. 赋值表达式](03.mongoDB增删改查操作.md/#1-赋值表达式)
  - [2. 修改选项](03.mongoDB增删改查操作.md/#2-修改选项)
- [5. query查询](03.mongoDB增删改查操作.md/#5-query查询)
  - [1. 字段值查询](03.mongoDB增删改查操作.md/#1-字段值查询)
  - [2. 范围查询](03.mongoDB增删改查操作.md/#2-范围查询)
  - [3. 集合查询](03.mongoDB增删改查操作.md/#3-集合查询)
  - [4. 逻辑查询](03.mongoDB增删改查操作.md/#4-逻辑查询)
  - [5. 元素运算符查询](03.mongoDB增删改查操作.md/#5-元素运算符查询)
  - [6. 其他常用查询](03.mongoDB增删改查操作.md/#6-其他常用查询)

# [04.索引](04.索引.md)
- [1. 普通索引](04.索引.md/#1-普通索引)
	- [1. 单列索引](04.索引.md/#1-单列索引)
	- [2. 多列索引](04.索引.md/#2-多列索引)
	- [3. 子文档索引](04.索引.md/#3-子文档索引)
- [2. 唯一索引](04.索引.md/#2-唯一索引)
- [3. 稀疏索引](04.索引.md/#3-稀疏索引)
- [4. 哈希索引](04.索引.md/#4-哈希索引)
- [5. 重建索引](04.索引.md/#5-重建索引)
- [6. 删除索引](04.索引.md/#6-删除索引)
- [7. 查看索引和执行计划](04.索引.md/#7-查看索引和执行计划)

# [05.数据备份与恢复](05.数据备份与恢复.md)
- [1. mongoexport导出json/csv结构化数据](05.数据备份与恢复.md/#1-mongoexport导出jsoncsv结构化数据)
- [2. mongoimport导入json/csv结构化数据](05.数据备份与恢复.md/#2-mongoimport导入jsoncsv结构化数据)
- [3. mongodump导出二进制数据](05.数据备份与恢复.md/#3-mongodump导出二进制数据)
- [4. mongorestore导入二进制数据](05.数据备份与恢复.md/#4-mongorestore导入二进制数据)

# [06.mongoDB的其他](06.mongoDB的其他.md)
- [1. 获取mongodb状态信息](06.mongoDB的其他.md/#1-获取mongodb状态信息)
- [2. 非正常关闭mongodb导致无法启动的解决方法](06.mongoDB的其他.md/#2-非正常关闭mongodb导致无法启动的解决方法)
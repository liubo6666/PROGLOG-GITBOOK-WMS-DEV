> 代码生成器生成Model

---

* 连接持久层即Oracle实体库

  1\)进入代码生成器模版目录：\Doc\框架手册\开发手册\代码生成\Templates\Model

  2\)右键模版“ORMModelTemplate.cst”，执行Execute（安装CodeSmith后才可以直接运行）

![](/assets/CodeSmithUse/01.png)

3\)在打开的模板界面，点击SourceTable扩展项，在新的Table Picker界面上选择Data Source扩展项，在新的Data Source Manager中添加实体对应的数据源

![](/assets/CodeSmithUse/02.png)

4\)在数据源管理界面中，按照下图的步骤：1给数据源命名;2选择数据驱动OracleSchemaProvider;3配置数据源连接字符串;4实体库对应的本地tns配置名;5数据库用户名;6数据库密码;7连接测试;8测试成功。

![](/assets/CodeSmithUse/03.png)

注：数据库连接配置只有在第一次时需要。

* 选择Model对应的实体表生成Model类
1\)在配置完毕的Table Picker界面上选择，本次需要生成的实体

![](/assets/CodeSmithUse/04.png)

2\)选择了实体表，输入Model的命名空间，点击Generate

![](/assets/CodeSmithUse/05.png)

3\)将生成的Model类保存到对应的项目文件夹中

![](/assets/CodeSmithUse/06.png)


* 生成Model并加载到项目中




# 测试
### 按岗位分
* 黑盒测试：测试业务逻辑
* 白盒测试：测试逻辑方法
### 按测试粒度
* 方法测试 function
* 单元测试 unit
* 集成测试 integration
* 系统测试 system
### 按暴力程度
* 冒烟测试 smoke
* 压力测试 pressure
### monkey

# 单元测试框架
* 可以直接云心代码
* 需要指定指令集和定义使用的类库

# SQLite数据库

# ListView
* 用来显示列表
* 每一行内容称为一个条目
* ListView的每一个条目都是一个View对象
* 不同布局文件中，资源id可以相同，找的时候注意设置在哪个布局中找
* 只要内存中有条目缓存，在新的条目出现时，就会使用缓存
### MVC
* M：模型层
	* javaBean
	* personList
* V：视图层
	* jsp
	* ListView
* C：控制层
	* servlet
	* Adapter

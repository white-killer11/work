# 洪天乐的博客系统

项目架构:

* 前端:Bootstrap + jquery 
* 后台:Nodejs + express

项目文件说明：

config  文本编辑类的相关操作和限制（包括邮箱的限制和错误文件的检测）

controller 登录登出的查询操作和对博客篇章的查询操作，并将相关的数据返回

models 文件连接和部分全局设定的js文件

views前端html网页的各个页面的集合

目前实现了:

1. 用户登录、注册、验证、发表文章、退出、权限控制等功能
2. 使博客支持了Markdown语法，发表文章更简单^_^!~~
3. 用户文件、图片的上传功能
4. 实现了通过用户查找文章页面,以及通过点击文章查询到某文章页面的需求
5. 实现了不同的用户通过session验证修改或删除自己的文章
6. 实现文章留言板功能使用mongoose的Model.updat({查询对象参数},
7. 实现了文章按照发布日期归档功能
8. 实现了文章标签功能以及新增标签页面
9. 实现了文章Pv统计,以及用户回复统计
10. 新增文章索引功能,查询文章 
11. 新增友情链接
12. 新增404页面
13. 新增用户头像 
14. 实现转载记录
15. 添加日志记录

# 功能页面展示

登录界面

![](C:\Users\Administrator\Desktop\readme\4.png)

注册界面

![](C:\Users\Administrator\Desktop\readme\5.png)

首页

![](C:\Users\Administrator\Desktop\readme\7.png)

查看博文

![](C:\Users\Administrator\Desktop\readme\8.png)

查看博文的tag

![](C:\Users\Administrator\Desktop\readme\6.png)

写博文

![](C:\Users\Administrator\Desktop\readme\2.png)

插入图片

![](C:\Users\Administrator\Desktop\readme\10.png)

搜索博文

![](C:\Users\Administrator\Desktop\readme\9.png)

撰写评论

![](C:\Users\Administrator\Desktop\readme\1.png)

# 编程过程

1，获取项目，跑通后进行first commit

2，修改后进行第二次commit
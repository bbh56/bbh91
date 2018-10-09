                             1.原系统介绍
项目名：为社会人士提供温暖

目的： 为那些环卫工人以及一些生活水平不是很好的人提供一些温暖。

本项目的意义在于锻炼团队的scrum能力，加强团队合作能力。确定本项目采用的技术方向：本项目整体采用java web 实现，前端采用HTML+CSS+JavaScript实现，后端采用JSP+Servlet实现。

2.模块拆分
    模块大致可分为3个模块:卡户模块，产品模块，购买模块
    1）卡户模块主要是那些符合条件的人去登录注册卡的功能。
    2）产品模块是在用户购买或者补充货源后可以及时更新库存，以免出现没有货物的下现象出现。
    3）购买模块是用户用卡在贩卖机上识别出来是温暖卡之后选择自己想要的东西，机器自动掉下所需产品，具体可以参考自动贩卖机的售卖情况。

3.接口说明
登录接口：就是识别卡的软件
货物查询接口：暂无  
参数	      说明
cshopping   所查找的东西
cnum        货物数量

4.数据库设计
    由于以前开发没有需要使用数据库的地方，所以没有将数据存储到数据库，在后续的开发中可能需要存储登录用户的信息以便后续功能可以直接使用本地的数据而不是每次都使用接口去解析。例如用户登录时如果数据库中没有记录则去接口查询，然后添加进数据库，下次再登录时直接从数据库查询，而不必走登录接口提高响应速度。

5.参考资料
[1] layui 经典模块化前端框架 https://www.layui.com/doc/

QQBot
-----
使用非公开协议(web.qq.com)的QQ机器人


状态
-----
可行性测试阶段，应该有戏

关于
----
不久前在一个比特币群中发现了有群机器人的存在，管理员可以通过它管理其他成员，群成员也可通过各种指令了解各平台比特币的市场行情。另外惊奇的是居然能自动踢掉刷屏的人，潜力无限，骚动不止！

> 2013.12.28  

* 19:43 搜索了下果然已有好多轮子，但几乎所有的都是闭源付费以及是基于win系统。所以决定测试下基于webQQ协议的可能性。  
* 20:13 有点急功近利了，直接用coffeescript编码有点搞不定的感觉。看会Coffee和node的语法和api  
* 21:18 基本语法和http测试完成 :smile:  

> 2013.12.29   

* 10:23 昨晚一直卡在登录账户验证处，调试到凌晨终于通过登录验证的第一个环节。PS.使用coffee写代码还真是蛮清爽的
* 15:07 去了趟医院，怎么就突然感冒咳嗽头晕了。成功搞定node http post以及获取到qq登录最后一步token。睡会会。  
* 19:43 https://code.google.com/p/mingqq/ 发现了一款开源的webqq协议的win客户端，看截图完成度相当高。对了增加了验证码的支持
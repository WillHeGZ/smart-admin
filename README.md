#### 简介
SmartAdmin由河南·洛阳 [1024创新实验室](https://www.1024lab.net/) （钢圈网旗下）团队研发的一套互联网企业级的通用型中后台解决方案！ 使用最前沿的前后台技术栈 SpringBoot 和 Vue，开发出的一套简洁、易用的中后台系统，为广大开发者们节省时间！

我们希望用一套漂亮优雅的代码和一套整洁高效的代码规范，让大家在这浮躁的代码世界里感受到一股把代码写好的清流！ 同时对我们而言，这不仅是一套系统，也是我们团队的一次自我审视与成长。身为开发者，我们希望在一次次的披荆斩棘之后，能收获和留下些什么，这正是我们存在的意义！

保持谦逊，不断学习，热爱代码，热爱生活 !

#### 在线预览

在线预览： [http://smartadmin.1024lab.net](http://smartadmin.1024lab.net)

演示用户1：demo 密码：123456

演示用户2：demo2 密码：123456

#### 疑惑
有人问：又是个“轮子”？ 轮子靠谱吗？为什么要选择你这个轮子？

**1024Lab**回答：它不是“轮子”，而是一套代码，一套规范，一套开发理念，一套思想。

#### 理念与思想
- 我们分享的不是代码，不是徒劳无功的堆砌功能，而是你必须的基础功能，比如Vue前端权限、心跳、动态Reload、Keepalived标签页等等，可能还有一些正是你当前项目中缺失的功能。
- 我们分享的不仅有代码，还有一套经过几十人验证过的前、后端代码。细节决定成败，好的规范能让我们敲下的每行代码更铿锵有力！
- 我们推崇高质量的代码，身为开发，代码即利剑，键盘上一套行云流水，宛如侠客，事了拂衣去，深藏身与名。
- 我们推崇团队的高度配合默契、互相帮助，从不加班，而不是一看到别人的代码就头皮发麻，留其996.ICU
- 我们热爱编程，热爱代码，保持谦逊，不断学习，快乐工作，热爱生活。
- **请相信并认真阅读下面的每一个点，让你感受不一样的编码体验**

#### 技术体系

- 前端：Vue + Vue-Router + Vuex + ViewUI(iview) + vue-enum
- 后端：SpringBoot2 + Mybatis-plus + jwt + druid + mysql
- 前端代码规范smart-front-standard -guide
- 基于阿里规范之上的后端规范smart-backend-standard-guide


#### 前端特点
- 高质量的代码、代码结构、和代码注释
- 漂亮的UI，菜单栏、标签页等等
- 优化基于Keepalive的标签页，做到标签页该缓存的时候缓存，比如左右切换等，不该缓存的时候不缓存，比如新建，表单提交结束等
- 前端常量维护: vue-enum，拒绝出现魔法数字，代码不可维护的现象
- 全新的基于前端的权限设计（忘掉传统的权限设计吧，已经不适合这个前端时代）
- 体验、交互更好用的员工、部门、角色、菜单管理
- 基于websocket的在线人数
- 支持一级、二级、三级菜单
- 支持菜单搜索功能
- 其他功能：邮件、富文本、消息、系统配置等等
- 定时任务
- 写不完了，太多好的细节需要你的发现

#### 后端特点
- 高质量的Java代码、分包结构、和代码注释
- 业内独创的请求返回码维护，非常值得一看
- 基于一个注解和controller的权限设计放弃更复杂的shiro
- 完整的数据权限支持
- 四层架构（controller, service, manager, dao）
- 代码阅读性强、扩展性极高的员工、部门、角色、菜单管理
- 基于LRU策略的内存级权限缓存
- 自定义枚举表单验证，BigDecimal验证等
- 配合前端vue-enum的swagger文档注解
- 心跳服务，让你发现有哪些机器再跑，哪些人在偷偷的跑你的Job
- 自定义的quartz job添加和修改，方便测试人员测试
- smart-reload，为系统预留钩子，动态加载，在不重启程序前提下执行一些代码，你懂的
- 其他功能：邮件、富文本、消息、系统配置等等
- 以上只是一些举例，更多灿若繁星的惊喜和细节，等待着你的发现！

#### 前端代码规范
- 文件、文件夹、目录结构、组建、变量等等怎么命名
- html、css、less等如何规范
- vue项目目录结构如何划分
- router和store该怎么划分扩展性更好
- vue组件规范该选择哪些
- 以及更多，数不胜数让你觉得实用，同时身心愉悦的规范

#### 后端代码规范
- 好多种分包，哪种更合理一些
- 四层架构（controller, service, manager, dao） 是什么，为什么要有四层
- 各个层的代码该怎么写才能让团队配合默契，高度一致
- vo, bo, dto, entity 怎么区分和使用
- spring的 @Transactional 你用对了吗
- 方法参数个数、注释、todo这些也要有规范，你遵守过吗
- 以上举例，只是沧海一粟，更多的细节等待你的发现！

ps：以上规范基础都是以团队出发，让团队开心快乐的写代码，而不是为了代码规范而规范。

#### 联系我们
[1024创新实验室](https://www.1024lab.net/)

1024Lab官方微信号：

![](http://cdn.1024lab.net/img/smart-admin/1024lab-wechat.png)

SmartAdmin 官方QQ群：914442584

![](http://cdn.1024lab.net/img/smart-admin/smart-admin-qq-group.png)

官方捐助（微信）

![](http://cdn.1024lab.net/img/smart-admin/zhuoda-wechat-money.jpg)


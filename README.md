# GraduatedDesign
个性化定制APP应用的设计与实现。通过对APP开发和用户体验设计的大量研究、整理和归纳，结合移动APP用户体验设计特点，寻求用户体验设计与开发协同的匹配点。结合移动APP开发流程特点与用户体验设计原则，提取符合APP开发思想和流程的移动APP用户体验设计要素，建立符合用户体验设计的环形设计流程，并基于全新的设计要素与设计流程构建基于移动APP用户体验设计模型。

针对现今APP应用的迅速发展，为了解决用户手机内存空间和运存空间需求大的问题，降低手机客户端的成本；提高可用性和改进用户体验；涉及到网站的抓取和索引的时候，对SEO很契合；解决可移植性问题；减轻了用户终端任务，节省用户大量的资源；启用免更新服务，为用户节省时间和流量的特点而开发的一套基于C/S结构的在线APP应用定制管理系统的设计与实现。阐述了系统设计的背景和目的、体系结构、主要功能以及设计方法和特点。

喜欢或者觉得有用可以点击右上角 star，有兴趣可以一起改进和加入，邮件联系。

# 系统目标设计
本系统主要实现5个大的功能模块：APP应用管理、用户管理、APP定制管理、新闻管理、android客户端应用同步。每个大模块分成很多子模块。
从使用android客户端的用户来看，要求系统达到以下目标：

（1）简单的注册，快捷的登录，找回密码的安全保障。

（2）快速的定制APP应用。

（3）良好的APP应用使用体验。

（4）简单的APP应用添加与删除。

从设计架构人员来看，要求系统达到以下目标：

（1）能够方便信息的管理，如对数据的增、删、改、查、统计、分析、报表等。

（2）系统运行稳定，可靠性高。

（3）具有良好的运行效果和用户体验。

（4）具有较高的可维护性，能够适应用户的业务要求。

# 系统流程分析
通过对APP应用开发和用户体验设计的大量研究和归纳，以及对APP开发理论和方法的行研究，结合移动APP用户体验设计特点，寻求用户体验设计与开发协同的匹配点。通过对市场APP设计的分析，结合移动APP开发流程特点与用户体验设计的特点，提取符合APP开发思想和流程的移动APP用户体验设计要素，建立APP设计的环形设计流程，并基于用户体验与设计流程构建基于移动APP用户体验设计模型。为快速开发移动WEBAPP的深入研究和实践提供支持和借鉴。

# 技术与功能
本系统将在基于AndroidStudio和VisualStudio开发环境下采用WebService结合SQLServer 关系数据库技术来制作一个用户自由定制WEBAPP应用的系统，该系统包含一下几个功能：

Android微端用户主要功能：注册与登录；找回密码；资料修改；应用主题设置；定制APP应用；增加APP应用；删除APP应用；个性化APP应用推荐；清空APP应用；安全设置；多功能搜索等。

Android微端用户功能：

（1）用户登录：该模块用户可以很方便的输入帐号及密码进行登录，同时，会自动保存用户的现场信息，为下次登录节省输入数据量；

（2）用户注册：该模块用户可以填写昵称、邮箱帐号、设置密码注册自己的帐号；

（3）找回密码：用户可以验证自己的邮箱，找回自己的密码；

（4）进入应用：该模块用户可以进入主界面，使用自己定制的APP应用；

（5）定制应用：该模块用户可以定制自己想要的APP应用；

（6）增加应用：该模块用户可以增加自己需要的APP应用；

（7）删除应用：该模块用户可以删除自己现在不需要的APP应用；

（8）专属推荐：该模块用户可以查看系统算法根据自己的个人资料以及使用的APP应用推荐匹配的个性化APP应用；

（9）注销帐号：该模块用户可以注销帐号和清除登录信息，登录其它帐号；

（10）安全设置：该模块用户可以修改自己的密码，绑定手机号、QQ号；

（11）主题设置：该模块用户可以设置自己喜欢的主题颜色；

（12）个人资料：该模块用户可以修改个人的资料；

（13）多功能搜索：该模块用户可以在只输入一次关键字的情况下得到多种搜索引擎搜索的结果。

开发者与管理员主要功能：可以对Android微端用户、APP应用、新闻系统、业务处理进行各种管理操作。

（1）用户管理：管理员可以对普通用户进行增加、删除、查询、修改、冻结、激活等操作。

（2）APP应用管理：开发者可以上传APP应用，下架APP应用，更新APP应用信息，查询所有的APP应用信息等操作；管理员对APP应用进行查询、审核、上架、下架、拒绝上架等操作。

（3）开发者管理：管理员可以对开发者进行审核，查看开发者信息，修改开发者信息，增加开发者和删除开发者等操作。

（4）新闻管理：管理员可以发布新闻，对新闻进行修改、查询和删除操作。

# 其它
如需 webservice和pc端全部源码和相关论文，可以联系作者。

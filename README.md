# TeamTalk
	TeamTalk is a solution for enterprise IM
	
	具体文档见doc目录下,安装之前请仔细阅读相关文档。
	
# 交流
		建议大家在开发过程中遇到问题,提交issues到https://github.com/mogujie/TeamTalk/issues  
		
		我们的官方维护人员会抽时间解答,谢谢大家的理解.
		* qq群:341273218
TeamTalk 详细介绍
项目背景

蘑菇街能有今天的快速发展，得益于开源软件群雄崛起的大环境背景，我们一直对开源社区怀有感恩之情，因此也一直希望能为开源社区贡献一份力量。

2013年我们蘑菇街从社区导购华丽转身时尚电商平台，为解决千万妹子和时尚卖家的沟通问题，我们开发了自己的即时通讯软件。既然已经有了用户使用 的IM，为什么我们自己公司内部沟通还要用第三方的呢？因此就有了TT(TeamTalk)的雏形，现在蘑菇街内部的在线沟通全部通过TT来完成。随着 TT功能的逐渐完善，我们决定把TT开源来回馈开源社区，希望国内的中小企业都能用上开源、免费、好用的IM工具！



项目介绍

名称：TeamTalk

官网：http://tt.mogu.io/

开源协议：Apache License, Version 2.0

定位：中小型企业用户，member >= 2

特点：开源与产品并重

功能：可靠的消息传递机制；支持文字、图片、语音等富文本信息；文件收发等

项目框架

麻雀虽小五脏俱全，本项目涉及到多个平台、多种语言，简单关系如下图：

teamtalk架构图
![架构图](https://github.com/jdtsg/TeamTalk/blob/master/img/teamtalkorg.jpg)
服务端：

CppServer：TTCppServer工程，包括IM消息服务器、http服务器、文件传输服务器、文件存储服务器、登陆服务器 java DB Proxy：TTJavaServer工程，承载着后台消息存储、redis等接口 PHP server：TTPhpServer工程，teamtalk后台配置页面

客户端：

mac：TTMacClient工程，mac客户端工程

iOS：TTIOSClient工程，IOS客户端工程

Android：TTAndroidClient工程，android客户端工程

Windows：TTWinClient工程，windows客户端工程

语言：c++、objective-c、java、php

系统环境：Linux、Windows，Mac, iOS, Android

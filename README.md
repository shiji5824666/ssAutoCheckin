# v2ray/SSR机场定时批量签到

自动签到使用ssPanel搭建的机场程序，支持多账户

目前此功能正在公开测试中，若有bug请到Issues反馈

暂时仅支持同一个机场 多个账户密码自动签到

# 使用教程

## 入门
首先，如果需要免费使用此脚本，你需要先Fork这个仓库

(如果你不会用Github，可以先问问谷歌，大概看明白了就可以一起愉快地玩耍了)

Fork之后，请设置secret，按照下图说明进行设置(我随时可能会把自己简陋的图床抛弃，所以图片下面留有文字说明)

![Secrets设置教程](http://files.iruanp.com/public/066ccb7ab71c11d420ff5ecfad59e609.png)

创建三个Secrets，名称分别是:PSWD、SITE、USERS

USERS用于存放账户名称，PSWD用于存放和前者对应的密码

SITE用于存放你要签到的机场的URL，需要注意格式，否则可能会出现一些BUG，这个地址例如：https://www.iruanp.com 这种，带上协议，结尾不要斜杠

保存之后就会在每天早上七点钟自动执行

# 版权声明

此仓库照抄了一部分代码，来源:https://github.com/zhjc1124/ssr_autocheckin/blob/master/main.py

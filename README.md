# <center>PyWxDump</center>

[![Python](https://img.shields.io/badge/Python-3-blue.svg)](https://www.python.org/)
[![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/xaoyaoo/pywxdump)](https://github.com/xaoyaoo/PyWxDump)
[![GitHub all releases](https://img.shields.io/github/downloads/xaoyaoo/pywxdump/total)](https://github.com/xaoyaoo/PyWxDump)
[![GitHub stars](https://img.shields.io/github/stars/xaoyaoo/PyWxDump.svg)](https://github.com/xaoyaoo/PyWxDump)
[![GitHub forks](https://img.shields.io/github/forks/xaoyaoo/PyWxDump.svg)](https://github.com/xaoyaoo/PyWxDump/fork)
[![GitHub issues](https://img.shields.io/github/issues/xaoyaoo/PyWxDump)](https://github.com/xaoyaoo/PyWxDump/issues)

[![PyPI](https://img.shields.io/pypi/v/pywxdump)](https://pypi.org/project/pywxdump/)
[![Wheel](https://img.shields.io/pypi/wheel/pywxdump)](https://pypi.org/project/pywxdump/)
[![PyPI-Downloads](https://img.shields.io/pypi/dm/pywxdump)](https://pypistats.org/packages/pywxdump)
[![GitHub license](https://img.shields.io/pypi/l/pywxdump)](https://github.com/xaoyaoo/PyWxDump/blob/master/LICENSE)

* 欢迎大家提供更多的想法，或者提供代码，一起完善这个项目。

### 如果是小白，请关注公众号：`逍遥之芯`(下方二维码)，回复：`PyWxDump` 获取图文教程。

### 如有问题，请先查看：[FAQ](https://github.com/xaoyaoo/PyWxDump/tree/master/doc/FAQ.md) 是否有答案，或者关注公众号回复: `FAQ`。

qq交流群：[276392799](https://s.xaoyo.top/gOLUDl) or [276392799](https://s.xaoyo.top/bgNcRa)（进群密码，请查看[UserGuide.md](https://github.com/xaoyaoo/PyWxDump/tree/master/doc/UserGuide.md)）.

<div>
  <img align="" width="200"  src="https://github.com/xaoyaoo/PyWxDump/blob/master/doc/img/qrcode_gh.jpg" alt="公众号" title="关注公众号" height="200"/>
</div>

# 一、项目介绍

## 1. 项目简介

[PyWxDump](https://github.com/xaoyaoo/PyWxDump)是一款用于获取账号信息(昵称/账号/手机/邮箱/数据库密钥)、解密数据库、查看聊天记录、备份导出聊天记录为html的工具。

* <strong><big>
  超级想要star，走过路过，帮忙点个[![Star](https://img.shields.io/github/stars/xaoyaoo/PyWxDump.svg?style=social&label=Star)](https://github.com/xaoyaoo/PyWxDump/)
  呗，谢谢啦~</big></strong>

## 2. 功能介绍

#### 2.1 核心功能

* （1）获取微信昵称、微信账号、微信手机号、微信邮箱、微信KEY的**基址偏移**
* （2）获取当前登录微信的微信昵称、微信账号、微信手机号、微信邮箱、微信KEY、微信原始ID（wxid_******）、微信文件夹路径
* （3）根据key解密微信数据库
* （4）合并多种类型数据库，方便统一查看

#### 2.2 扩展功能

* （1）通过web查看聊天记录
* （2）支持导出聊天记录为html、csv,备份微信聊天记录
* （3）远程查看微信聊天记录（必须网络可达，例如局域网）

#### 2.3 文档类

* （1）提供数据库部分字段说明
* （2）提供CE获取基址偏移方法
* （3）提供MAC数据库解密方法

#### 2.4 其他功能

* （1）增加极简版pywxdumpmini，只提供获取数据库密钥以及数据库位置的功能
* （2）支持微信多开场景，获取多用户信息等

**利用场景**

1. 网络安全……
2. 日常备份存档
3. 远程查看聊天记录(通过web查看聊天记录)
4. 等等...............

## 3. 更新计划

* 1.每个人聊天记录分析，生成词云。
* 2.分析每个人每天的聊天数量，生成折线图（天-聊天数量）
* 3.分析不同的人的月聊天数量，年聊天数量，生成折线图
* 4.生成年度可视化报告
* 8.增加企业微信的支持
* 11.备份后的聊天记录，恢复到微信中
* 12.朋友圈的查看与备份
* 13.微信存储空间清理，减少微信占用空间(希望能通过选择某个人或群，把这群里的聊天记录中涉及的图片、视频、文件、语音等的媒体文件找出来，以群对话为单位有选择性的（比如时间段）或按群会话批量从电脑的缓存中清除。)
* 14.通过UI控制，自动给指定人发送消息

## 4. 其他

[PyWxDump](https://github.com/xaoyaoo/PyWxDump)是[SharpWxDump](https://github.com/AdminTest0/SharpWxDump)的经过重构的python语言版本，同时添加了很多新的功能。

* 项目地址：https://github.com/xaoyaoo/PyWxDump
* 目前只在windows下测试过，mac、linux下可能会存在问题。
* 如发现[version_list.json](https://github.com/xaoyaoo/PyWxDump/tree/master/pywxdump/version_list.json)缺失或错误、bug，有改进意见、想要新增功能, 请提交[issues](https://github.com/xaoyaoo/PyWxDump/issues).
* 常见问题请参考[FAQ](https://github.com/xaoyaoo/PyWxDump/tree/master/doc/FAQ.md)，更新日志请参考[CHANGELOG](https://github.com/xaoyaoo/PyWxDump/tree/master/doc/CHANGELOG.md)
* Web UI的仓库位置 [wxdump_web](https://github.com/xaoyaoo/wxdump_web)
* 如果对wxdump实现原理感兴趣，请关注公众号：`逍遥之芯`，回复：`原理` 获取原理解析。

* [:sparkling\_heart: Support Me](https://github.com/xaoyaoo/xaoyaoo/blob/main/donate.md)

## 5. Star History

<details>
<summary>click to expand</summary>

[![Star History Chart](https://api.star-history.com/svg?repos=xaoyaoo/pywxdump&type=Date)](https://star-history.com/#xaoyaoo/pywxdump&Date)

</details>

# 二、使用说明

* 详细使用说明见 [UserGuide.md](https://github.com/xaoyaoo/PyWxDump/tree/master/doc/UserGuide.md)

* 极简版使用说明见 [pywxdumpmini](https://github.com/xaoyaoo/pywxdumpmini)

* 如果想修改UI，请clone [wx_dump_web](https://github.com/xaoyaoo/wxdump_web) 项目，然后按需修改（该UI采用VUE+ElementUI开发）

【注】:

* 关于基址使用cheat engine获取，参考[CE获取基址.md](https://github.com/xaoyaoo/PyWxDump/tree/master/doc/CE获取基址.md)
  （该方法可用`wxdump bias`命令代替，现仅用作学习原理）
* 关于数据库解析，参考[wx数据库简述.md](https://github.com/xaoyaoo/PyWxDump/tree/master/doc/wx数据库简述.md)

# 三、免责声明（非常重要！！！！！！！）

* 本项目仅供学习交流使用，请勿用于非法用途，否则后果自负。

* 您应该在下载保存，编译使用本项目的24小时内，删除本项目的源代码和（编译出的）程序。

* 本项目仅允许在授权情况下对数据库进行备份，严禁用于非法目的，否则自行承担所有相关责任。

* 下载、保存、进一步浏览源代码或者下载安装、编译使用本程序，表示你同意本警告，并承诺遵守它;

* 请勿利用本项目的相关技术从事非法测试，如因此产生的一切不良后果与项目作者无关。

# 四、致谢

[![PyWxDump 贡献者](https://contrib.rocks/image?repo=xaoyaoo/PyWxDump)](https://github.com/xaoyaoo/PyWxDump/graphs/contributors)[![UI 贡献者](https://contrib.rocks/image?repo=xaoyaoo/wxdump_web)](https://github.com/xaoyaoo/wxdump_web/graphs/contributors)


<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/FxL5qM0.jpg" alt="Bot logo"></a>
</p>

<h3 align="center">机器人姓名</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![Platform](https://img.shields.io/badge/platform-reddit-orange.svg)](https://www.reddit.com/user/Wordbook_Bot)
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 🤖 用几句话描述你的机器人做什么<br> 
</p>

## 📝 目录
+ [简介](#about)
+ [演示](#demo)
+ [原理](#working)
+ [用法](#usage)
+ [快速上手](#getting_started)
+ [部署你的机器人](#deployment)
+ [技术支持](#built_using)
+ [待做](../TODO.md)
+ [贡献](../CONTRIBUTING.md)
+ [作者](#authors)
+ [致谢](#acknowledgement)

## 🧐 简介 <a name = "about"></a>
用 1-2 个段落描述该机器人的用途。

## 🎥 演示 <a name = "demo"></a>
![Working](https://media.giphy.com/media/20NLMBm0BkUOwNljwv/giphy.gif)

## 💭 原理 <a name = "working"></a>


该机器人首先从评论中提取单词，然后从牛津词典 API 中获取单词的定义、语篇、例子和来源。如果该词在牛津词典中不存在，牛津词典的API 会返回一个 404 响应，机器人便会尝试从 Urban Dictionary 的 API 中获取结果。
该机器人使用 Pushshift API 来获取评论，使用 PRAW 模块来回复评论，使用 Heroku 作为服务器。它用 Python 3.6 编写。

## 🎈 用法 <a name = "usage"></a>

使用该机器人，键入：
```
!dict word
```
指令的第一部分，如 "!dict" 对大小写**不**敏感。
机器人会给你牛津词典（或 Urban Dictionary；如果该词不存在于牛津词典中）的定义作为评论回复。

### 示例:

> !dict what is love

**定义:**

Baby, dont hurt me~
Dont hurt me~ no more.

**示例:**

Dude1: Bruh, what is love?
Dude2: Baby, dont hurt me, dont hurt me- no more!
Dude1: dafuq?

**来源:** https://www.urbandictionary.com/define.php?term=what%20is%20love

---

<sup>Beep boop. I am a bot. If there are any issues, contact my [Master](https://www.reddit.com/message/compose/?to=PositivePlayer1&subject=/u/Wordbook_Bot)</sup>

<sup>Want to make a similar reddit bot? Check out: [GitHub](https://github.com/kylelobo/Reddit-Bot)</sup>

## 🏁 快速上手 <a name = "getting_started"></a>

遵循以下指引，你将在本地机器上建立并运行项目副本用于开发和测试目的。参见[deployment](#deployment)了解如何在实时系统上部署项目的注意事项。

### 先决条件
你需要哪些软件及如何安装它们。

```
举个例子
```

### 安装

手把手教你如何让运行开发环境。
介绍每一步都是什么

```
举个例子
```

重复以上

```
直到结束
```

最后用从系统中获取的一些数据来举例，或者用它来做一个小演示。

## 🚀 部署你的机器人 <a name = "deployment"></a>

 参见我的配置查看如何部署机器人的项目示例。
+ **Heroku**: https://github.com/kylelobo/Reddit-Bot#deploying_the_bot

## ⛏️ 技术支持 <a name = "built_using"></a>
+ [PRAW](https://praw.readthedocs.io/en/latest/) - Python Reddit API Wrapper
+ [Heroku](https://www.heroku.com/) - SaaS hosting platform

## ✍️ 作者 <a name = "authors"></a>
+ [@kylelobo](https://github.com/kylelobo) - 构想&初步工作

另请参见参与本项目的[贡献者](https://github.com/kylelobo/The-Documentation-Compendium/contributors)名单。

## 🎉 致谢 <a name = "acknowledgement"></a>
+ 向任何使用其代码的人致意
+ 灵感来源
+ 参考文献
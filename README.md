# Your Vote bot
### 基于 [Ubervotebot](https://github.com/haselkern/ubervotebot) @haselkern 的 Telegram 投票机器人

在原有的 Ubervotebot 上进行了修改和简化
* 隐藏了投票中结果的显示, 避免投票受到影响
* 提供了实名和匿名的结果显示方法(只有发起投票的 owner 可以使结果可见)
* 去掉了图片显示结果等方法
* 进行了中文化

![inline poll](https://raw.githubusercontent.com/tokinonagare/ubervotebot/master/screenshots/poll.png)

投票中和投票后的结果 如下图:

![poll ing](https://raw.githubusercontent.com/tokinonagare/ubervotebot/master/screenshots/poll-ing.png)

![result list](https://raw.githubusercontent.com/tokinonagare/ubervotebot/master/screenshots/result-list.png)

![result names](https://raw.githubusercontent.com/tokinonagare/ubervotebot/master/screenshots/result-names.png)


这个项目需要使用 @yukuku's 的 google cloud [telebot](https://github.com/yukuku/telebot) 来启动.

注: 我自己在 upload 的方法上使用的是 appcfg.py -A your-vote-bot -V 1 update .
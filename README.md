# T4BT是一个专为Telegram群发直接消息（DM）设计的机器人，用于创建独特的帖子。

## T4BT是一个为Telegram群发DM（直接消息）创建独特内容的Telegram机器人，是从事Telegram群发DM工作人员的关键和不可或缺的工具。
## 如果您在Telegram群发DM方面工作，T4BT将成为您不可或缺的助手。这个机器人将帮助您为群发创建独特的消息。
 
 * Software description is also available in English. See [T4BT - TG Posts Maker Bot EN](https://github.com/telegram-prime/TG-Posts-Maker-Bot)
 * Описание программы так же доступно на русском языке. См. [T4BT - TG Posts Maker Bot RU](https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU)


## T4BT Bot能做什么。
- 创建一篇或多篇帖子：
    * 文本消息；
    * 图片；
    * 普通视频；
    * 圆形视频；
    * GIF动画；
    * 音频文件；
    * 语音信息。
- 为每个媒体文件设置描述。
- 可以在描述中使用spintax，例如：`{文本_1|文本_2|文本_3|文本_4}`。
- 支持MARKDOWN格式，以在帖子描述或普通文本帖子中创建超链接，格式：`[链接文字](<https://www.examle.com>)`。
- 能够创建带有底部按钮的帖子，也能够无按钮。
- 可以选择每个帖子的按钮数量，以及每行显示的按钮数量。
- 在创建按钮时，spintax是受支持的，格式：`{按钮1|按钮2} | {<https://example1.com/>|<https://example2.com/>}`。生成按钮数据可以作为文本文件发送给机器人（用于创建大量帖子）。
- 可以在每个按钮链接中添加随机变量，格式：`<https://example1.com?jd73hddsk83>`。
- 能够创建指向帖子的链接，类似：`https://t.me/YourBotName_bot?start=c747ca0a61d46131`。
- 能够分别为机器人创建默认帖子（也称为默认帖子）。即对任何直接通过用户名切换到机器人的访客都会显示此帖子。它可能与意为供散布的已创建帖子有所不同。
- 能够通过代理运行机器人。
- 能够为特定时间段运行机器人。
- 多个机器人可以从相同计算机访问帖子数据库。
- 能够在相同计算机上运行多个机器人。
- 键绑定硬件，并且能够重置密钥。重置免费。
- 内置详细步骤说明。
- 该机器人提供四种语言：🇺🇸 🇷🇺 🇪🇸 🇨🇳。
- 免费更新。
- 在线技术支持。


## T4BT Bot运行模式。
-在`INLINE`模式下——最有前途和高效的方法。
   * 这是你自己的，也就是@postbot，只是由你为你的个人项目或服务创建的TG用户名！
   * 该模式与标准postbot的主要区别在于，它为一个帖子或许多已创建的帖子生成了多个唯一ID，而不仅仅是一个。
   * 使用文本随机化，用于媒体文件的描述和简单文本帖子，每发送使用其中一个ID的消息都将是独一无二的。
   * 对于帖子中的媒体文件也适用，即每发送的帖子都将具有唯一的媒体文件标识符。
   * 对于帖子中的按钮也适用，即每个帖子都将具有唯一的按钮，当然，假设按钮已经通过spintax设置。例如：{Button1|Button2} | {{https|http}://example1.com/|{https|http}://example2.com/|...}，以及1-2-5-10千种不同的搭配，通过反斜杠(|)分隔。


## 在`正常机器人`模式下。

   * 在这种模式下，每个帖子点击`/start`按钮后会生成一个单独的链接，其中包含一个唯一的ID，以转到该帖子。
   * 帖子的整个唯一化过程与上面描述的相同。


## 要启动机器人，您需要：
   * 从`@BotFather`获取您的bot令牌。
   * 负责管理和创建帖子的Telegram帐户的ID，将成为机器人的管理员。


## 我们提供一个24小时的免费试用期，在此期间，用户可以免费测试产品并确认系统的有效性，并获得对产品的完全访问权限。
### - 演示密钥请求按钮位于软件内部。

## 试用期结束后，产品将提供两种付费订阅：
  - 月度许可：1个月无限制。
  - 年度许可：1年无限制。


## 下载:
 - [始终为最新版本](https://github.com/telegram-prime/TG-Posts-Maker-Bot/releases/latest)


## 视频:
 - [YouTube](https://youtu.be/LS0AnAYDonU)


## 屏幕截图:


<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/32f2bb2d-946c-45e2-817e-ddc3ae196752" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/4ed2f1b0-c4f9-463c-a1d6-e867d936b8f9" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/37611e3e-3246-438e-94bf-4e06229d78a8" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/72c2d104-5b4f-4e48-934f-92cc4b57ceec" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/26849652-e03b-4720-b576-63d7e1ebe883" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/f6159d53-1b37-46fc-8627-488a5abf22c8" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/a43a3b5c-4fc3-42cf-b9a7-bc9bf12c8ec8" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/f5cb88c5-62fa-4f16-962e-51d4bbdb3ee3" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/58f124be-9cb5-432b-93ee-afba6f5d77e5" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/7bebc3e8-e0ea-4691-ba33-502766ac91ef" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot/assets/94137664/977d1a25-1746-40cf-87d1-33924bf44838" width="200" height="200">




##  联系方式:
- Wеb: https://telegramprime.net/ - EN Version
- Wеb: https://telegramprime.com/ - RU Version

- Email:    manager[@]telegramprime.net
- Telegram: [Send message](https://telegramprime.net/telegram-contact)
- ICQ:      [Send message](https://telegramprime.net/icq-contact)
- TamTam:   [Send message](https://telegramprime.net/tamtam-contact)
- Discord:  [Send message](https://telegramprime.net/discord-contact)
- Element:  [Send message](https://telegramprime.net/element-contact)


## 捐赠:
* [请我们喝咖啡）](https://nowpayments.io/donation/telegramprime)
* 谢谢！


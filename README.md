# 股票雄鹰
一个显示股票信息的软件

## 项目介绍
这是Udacity [Android Developer Nanodegree](https://cn.udacity.com/course/android-developer-nanodegree--nd801-cn-advanced) 的一个项目

这是此项目的初始代码 [股票雄鹰](https://github.com/udacity/StockHawk)，在初始版本中，该应用只能在网络上搜索股票价格并允许用户添加股票，从而跟踪其价格变化。而我所做的是根据以下用户反馈修改代码，为其上架做准备。

#### 用户反馈
- Hellen 说：“即使打开了Talkback，我也无法使用这个应用。我的朋友非常喜欢该应用，因此我也想下载它，但Talkback 无法告诉我这些按键的功能。”
- 你的老板 说：“我们要为股票雄鹰在中国的发布做准备，请完成应用的中文版本。”
- Adebowale 说：“股票雄鹰可以跟踪股票的当前价格，但我需要用外部程序来跟踪其长期的价格趋势。希望该软件能够针对每个股票提供更多的详细信息，包括其长期的价格趋势。”
- Gundega 说：“我的Android设备上有很多桌面小工具，我希望我的主屏幕上能有一个显示股票报价的小工具。”
- Jamal 说：“我在你们的应用中发现了一个 bug，当我搜索一个不存在的股票报价时，应用就会崩溃。”
- Xaio-lu 说：“当我第一次在未连接网络的情况下打开该应用时，应用显示仅为一片空白。我希望该应用能就显示空白的原因或我的股票报价是否过期给予提示。”

## 数据来源
数据来源于[YahooFinanceAPI](http://financequotes-api.com/)

## 修改内容
修改内容包括
- 增加异常情况处理

    其中包括网络异常处理，用户输入错误处理，数据库为空处理，更新价格失败提醒，并使用**Toast**给予用户有用的提示。
- 添加详细界面

    使用**MPAndroidChart**显示价格趋势图，用户可以点击某一日期进行互动。

- 添加桌面小工具

    用户可以添加大小可变的桌面小工具，查看多个股票的最新价格。

- 本地化及辅助功能

    用户可以选择中文或英文版本。
    所有按钮都添加内容说明。

## 依赖库
- [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)
- [butterknife](https://github.com/JakeWharton/butterknife)
- [YahooFinanceAPI](http://financequotes-api.com/)

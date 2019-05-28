# Scrapy 1.6文档

本文档包含您需要了解的有关Scrapy的所有信息。



## 获得帮助

遇到麻烦？我们想帮忙！

- 试试[常见问题](https://docs.scrapy.org/en/latest/faq.html) - 它有一些常见问题的答案。
- 寻找具体信息？尝试[索引](https://docs.scrapy.org/en/latest/genindex.html)或[模块索引](https://docs.scrapy.org/en/latest/py-modindex.html)。
- [使用scrapy标签在StackOverflow中](https://stackoverflow.com/tags/scrapy)提问或搜索问题。
- 在[Scrapy子板块](https://www.reddit.com/r/scrapy/)中询问或搜索问题。
- 搜索[scrapy用户邮件列表](https://groups.google.com/forum/#!forum/scrapy-users)的档案问题。
- 在[#scrapy IRC频道中](irc://irc.freenode.net/scrapy)提问。
- 在我们的[issues跟踪器](https://github.com/scrapy/scrapy/issues)中提交Scrapy的bug。
- 

## 第一步

[Scrapy初探](https://docs.scrapy.org/en/latest/intro/overview.html)

​	了解Scrapy是什么以及它如何帮助您。

[安装指南](https://docs.scrapy.org/en/latest/intro/install.html)

​	在您的计算机上安装Scrapy。

[Scrapy教程](https://docs.scrapy.org/en/latest/intro/tutorial.html)

​	写下您的第一个Scrapy项目。

[例子](https://docs.scrapy.org/en/latest/intro/examples.html)

​	通过使用预设的Scrapy项目了解更多信息。



## 基本概念

[命令行工具](https://docs.scrapy.org/en/latest/topics/commands.html)

​	学习用于管理您的Scrapy项目的命令行工具。

[爬虫(Spiders)](https://docs.scrapy.org/en/latest/topics/spiders.html)

​	编写规则以抓取您的网站。

[选择器(Selectors)](https://docs.scrapy.org/en/latest/topics/selectors.html)

​	使用XPath从网页中提取数据。

[Scrapy shell](https://docs.scrapy.org/en/latest/topics/shell.html)

​	在交互式环境中测试您的提取代码。

[Items](https://docs.scrapy.org/en/latest/topics/items.html)

​	定义您要爬取的数据。

[Item Loaders(加载器)](https://docs.scrapy.org/en/latest/topics/loaders.html)

​	使用提取的数据填充您的Items。

[Item Pipeline(管道)](https://docs.scrapy.org/en/latest/topics/item-pipeline.html)

​	后期处理并存储您已爬取的数据。

[原料输出](https://docs.scrapy.org/en/latest/topics/feed-exports.html)

​	使用不同的格式和存储输出您的已爬取的数据。

[请求和响应](https://docs.scrapy.org/en/latest/topics/request-response.html)

​	理解用于表示HTTP请求和响应的类。

[链接提取器](https://docs.scrapy.org/en/latest/topics/link-extractors.html)

​	方便的类，用于从页面中提取关联链接。

[设置](https://docs.scrapy.org/en/latest/topics/settings.html)

​	学习如何配置Scrapy并查看所有[可用设置](https://docs.scrapy.org/en/latest/topics/settings.html#topics-settings-ref)。

[异常](https://docs.scrapy.org/en/latest/topics/exceptions.html)

​	查看所有可用的异常情况及其含义。



## 内置服务

[日志记录(Logging)](https://docs.scrapy.org/en/latest/topics/logging.html)

​	学习如何在Scrapy上使用Python的内置日志记录。

[收集统计信息](https://docs.scrapy.org/en/latest/topics/stats.html)

​	收集有关您正在爬取的爬虫的统计信息。

[发送电子邮件](https://docs.scrapy.org/en/latest/topics/email.html)

​	发生特定事件时发送电子邮件通知。

[Telnet控制台](https://docs.scrapy.org/en/latest/topics/telnetconsole.html)

​	使用内置的Python控制台检查正在运行的爬虫。

[网络服务](https://docs.scrapy.org/en/latest/topics/webservice.html)

​	使用Web服务监视和控制爬虫。



## 解决具体问题

[经常问的问题](https://docs.scrapy.org/en/latest/faq.html)

​	获得最常见问题的答案。

[调试爬虫](https://docs.scrapy.org/en/latest/topics/debug.html)

​	学习如何调试scrapy爬虫的常见问题。

[爬虫合同](https://docs.scrapy.org/en/latest/topics/contracts.html)

​	学习如何使用合同来测试您的爬虫。

[常见做法](https://docs.scrapy.org/en/latest/topics/practices.html)

​	熟悉一些Scrapy的常见做法。

[通用爬虫](https://docs.scrapy.org/en/latest/topics/broad-crawls.html)

​	Tune Scrapy可以并行抓取大量域名。

[使用浏览器的开发者工具进行抓取](https://docs.scrapy.org/en/latest/topics/developer-tools.html)

​	学习如何使用浏览器的开发者工具。

[调试内存溢出](https://docs.scrapy.org/en/latest/topics/leaks.html)

​	学习如何查找和清除爬虫中的内存溢出。

[下载和处理文件及图像](https://docs.scrapy.org/en/latest/topics/media-pipeline.html)

​	下载与已爬取Items关联的文件和或图像。

[部署爬虫](https://docs.scrapy.org/en/latest/topics/deploy.html)

​	部署Scrapy爬虫并在远程服务器中运行它们。

[AutoThrottle扩展](https://docs.scrapy.org/en/latest/topics/autothrottle.html)

​	根据负载动态调整爬虫速率。

[标杆管理](https://docs.scrapy.org/en/latest/topics/benchmarking.html)

​	检查Scrapy如何在您的硬件上执行。

[Jobs：暂停和恢复抓取](https://docs.scrapy.org/en/latest/topics/jobs.html)

​	学习如何暂停和恢复大型爬虫的抓取。



## 扩展Scrapy 

[架构概述](https://docs.scrapy.org/en/latest/topics/architecture.html)

​	了解Scrapy架构。

[下载中间件](https://docs.scrapy.org/en/latest/topics/downloader-middleware.html)

​	自定义页面的请求和下载。

[爬虫中间件](https://docs.scrapy.org/en/latest/topics/spider-middleware.html)

​	自定义您的爬虫的输入和输出。

[扩展](https://docs.scrapy.org/en/latest/topics/extensions.html)

​	使用您的自定义功能扩展Scrapy

[核心API](https://docs.scrapy.org/en/latest/topics/api.html)

​	在扩展和中间件上使用它来扩展Scrapy功能

[信号](https://docs.scrapy.org/en/latest/topics/signals.html)

​	查看所有可用信号以及如何使用它们。

[Item导出](https://docs.scrapy.org/en/latest/topics/exporters.html)

​	快速将您已爬取的items导出到文件（XML，CSV等）。



## 其他

[发行说明](https://docs.scrapy.org/en/latest/news.html)

​	查看最近Scrapy版本中的变化。

[为Scrapy做贡献](https://docs.scrapy.org/en/latest/contributing.html)

​	学习如何为Scrapy项目做出贡献。

[版本控制和API稳定性](https://docs.scrapy.org/en/latest/versioning.html)

​	了解Scrapy版本控制和API稳定性。



[下一个 ](https://docs.scrapy.org/en/latest/intro/overview.html)
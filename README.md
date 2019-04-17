# dateNewsBug
* 这是我参加的第四届中国数据新闻大赛，搜集大数据时所使用的简单爬虫，因为所爬政府网站的反爬策略不严格（毕竟政府公示就是为了公开公正，取信于民嘛），所以没有使用线程与代理池。  
* 该工具实现了递归爬取网站中的包含某关键字的所有通告，并将其标题、发布时间、正文网站、正文等通过jdbc存入数据库，数据表的创建被包含在代码中，只需要输入库的位置以及账号密码即可  
* 这里使用了jdbc、递归、http，io流等相关知识，使用的解析器是jsoup，如要使用或者检测的话请务必下载文件中的jdbc驱动以及jsoup.jar包  

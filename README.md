## 豆瓣读书爬虫

基于[lanbing510/DouBanSpider](https://github.com/lanbing510/DouBanSpider)开源部分代码进行大规模重构，并将Python版本升级为3.8

旨在提供api级别的接口，目前可将数据导出为JSON格式（暂未集成Web或Java服务）

#### Feature
 - 爬取豆瓣读书默认标签下图书列表（如[https://www.douban.com/tag/%E7%BD%97%E9%A9%AC/](https://www.douban.com/tag/%E7%BD%97%E9%A9%AC/?source=topic_search)）及用户自定义标签下图书列表（如[https://book.douban.com/tag/%E5%8F%A4%E5%B7%B4%E6%AF%94%E4%BC%A6](https://book.douban.com/tag/%E5%8F%A4%E5%B7%B4%E6%AF%94%E4%BC%A6)）
 - 导出JSON格式数据，数据涵盖图书概要、评分、图书与作者简介以及用户评论等（可插拔）

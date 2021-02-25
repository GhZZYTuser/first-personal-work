# first-personal-work
1. 数据采集（在一起222.py)  
* 采集腾讯视频里电视剧《在一起》的全部评论信息   
主要思路：抓取url地址 --> 遍历url --> 正则提取评论 --> 保存结果为json  
  * 😜容易编写代码  
  
2. 数据处理(High.py)  
* 用jieba进行分词，统计高频词及数量  
  * 这部分主要完成评论中高频词的统计
  * 并将高频词和数量结果保存为json形式，以便于制作词云图  
 
3. 数据分析展示(photo.html)  
* 将采集到的评论信息做成词云图  
结合插件echarts.js，echarts-wordcloud.min.js

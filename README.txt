IDE:pycharm
语言:python
web框架:Flask
分词工具:结巴
爬虫工具:BeatifulSoup+Request三方库


1) TFIDF: 给定用自己名字命名的文件夹，请自己爬取一定数量的网页、微博形成语料集合，存入该文件夹；在线状态下，对其中的词语进行TFIDF统计，且输出到“姓名-tfidf-日期.txt“文件中

tfidfpage.py
生成预料集合已经在殷旺文件夹下，内附爬虫工具
在线tfidf统计网站为127.0.0.1:5000/tfidf 上传文件保存为test.txt 结果为3015216028-tfidf-5月8日

2) SIM: 在线状态下，从网页页面输入任意两个句子，求其相似度，包括：内积，余弦及Jaccard三种度量方式；同时，可实现对导入的文件夹语料的tfidf统计。 

simpage.py
两个句子网站为127.0.0.1:5000/sim
对文件夹语料的tfidf统计127.0.0.1:5000/sim/文本id

3）SJet：实现基于向量空间模型（VSM）的搜索引擎。 
sjetpage.py
网站为127.0.0.1:5000/sjet


基于flask python3.x
是用pycharm直接导入工程 运行run.py即可
详细实现 代码内有注释

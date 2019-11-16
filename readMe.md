# 爬取的数据集合

## 1.IMDB电影数据

### 介绍：

movies_imdb.json： IMDB上有票房数据的电影信息

**数据来源**：IMDB

[https://www.imdb.com/search/title/?title_type=feature&release_date=1980-01-01,2019-12-31](https://www.imdb.com/search/title/?title_type=feature&release_date=1980-01-01,2019-12-31)

（类型：Feature Film，时间：1980-2019）

爬取时间：2019年11月

**数据概况：**

共有36793条数据，24个属性。

具体如下：

	actors             34333 non-null object
	box_office         36793 non-null object
	box_office_ow      12537 non-null object
	budget             12412 non-null object
	certificate        17914 non-null object
	countries          35098 non-null object
	directors          34387 non-null object
	distribution_co    30964 non-null object
	genre              34203 non-null object
	languages          34881 non-null object
	metascore          10397 non-null object
	month              36374 non-null object
	production_co      32374 non-null object
	rating             36793 non-null object
	release_country    36741 non-null object
	release_dates      36741 non-null object
	review             27898 non-null object
	runtime            28085 non-null object
	tagline            13954 non-null object
	tconst             36793 non-null object
	title              36793 non-null object
	votes              36793 non-null object
	writers            33189 non-null object
	year               36793 non-null object
**注：票房信息已处理成统一的单位（美元）（用的是当时的汇率）**

**用途参考：** 票房预测



## 2.豆瓣电影数据

### 介绍

movies_douban.sql：豆瓣电影信息数据。

共9915条，包括标题、年份、演员、评分等信息。

具体如下：

​        ![img](https://uploader.shimo.im/f/qzlZpHgz95ItJlA7.png!thumbnail)
​     

## 3.豆瓣电影评论数据

### 介绍

comments_douban.sql： 近500万条豆瓣短评数据。

**用途参考**： 影评情感分析








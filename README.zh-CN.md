简体中文 ｜ [English](README.md)

# 动漫台词数据集

一个CSV格式的动漫台词数据集，从互联网上爬取整理所得。本数据集可用作T2T，尤其动漫相关的llm生成模型的nlp项目。这是第一部分的数据集，未来可能会有第二部分。

## 描述

* CSV文件包含两列（名字，字幕），4055行数据，大小在400MB左右。每个名字就是一季动漫或者一个动漫剧场版，字幕均不包含角色，独白等内容，只有一个个对话，空格分隔。名字和字幕大部分是中文，名字包含少量的繁体，字幕有部分是英文和日文。

* 部分数据截图

[capture 1](https://github.com/cily-yyds/Anime-subtitles/blob/main/glimpse/capture%201.png)

[capture 2](https://github.com/cily-yyds/Anime-subtitles/blob/main/glimpse/capture%202.png)

## 用法

克隆我的仓库地址即可

## 贡献

从截图可以看到，有些数据存在一些问题，字段重复，部分名字缺失，一些无关无意义的字符组合。我的数据预处理做的并不够好，欢迎大家指正PR。
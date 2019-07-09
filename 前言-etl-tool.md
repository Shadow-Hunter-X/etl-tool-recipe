---
title: 前言-etl-tool
---

## 主要内容说明

主要对目前数据整合处理中的较为流行，且具有一定的代表性的ETL工具进行说明,包括:

|名称|开源&跨平台|代表性|支持hadoop|操作性|
|-----|-----|-----|------|------|
|kettle|开源&跨平台|开源软件|支持|图形化操作|
|ssis|不开源&只在Windows|商业软件|支持|图形化操作|
|sqoop|开源|专为Hadoop|支持|编写脚本|
|kafka|开源|实时ETL-未来实时流数据处理平台|支持|脚本| 

所以针对每种的ETL工具中,具有不同的特点和倾向性,因此具有不同的代表性,在适合的场景下选择合适的工具。

* kettle 
	Kettle是一款国外开源的ETL工具，纯java编写，可以在Windows、Linux、Unix上运行，数据抽取高效稳定。
	
* SSIS
    是Microsoft SQL Server Integration Services的简称，是生成高性能数据集成解决方案（包括数据仓库的提取、转换和加载 (ETL) 包）的平台
	
* Sqoop
	主要用于在Hadoop(Hive)与传统的数据库(mysql、postgresql...)间进行数据的传递，可以将一个关系型数据库（例如 ： MySQL ,Oracle ,Postgres等）中的数据导进到Hadoop的HDFS中，也可以将HDFS的数据导进到关系型数据库中。
	
* kafka 用于实时ETL
	Kafka是由Apache软件基金会开发的一个开源流处理平台
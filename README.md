# 介绍

本repo用以分享蓝尾星小组所完成的平话数位化文献及词库。由于数据库暂未上线，文件夹内的数据并没有经过完全的mapping。

## 文件管理规范

### 文件及文件夹命名格式：

`年份月份-版次-文献原始标题：文献原始副标题（版本信息）`

如：

`199410-1-福州方言词典`

其中：

- 年份如不明确，可写大约年份、年代（*e.g.* 2010s）、世纪（*e.g.* 20c）；
- 如月份不明确、无版次，则留空，如`1754--福州府志·卷之二十四·方言`、`1906--加订美全八音`；
- 如有副标题再于全角冒号后填写，否则留空，亦不需留冒号；
- 如有版本信息再于全角括号内填写，否则留空，亦不需留括号；
- 如版次相同，刷次不一，则年份月份从出版时间，版次亦遵原书，于括号内填写刷次信息。
- 
### 数位化格式：

在数位化文件的第一行，以#号注释书名，如`#《福州府志·卷之二十四·方言》`。

在数位化文件的第二行，以#号注释文件解析格式，如`#第一列爲ID；第二列爲輸入法寫法（可忽略）；第三列爲原書寫法；第四列爲正文。正文內含兩個條目的，則分列，如“郎罷”與“囝”。`。

在数位化文件的第三行，以#号注释文件mapping进度，如`#mapping完成，差1詞暫時未知發音`。

在数位化文件的第四行，以#号记录数位化团队成员。

在数位化文件的第五行，以#号记录其他内容，如感谢等。

每份文件的解析格式，可依据原书格式灵活处理，不需要每一份数位化文献都遵循相同的格式。

若文件在释音或释义上有错误，则以“`	#註=`”的格式对其进行注释。
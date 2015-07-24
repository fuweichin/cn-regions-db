# 县及县以上行政区划代码数据库（截止2014年10月31日）

## 说明
1. 表cn_region中的数据直接来自国家统计局<a href="#a1"><sup>[1]</sup></a>，未经加工，可作数据存根之用。
2. 表cn_province cn_city和cn_county是从cn_region中拆分、加工而来，分别为省、市、县三级行政区域表。
其中列name和suffix是从列fullname粗略提取而来，遵循name+suffix=fullname。
表cn_province中的列domain数据参考自中国互联网络域名体系<a href="#a1"><sup>[2]</sup></a>。
3. 若不需要列name，则可直接忽略或删除列name和suffix。
否则，需自行校对name的可读性（name字符长度可能为0或1）。

## 参考
<i id="a1">[1]</i> [国家统计局《最新县及县以上行政区划代码（截止2014年10月31日）》](http://www.stats.gov.cn/tjsj/tjbz/xzqhdm/201504/t20150415_712722.html)

<i id="a2">[2]</i> [信息产业部《关于调整中国互联网络域名体系的公告》](http://www.gov.cn/gzdt/2006-02/24/content_210497_2.htm)

# 县及县以上行政区划代码数据库（截止2014年10月31日）

## 特点

+ 以行政区划代码作为主键
+ 支持名称与单位分离，如果全称可被拆分
+ 支持拼音检索（数据由jpinyin提供）

## 说明

1. 表cn_region中的数据直接来自国家统计局<a href="#a1"><sup>[1]</sup></a>，可作数据存根之用。
2. 表cn_province cn_city和cn_county是从cn_region中拆分、加工而来，分别为省、市、县三级行政区域表。
3. 列code和pcode分别为行政区划代码及其上一级的行政区划代码；
  列name和suffix是从列fullname粗略提取而来，遵循name+suffix=fullname；
  列pinyin和py分别为列name拼音输入的全拼和简拼


## 参考
<i id="a1">[1]</i> [国家统计局《最新县及县以上行政区划代码（截止2014年10月31日）》](http://www.stats.gov.cn/tjsj/tjbz/xzqhdm/201504/t20150415_712722.html)

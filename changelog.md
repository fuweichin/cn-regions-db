# 变化日志
## cn_regions_db 0.3 变化日志

+ 对于表cn_province cn_city和cn_county
	+ 删除字段`id`
	+ 改用`code`作主键
	+ 添加字段`pinyin`和`py`以支持拼音或简拼检索
+ 从表cn_province删除列domain

## cn_regions_db 0.2 变化日志

+ 从表cn_region中拆分出表cn_province cn_city和cn_county
+ 为表cn_province添加列domain并初始化数据

## cn_regions_db 0.1 变化日志

+ 添加表cn_region，并从导入统计局发布的数据

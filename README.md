### 数据清洗

#### 版本一

抽取timestamp,imsi,lac_id,cell_id 四个字段

去除imsi中，包含特殊字符的数据条目（‘#’,’*’,’^’）

去除空间信息残缺的记录条目（imsi、lac_id、cell_id中为空）

timestamp时间戳转换格式 ‘20190603000000’--年月日时分秒

#### 版本二

去除干扰数据条目（不是2018.10.03当天的数据）

#### 版本三（进行时）

去除两数据源关联后经纬度为空的数据条目

以人为单位，按时间正序排序

211-Query
WebGIS课程设计：211大学可视化查询系统

要将各大高校显示在地图上需要各高校的位置信息。各高校的经纬度坐标数据由两个double字段组成。坐标数据和简介、链接等信息存储在云后端，数据字段格式如下图所示。

![数据库结构](https://dn-shimo-image.qbox.me/4ZI2eoE8BbEHr2aK.png)

（注：ID为学校在数据库中的编号，Sname为学校名称，Settime为建校时间，Sdistrict为学校所在的城市，X为纬度，Y为经度，Surl为百科链接，State为学校简介。）

img

图片数据存储于服务器，命名为“高校名称”+.jpg。通过src值获取。

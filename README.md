<p align="center">
<a href="https://github.com/DeerCloud/IPList">
<img src="https://user-images.githubusercontent.com/2666735/50806883-84930c00-1333-11e9-869e-3c2f2664f154.png" />
</a>
</p>

<h1 align="center">IP 地址库</h1>

<p align="center">数据基于 IPIP.NET 分类，更新日期 20190109.</p>

<p align=center>
<a href="https://i-meto.com/">Author Website</a> ·
<a href="https://github.com/DeerCloud/IPList">Project Source</a> ·
<a href="https://t.me/metooooo">Telegram Channel</a>
</p>

***

## 分类

### 国家 IP 段

采用 [ISO_3166-1](https://zh.wikipedia.org/wiki/ISO_3166-1%E4%BA%8C%E4%BD%8D%E5%AD%97%E6%AF%8D%E4%BB%A3%E7%A0%81) 进行分类

|IDC|CIDR|
|---|---|
|中国 (CN)|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/country/CN.txt|
|中国香港|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/country/HK.txt|
|美国|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/country/US.txt|
|日本|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/country/JP.txt|
||[ > 查看更多](https://github.com/DeerCloud/IPList/tree/master/data/country)|

### 大陆 IP 段

相比较国家 IP 段，数据经过精简合并

|IDC|CIDR|
|---|---|
|中国 (CN)|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/special/china.txt|

### 省级 IP 段

采用 [行政区划代码](http://www.mca.gov.cn/article/sj/xzqh/2019/201901-06/20190203221738.html) 进行分类，如广东省为 440000

|IDC|CIDR|
|---|---|
|北京市|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/cncity/110000.txt|
|浙江省|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/cncity/330000.txt|
|广东省|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/cncity/440000.txt|
||[ > 查看更多](https://github.com/DeerCloud/IPList/tree/master/data/cncity)|

### 市级 IP 段

采用 [行政区划代码](http://www.mca.gov.cn/article/sj/xzqh/2019/201901-06/20190203221738.html) 进行分类，如广东省为 440000，广州市为 440100

|IDC|CIDR|
|---|---|
|广东省广州市|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/cncity/440100.txt|
|广东省深圳市|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/cncity/440300.txt|
|广东省佛山市|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/cncity/440600.txt|
||[ > 查看更多](https://github.com/DeerCloud/IPList/tree/master/data/cncity)|

由于免费 IP 库无法达到区县级精度，因此不做更细化的分类

### Anycast IP 段

数据由纯真、IPIP.net 综合分析整理而成，CIDR 段不作合并处理，不定期更新

|IDC|CIDR|
|---|---|
|Anycast|https://cdn.jsdelivr.net/gh/deercloud/iplist/data/special/anycast.txt|

## 致谢

 - 感谢 [淘宝IP](http://ip.taobao.com/) 提供免费 IP 接口
 - 感谢 [纯真](http://cz88.net/) 提供离线数据库参考
 - 感谢 [IPIP.NET](https://www.ipip.net/) 提供的免费 IP 离线数据库
 - 感谢 [IP2](https://github.com/metowolf/IP2) 项目提供 datx 数据库格式的读取工具
 - 感谢 [IPDB](https://github.com/metowolf/ipdb) 项目提供 ipdb 数据库格式的读取工具
 - 感谢 [IPDB-range](https://github.com/metowolf/ipdb) 项目提供 ipdb 数据库格式的分段工具

## 说明

由于许可原因，项目脚本源码不作开源，请谅解。

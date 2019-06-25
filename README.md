<p align="center">
<a href="https://github.com/metowolf/IPList">
<img src="https://user-images.githubusercontent.com/2666735/50806883-84930c00-1333-11e9-869e-3c2f2664f154.png" />
</a>
</p>

<h1 align="center">IP 地址库</h1>

<p align="center">数据基于 IPIP.NET 分类，更新日期 20190601.</p>

<p align=center>
<a href="https://i-meto.com/">Author Website</a> ·
<a href="https://github.com/metowolf/IPList">Project Source</a> ·
<a href="https://t.me/metooooo">Telegram Channel</a>
</p>

***

## 分类

### 国家 IP 段

采用 [ISO_3166-1](https://zh.wikipedia.org/wiki/ISO_3166-1%E4%BA%8C%E4%BD%8D%E5%AD%97%E6%AF%8D%E4%BB%A3%E7%A0%81) 进行分类

|Country|CIDR|
|---|---|
|中国 (CN)|https://raw.githubusercontent.com/metowolf/IPList/master/data/country/CN.txt|
|中国香港|https://raw.githubusercontent.com/metowolf/IPList/master/data/country/HK.txt|
|美国|https://raw.githubusercontent.com/metowolf/IPList/master/data/country/US.txt|
|日本|https://raw.githubusercontent.com/metowolf/IPList/master/data/country/JP.txt|
||[ > 查看更多](https://github.com/metowolf/IPList/tree/master/docs/country.md)|

### 大陆 IP 段

相比较国家 IP 段，数据经过精简合并

|Country|CIDR|
|---|---|
|中国 (CN)|https://raw.githubusercontent.com/metowolf/IPList/master/data/special/china.txt|

### 省级 IP 段

采用 [行政区划代码](http://www.mca.gov.cn/article/sj/xzqh/2019/201901-06/201906211048.html) 进行分类，如广东省为 440000

|City|CIDR|
|---|---|
|北京市|https://raw.githubusercontent.com/metowolf/IPList/master/data/cncity/110000.txt|
|浙江省|https://raw.githubusercontent.com/metowolf/IPList/master/data/cncity/330000.txt|
|广东省|https://raw.githubusercontent.com/metowolf/IPList/master/data/cncity/440000.txt|
||[ > 查看更多](https://github.com/metowolf/IPList/tree/master/docs/cncity.md)|

### 市级 IP 段

采用 [行政区划代码](http://www.mca.gov.cn/article/sj/xzqh/2019/201901-06/20190203221738.html) 进行分类，如广东省为 440000，广州市为 440100

|City|CIDR|
|---|---|
|广东省广州市|https://raw.githubusercontent.com/metowolf/IPList/master/data/cncity/440100.txt|
|广东省深圳市|https://raw.githubusercontent.com/metowolf/IPList/master/data/cncity/440300.txt|
|广东省佛山市|https://raw.githubusercontent.com/metowolf/IPList/master/data/cncity/440600.txt|
||[ > 查看更多](https://github.com/metowolf/IPList/tree/master/docs/cncity.md)|

由于免费 IP 库无法达到区县级精度，因此不做更细化的分类

### Anycast IP 段

数据由纯真、IPIP.net 综合分析整理而成，CIDR 段不作合并处理，不定期更新

|IDC|CIDR|
|---|---|
|Anycast|https://raw.githubusercontent.com/metowolf/IPList/master/data/special/anycast.txt|


## 数据来源

|采信源|文件|版本|条目|
|---|---|---|---|
|IPIP.NET|ipip_temp.ipdb|2019060103|5734260|
|纯真数据库|qqwry.ipdb|20190620|917601|
|纯真数据库|qqwry.raw.ipdb|20190620|1081472|
|MaxMind|GeoLite2-City.mmdb|20190625|3759530|

## 致谢

 - 感谢 [淘宝IP](http://ip.taobao.com/) 提供免费 IP 接口
 - 感谢 [纯真](http://cz88.net/) 提供离线数据库参考
 - 感谢 [MaxMind](https://dev.maxmind.com/geoip/geoip2/geolite2/) 提供的 GeoLite2 数据库参考
 - 感谢 [IPIP.NET](https://www.ipip.net/) 提供的免费 IP 离线数据库
 - 感谢 [IP2](https://github.com/metowolf/IP2) 项目提供 datx 数据库格式的读取工具
 - 感谢 [IPDB](https://github.com/metowolf/ipdb) 项目提供 ipdb 数据库格式的读取工具
 - 感谢 [IPDB-range](https://github.com/metowolf/ipdb) 项目提供 ipdb 数据库格式的分段工具
 - 感谢 [maxmind](https://www.npmjs.com/package/maxmind) 项目提供 mmdb 数据库格式的读取工具

## 说明

由于许可原因，项目脚本源码不作开源，请谅解。

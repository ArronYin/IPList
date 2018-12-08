<p align="center">
<img src="https://user-images.githubusercontent.com/2666735/46994002-eda82080-d144-11e8-873b-f568e4bdae8c.png">
</p>


# IP 地址库

基于 [IP2](https://github.com/metowolf/IP2) 项目分类的 IP 地址库

**数据更新日期：20181208 (IP2)**

## 分类

### 国家 IP 段

采用 [ISO_3166-1](https://zh.wikipedia.org/wiki/ISO_3166-1%E4%BA%8C%E4%BD%8D%E5%AD%97%E6%AF%8D%E4%BB%A3%E7%A0%81) 进行分类

详见 https://github.com/DeerCloud/IPList/tree/master/data/country

|IDC|CIDR|
|---|---|
|中国 (CN)|https://raw.githubusercontent.com/deercloud/IPList/master/data/country/CN.txt|
|中国香港|https://raw.githubusercontent.com/deercloud/IPList/master/data/country/HK.txt|
|美国|https://raw.githubusercontent.com/deercloud/IPList/master/data/country/US.txt|
|日本|https://raw.githubusercontent.com/deercloud/IPList/master/data/country/JP.txt|

### 大陆 IP 段

相比较国家 IP 段，数据经过精简合并

|IDC|CIDR|
|---|---|
|中国 (CN)|https://raw.githubusercontent.com/deercloud/IPList/master/data/special/china.txt|

### 省级 IP 段

采用 [行政区划代码](http://www.mca.gov.cn/article/sj/xzqh/2018/201804-12/20180810101641.html) 进行分类，如广东省为 440000

详见 https://github.com/DeerCloud/IPList/tree/master/data/cncity

|IDC|CIDR|
|---|---|
|北京市|https://raw.githubusercontent.com/deercloud/IPList/master/data/cncity/110000.txt|
|浙江省|https://raw.githubusercontent.com/deercloud/IPList/master/data/cncity/330000.txt|
|广东省|https://raw.githubusercontent.com/deercloud/IPList/master/data/cncity/440000.txt|

### IDC 段

详见 https://github.com/DeerCloud/IPList/tree/master/data/idc

|IDC|CIDR|
|---|---|
|阿里云|https://raw.githubusercontent.com/deercloud/IPList/master/data/idc/alicloud.txt|
|腾讯云|https://raw.githubusercontent.com/deercloud/IPList/master/data/idc/tencentcloud.txt|
|DigitalOcean|https://raw.githubusercontent.com/deercloud/IPList/master/data/idc/digitalocean.txt|


## 致谢

 - 感谢 [淘宝IP](http://ip.taobao.com/) 提供免费 IP 接口
 - 感谢 [IPIP.NET](https://www.ipip.net/) 整理提供的 IP 离线数据库
 - 感谢 [IP2](https://github.com/metowolf/IP2) 项目提供 datx 数据的读取工具

## 说明

由于许可原因，项目脚本源码不作开源，请谅解。

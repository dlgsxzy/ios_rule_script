# Global

## 前言

本项目的Global分流规则由爬虫程序自动维护。

定时爬取互联网上开源的Global分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。



最后检查时间：2020-12-31 03:52:27。

## 规则统计

总计规则：781 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN-SUFFIX | 687 |
| DOMAIN-KEYWORD | 18 |
| IP-CIDR | 27 |
| IP-CIDR6 | 3 |
| DOMAIN | 45 |
| PROCESS-NAME | 1 |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Clash 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global.yaml

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/Global/Global.yaml

## 重复统计

Global分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Adobe)    | 34   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   2.94% |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Advertising)    | 49293   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   0.01% |
|  [AdvertisingTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AdvertisingTest)    | 68638   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   0.01% |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AdvertisingLite)    | 20699   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   0.01% |
|  [AppStore](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AppStore)    | 2   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Apple)    | 33   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   3.03% |
|  [AppleBlock](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AppleBlock)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Bahamut](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Bahamut)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/BlackList)    | 768   | [234](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   30.47% |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/China)    | 596   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   0.5% |
|  [ChinaTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/ChinaTest)    | 72654   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   0.01% |
|  [Discord](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Discord)    | 6   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   50.0% |
|  [Dubox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Dubox)    | 2   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Facebook](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Facebook)    | 25   | [25](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [PayPal](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/PayPal)    | 4   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   50.0% |
|  [Steam](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Steam)    | 16   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   6.25% |
|  [Game](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Game)    | 29   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   13.79% |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Google)    | 121   | [55](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   45.45% |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/YouTube)    | 9   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   55.56% |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Microsoft)    | 88   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   5.68% |
|  [OneDriver](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/OneDriver)    | 17   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   35.29% |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Niconico)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Speedtest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Speedtest)    | 4   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   25.0% |
|  [Telegram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Telegram)    | 14   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   71.43% |
|  [Netflix](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Netflix)    | 38   | [27](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   71.05% |
|  [Disney](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Disney)    | 6   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   66.67% |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/GlobalMedia)    | 237   | [133](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   56.12% |
|  [Github](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Github)    | 6   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   66.67% |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Spotify)    | 7   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   85.71% |
|  [Spark](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Spark)    | 5   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   40.0% |
|  [TestFlight](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/TestFlight)    | 3   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   33.33% |
|  [Twitter](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Twitter)    | 11   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   90.91% |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Proxy)    | 6014   | [516](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   8.58% |
|  [Instagram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Instagram)    | 2   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   100.0% |
|  [Wikipedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Wikipedia)    | 12   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   41.67% |
|  [Whatsapp](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Whatsapp)    | 21   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   9.52% |
|  [Amazon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Amazon)    | 24   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   16.67% |
|  [BBC](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/BBC)    | 3   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   66.67% |
|  [Developer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Developer)    | 23   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global_Repeat.list)   |   8.7% |
### 特别说明
程序在实际运算时，会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6间的包含关系进行去重，而出于运行效率考虑，重复规则只统计纯文本匹配，所以可能与实际效果有所出入，仅供参考。

## 数据来源

本项目的Global分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的Global分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/GlobalMedia.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Global.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果您有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 程序特点

### 断链处理

对于某些已删除或失效的数据源，继续使用本地缓存的文件，减少因为断链造成的影响。

### 规则过滤

通过关键字、正则、模糊匹配三种方式对规则进行过滤，以移除部分数据源中的错误规则。

### 合并去重

不仅对完全相同的规则进行去重，还会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6等规则间的包含关系进行合并去重。

### 域名解析

对DOMAIN类型的规则进行DNS解析记录查询，丢弃连续多次无法解析的域名。

### 正则合并

通过程序对相似正则进行合并，不定时手动核验正则合并结果。

### 正则推导

通过程序对含有正则的规则，推导需要MITM的主机名，不定时手动核验推导结果。

### 正则编译

通过程序对正则类型的规则进行编译，去除无法通过编译的正则。

## 最后

### 完善规则

如果您：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的Global分流规则。

感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) 

提供规则数据源及改进建议

### 其他问题

爬虫开发的初衷是为满足自己几方面需求：

1. 去除混用多个去广告规则造成的重复
2. 去除多个去广告规则中某些规则
3. 多个分流规则间重复情况检查
4. 定时同步数据源更新

本项目的分流规则还是以自用为主，请不要对外宣传此分流规则。所以，还是请低调使用吧。
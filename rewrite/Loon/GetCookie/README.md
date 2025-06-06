# 获取签到脚本Cookie

## 前言

本项目的获取签到脚本Cookie复写规则由爬虫程序自动维护。

定时爬取互联网上开源的获取签到脚本Cookie复写规则，将其进行清洗、去重、合并、优化后，形成单一的复写规则文件，旨在解决引用大量外部规则造成规则重复的问题。

**含有我自己所有签到脚本的GetCookie复写。**


最后检查时间：2020-12-31 03:52:35。

## 复写统计

| 类型 | 数量(条) |
| ---- | ---- |
| mitm | 20 |
| http-request | 17 |
| http-response | 2 |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Loon 

实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rewrite/Loon/GetCookie/GetCookie.plugin

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rewrite/Loon/GetCookie/GetCookie.plugin

如果稳定版无法访问 ，可能是尚未从实时版的分支合并，建议您先使用实时版，或等待下次稳定版分支合并。

## 数据来源

本项目的获取签到脚本Cookie复写规则的数据来自以下链接，通常已涵盖所有数据来源的复写规则。如果你正在使用这些复写规则，请先删除后再使用本项目的获取签到脚本Cookie复写规则，以免造成规则重复。

- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/10010/unicom_checkin.sgmodule
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/didachuxing/didachuxing_plus.lnscript
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/didichuxing/didi_checkin.sgmodule
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/dingdong/dingdong_checkin.sgmodule
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/eleme/eleme_daily.sgmodule
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/famijia/famijia_checkin.sgmodule
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/jiazhangbang/jiazhangbang_checkin.sgmodule
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/luka/luka_signin.sgmodule
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/manmanbuy/manmanbuy_checkin.lnscript
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/meituan/maicai_checkin.sgmodule
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_checkin.sgmodule
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/tieba/tieba_checkin.sgmodule
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/wanda/wanda_checkin.lnscript


感谢以上复写规则作者的辛勤付出（排名不分先后）。

如果你有更好的复写规则，欢迎提交给我，我会将它加到数据源中继续完善。

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

通过程序含有正则的规则，推导需要MITM的主机名，不定时手动核验推导结果。

### 正则编译

通过程序对正则类型的规则进行编译，去除无法通过编译的正则。

## 最后

### 完善复写

如果你：

1. 有更优的原始复写数据
2. 有更多的黑名单复写数据
3. 有更好的优化建议
4. 在使用复写规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的获取签到脚本Cookie复写规则。

感谢

[@Tartarus2014](https://github.com/Tartarus2014)  [@chenyiping1995](https://github.com/chenyiping1995) 

提供规则数据源及改进建议
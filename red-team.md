# 安全蓝军岗位

#### 蓝军认知

- ★★★★☆ 安全蓝军和常规渗透测试的差异是什么？

- ★★★★☆ 蓝军如何体系建设？

- ★★★☆☆ 如何在有限的人力下最大化突出蓝军价值？

#### 信息收集

- **★★☆☆☆ 如何通过程序判断一批域名是否是泛解析域名？**

**提示：**查询一个绝对不存在域名的A记录，比如`enumsubdomain-feei.feei.cn`，根据是否返回IP来判断是否是泛解析（若返回IP则是泛解析域名）。

- **★★☆☆☆ 单机上进行域名爆破存在什么缺陷？**

提示：会导致IP的遗漏，有些域名为增加网站的访问速度，会针对不同线路（电信、联通、移动、教育）解析不同IP。

- **★★☆☆☆ GitHub中可根据企业哪些特征进行搜索？**

提示：内部域名，内网接口使用的域名、测试域名等，比如`feei.cn`；外部域名，对外使用的域名，可以选一些风险较高的，比如`mail.feei.cn`；代码版权，代码头部注释中的版权声明，比如`Copyright 2018 Feei. All Rights Reserved`；主机域名，服务器HOST域名，比如`goods.db.feei.host`；代码包名，Java代码包名，比如`com.feei.goods`；

- **★★☆☆☆ 如何找到某个人的联系方式？**

**提示：**新浪微博私信、知乎、搜索引擎、公众号、LinkIn、天眼查、Whois、上市财报等渠道

#### 漏洞原理

漏洞原理部分同**应用安全岗位**

#### 攻击入口

- ★★☆☆☆ 各种常见木马的的优劣势？

- ★★★☆☆ 木马免杀有哪些方式？哪种方式最有效？

- ★★★☆☆ 木马隧道有哪些？哪种隧道在当前最有效？

- ★★☆☆☆ Word DDE和Office宏有什么优劣势？

- ★★★☆☆ 如何绕过Office受保护视图？

- ★★★☆☆ 有哪些有效的钓鱼方式？

- ★★☆☆☆ 如何绕过WAF、HIDS、威胁感知，选其一回答？

- ★★☆☆☆ BadUSB原理及局限？

#### 出网

- ★★☆☆☆ 如何在禁止出网的机器上访问互联网？

- ★★☆☆☆ ew、frp差异？

- ★★☆☆☆ ICMP如何出网？

- ★★☆☆☆ 如何进行水坑攻击？

- ★★☆☆☆ 如何利用XSS让影响最大化？

#### 行为

- ★★☆☆☆ 如何全流程最大限度降低被红军发现概率？
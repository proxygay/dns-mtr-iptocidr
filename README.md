# MTR-CWB-IPS
通过本地MTR查询收集所有DNS路由路径的IP和域名，转化成对应的CIDR，区分本地网路由CIDR，骨干网路由CIDR，国际网路由CIDR，实现网络路由线路精准分类，根据自己的本地网络需要添加新的本地网络路由CIDR，骨干网路由CIDR，进行网络路由优化，实现有效网络传输稳定性。

Collect IP and domain names of all DNS routing paths through local MTR query, convert them into corresponding CIDRs, distinguish local network routing CIDRs, backbone network routing CIDRs, and international network routing CIDRs, achieve the precise classification of network routing lines, and add them according to your own local network needs. New local network routing CIDR, backbone network routing CIDR, network routing optimization, to achieve effective network transmission stability.

DNS数据来源:（DNS data source:）

https://cloud.tencent.com/developer/article/1352604?from=15425

https://www.increasebroadbandspeed.co.uk/usa-isp-best-public-dns-server-settings

IP地址库来源:（IP address library source:）

https://bgp.space/

CIDR数据反查:（CIDR data reverse check:）

https://bgp.he.net/

https://ipinfo.io/8.8.8.8

https://db-ip.com/as15169

目前数据都是靠手工复制黏贴转换成CIDR和EXCEL数据去重，如果有更好的方法进行MTR的IP数据提取和分类、转换CIDR，希望得到指导，谢谢。
全面的收集MTR中间路由IP和域名，数据量巨大，需要大家的共同努力。

At present, the data are manually copied and pasted into CIDR and EXCEL data to deduplicate. If there is a better way to extract and classify MTR IP data and convert CIDR, I hope to get the guidance, thank you.
A comprehensive collection of MTR intermediate routing IPs and domain names requires the joint efforts of everyone.

https://github.com/proxygay/dns-mtr-iptocidr/releases

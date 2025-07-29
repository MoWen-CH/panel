变量	用法
UUID	必要；在线生成 ，用于生成 VLESS 节点配置
PROXY_IP	必要；旧版本是PROXYIP，查是否有效
TR_PASS	必要；密码，用于生成 Trojan 节点配置
kv	必要；KV命名空间
/panel	在 url 后面增加/panel访问面板
SUB_PATH	订阅的 URI
FALLBACK	后备域
DOH_URL	核心 DOH

代理IP的变量：v3.1.4 及以下称为旧版本为PROXYIP，v3.2.0 及以上版本为PROXY_IP。
来自大佬分享的PROXYIP：bpb.yousef.isegaro.com、ts.hpc.tw、cdn.xn--b6gac.eu.org、cdn-all.xn--b6gac.eu.org、bestproxy.onecf.eu.org、proxyip.cmliussss.net。
试问面板：/panel，部署成功后，在 url 后面增加/panel来进行访问面板，访问面板修改的密码将会保存在kv对里。
面板设置要注意：v3.2.0 及以上版本，IP/域名用回车键ENTER分隔；v3.1.4 及以下版本，IP/域名用英文逗号,分隔。

检测PROXYIP:
https://www.nslookup.io/domains/ts.hpc.tw/dns-records/#cloudflare

详细：
https://github.com/Setout8/Book-Pen-Book?tab=readme-ov-file

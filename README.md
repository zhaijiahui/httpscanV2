# httpscan

httpscan是一个扫描指定CIDR网段的Web主机的小工具。

httpscan会返回IP http状态码 Web容器版本 以及网站标题。




**Usage**：`./httpscan IP/CIDR –t threads`

Example:`./httpscan.py 10.20.30.0/24 –t 10`



fork#20200521

- httpscan.py
	- 原版本，修复卡死问题
- httpscanV2.py
	- 增加常见的HTTP端口内容爬取



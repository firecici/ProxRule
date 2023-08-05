# ProxRule
https://raw.githubusercontent.com/firecici/ProxRule/master/Shadowrocket.conf


https://raw.githubusercontent.com/firecici/ProxRule/master/gfwlist.txt
https://tool.oschina.net/encrypt?type=3
gfwlist.txt是一个文本文件，用于存储被防火长城（GFW）屏蔽的网站的列表。它的语法是基于Adblock Plus的过滤规则，可以用于配置代理软件，如SwitchyOmega。12

gfwlist.txt的格式如下：
以!开头的行是注释，不会被解析。

以|开头的行表示完全匹配，例如|http://example.com表示只匹配http://example.com这个网址。

以||开头的行表示匹配域名或子域名，例如||example.com表示匹配example.com及其所有子域名。

以@@开头的行表示例外规则，即不被屏蔽的网址，例如@@||example.com表示不匹配example.com及其所有子域名。

以/开头和结尾的行表示正则表达式规则，例如/^https?:\/\/[^\/]+example\.com/表示匹配以example.com结尾的任意网址。

其他行表示关键字匹配，例如.example.com表示匹配包含.example.com的任意网址。

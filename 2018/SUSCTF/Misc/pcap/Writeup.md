##  pcap

##  Tools

- example
- example

##  Steps

- Step 1

拿到流量包,主要位http协议,看下包含的附件找到一个`flag.zip`的压缩包,再根据流量包的内容发现访问了一个页面输入了账号密码,登陆页面用流量包内的账号密码成功登陆

登陆页面后得到莫斯点马

```
−−−−− ••−• • −•••• ••••• −•••• −••• • −−−−• • ••−−− ••−• −•••• −•−• •−−−− −•••• •−−−− • −−••• −•−• •••−− −−−−• −−••• −−−•• ••••− −−−−− −−−•• −−−•• •−−−− −•••• −••• −−−−−
```


- Step 2

用 http://tool.ph0en1x.com/hashtool/tools.html#conv/ 

得到压缩包密码 `0fe656be9e2f6c161e7c3978408816b0`

- Step 3

解开压缩包得到flag



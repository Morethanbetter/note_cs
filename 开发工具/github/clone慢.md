1. 设置终端的HTTP请求走代理
```shell
// port 换成你自己的端口号
git config --global http.proxy 'socks5://127.0.0.1:1086' 
git config --global https.proxy 'socks5://127.0.0.1:1086'
```
2. git clone 的地址用https地址，不要用SSH地址。


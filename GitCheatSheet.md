# My Git Cheat Sheet
* 先在github gitee上建立代码仓库并拷贝https://githun.com/xxx/xxx.git
* 在本地clone远程的空代码库
```
git clone https://githun.com/xxx/xxx.git
```

在完成了clone文档之后，可以在本地编辑。然后本地提交

```
git add .
git commit -m "some msg"
git push
```

如果提示找不到用户名或者邮箱,需要进行配置

```
git config --global user.name "xxxx"
git config --global user.email "xxxx@xxx.com"
```

如果在提交过程中提示socks错误

![Alt text](./data/giterr_socks5.png?raw=true "sockserr")

这可能是代理问题，一般解决的问题有两种。一般可以先pull一下

```
git pull
``

然后再进行push

```
git push
```

或者修改一下代理（不推荐）

```
git config --global http.proxy 'socks5://127.0.0.1:xxxx'
git config --global https.proxy 'socks5://127.0.01:xxxx'
```

![Alt text](./data/gitshow_proxy.png?raw=true "proxy_status")

总之，遇到push不成功的一般解决思路是
* 先pull
* 本地add
* 本地commit -m
* 远程push
* 再不济，修改代理

![Alt text](./data/gitshow_push_success.png?raw=true "proxy_status")

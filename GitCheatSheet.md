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
git config --global user.name "XXXXX"
git config --global user.email "xxxx@xxx.com"
```
如果在提交过程中提示socks错误
![Alt text](./data/giterr_socks5.png?raw=true "sockserr")

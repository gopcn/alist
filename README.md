**Blank Repl**

```bash
git clone https://github.com/gopcn/alist.git \
&& shopt -s dotglob \
&& mv -b alist-replit/* . \
&& rm -rf *~ alist-replit .git README.md .github \
&& echo "部署成功，点击Run使用。"
```

**获取密码**
```bash
# 随机生成一个密码
./alist admin random
```
```bash
# 手动设置一个密码 `NEW_PASSWORD`是指你需要设置的密码
./alist admin set NEW_PASSWORD
```

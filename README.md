# 设置远程仓库地址
```
git remote add origin https://github.com/xxx/xxx.git
```


# 更换远程仓库地址
```
git remote set-url origin https://github.com/xxx/xxx.git
```

# git push 失败
```
# 可能是因为开VPN导致的本机系统端口号和git的端口号不一致导致的
git config --global http.proxy 127.0.0.1:xxxx   # xxxx为本机系统端口号
git config --global https.proxy 127.0.0.1:xxxx   # xxxx为本机系统端口号
```
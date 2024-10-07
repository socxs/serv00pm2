# alist_repl
Deploy alist on Replit.

temlate：Bash

Add `pkgs.busybox` in *replit.nix*

then

```bash
bash <(curl -s https://raw.githubusercontent.com/k0baya/alist_repl/main/test.sh)
```
## Update alist version
The same command above.
## Set password
Add a Secret in Tool box.
|Key|Value|
|-|-|
|PASSWORD|Your password|

# Deploy pm2 on serv00

```bash
bash <(curl -s https://raw.githubusercontent.com/socxs/serv00pm2/main/serv00/install-pm2.sh)
```

## 卸载PM2步骤
停止所有PM2进程：
1. 在卸载PM2之前，建议先停止所有正在运行的PM2进程。可以使用以下命令：
```
pm2 stop all
```
2. 使用npm全局卸载PM2：
```
npm uninstall -g pm2
```
3. 删除PM2相关文件：
```
rm -rf ~/.pm2
```
4. 检查PM2是否已卸载：
运行以下命令，确保PM2已被成功卸载：如果PM2已被卸载，系统会提示找不到该命令。
```
pm2 --version
```

# Deploy alist on serv00

```bash
wget -O alist-freebsd.sh https://raw.githubusercontent.com/k0baya/alist_repl/main/serv00/alist-freebsd.sh && sh alist-freebsd.sh
```

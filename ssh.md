# ssh



### 概述

ssh多用于远程登录,英文为Secure Shell 安全协议外壳

### 释义

| 命令 |   英文释义   |   参数   |
| :--- | :----------: | :------: |
| ssh  | Secure Shell | -p -x -X |

```bash
ssh wangfpp@172.16.1.110
# 用于本机登录远程172.16.1.110的wangfpp账号 过程需要ssh验证

ssh -X wangfpp@172.16.1.110
# -X参数标识开启X11转发功能 比如你登录远程机器了 open a.jpg就可以在你本机窗口上显示远程的ajpg文件
# -x 标识关闭x11转发功能

ssh -p 22 wangfpp@172.16.1.110
# -p 表示指定远程的端口
```

### 解决超时问题

### [ssh timeout](https://www.cnblogs.com/williamjie/p/9996946.html)
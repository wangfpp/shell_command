# scp

### 概述

scp和cp类似只是多了一个s, super copy超级拷贝,一般用于远程文件的拷贝

### 释义

| 命令 |  英文释义  | 参数 |
| :--- | :--------: | :--: |
| scp  | super copy |  -r  |



```bash 
# scp多用于对远程文件的拷贝 可以吧本地文件拷贝到远程
# 也可以把远程文件拷贝到本地  过程中需要ssh验证

scp ./a.txt wangfpp@172.16.1.110:./work/
# 意思为把本地当前目录的a.txt文件拷贝到 远程机器 172.16.1.110  wangfpp账户的work目录下,过程中需要ssh验证 得输入远程账户的密码才可以

scp wangfpp@127.16.1.110:./work/index.js  ./
# 把远程机器wangfpp账户下 work目录的index.js 拷贝到本地当前目录下

scp -r ./build wangfpp@172.16.1.110:./work/ 
# 把当前目录下的build文件夹内及全部内容拷贝到 远程目录work下  -r为通用的递归
```


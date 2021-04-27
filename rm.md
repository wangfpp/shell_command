# rm



### 概述

rm的英文是remove删除的意思 就是删除文件的意思

### 释义

| 命令 | 英文释义 | 参数  |
| :--: | :------: | :---: |
|  rm  |  Remove  | -r -f |



```bash
rm ./a.txt
# 删除 当前目录的a.txt文件

rm -r ./build/*
# 删除当前目录下build内的全部内容 可以支持过滤 *.js *.md等 -r 是递归的意思

rm -rf ./build/*
# 强制删除build内的所有内容 -f 是force的意思  删库跑路用的就是rm -rf *了 千万要慎用
```


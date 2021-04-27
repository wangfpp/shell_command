# cat

### 概述

cat的英文为concatenate 意思为连接 连在一起, 长用于把读取文件并打印到标准输出设备上

### 释义

| 命令 | 英文 | 参数  |
| :--: | :--: | :---: |
| cat  |      | -n -b |

```bash

cat ./a.txt
# 把a.txt的内容输出到终端上

cat ./a.txt > ./b.txt
# 实现把a.txt的内容覆盖写入b.txt 这里的 >  是清空重写

cat ./a.txt >> ./b.txt
# >> 就是追加的意思了 b.txt的末尾继续写入a.txt的内容

# -n标识对输出行号进行编号
# -b标识对于空白行不进行编号

# 清空一个文件
cat /dev/null > ./a.txt   
# /dev/null是一个空设备文件 它丢弃一切写入的数据

# windows Get-Content  || type
```


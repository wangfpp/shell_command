# wc

### 概述

wc的英文为word count,用于计算文件的Byte数、单词数、行数等

### 释义

| 命令 |    英文    |    参数     |
| :--: | :--------: | :---------: |
|  wc  | word count | -b -c -l -w |

 ```bash
wc ./release.sh
# 28      69     571 ./release.sh  输出的为release.sh的行数 单词数  字节数

wc -l ./release.sh
# 统计行数 28 ./release.sh

wc -b ./release.sh
# 571 ./release.sh -b或者-c输出文件含有的字节数

wc -w ./release.sh
# 69 ./release.sh  输出含有的单词数 
 ```


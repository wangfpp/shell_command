# tree

### 概述

tree的英文就是tree 用于以树状结构列出目录下的内容

### 释义

| 命令 | 英文 |   参数   |
| :--: | :--: | :------: |
| tree | tree | -I -L -a |

 ```bash
tree ./
# 列出当前目录的所有目录结构

tree ./ -L 2
# 列出当前目录最多两级的目录结构

tree ./ -I "node_modules"
#  列出当前目录下除node_modules目录的素有目录结构  多个排除想以 | 分割

tree ./ -I "node_modules" -A
# 使用ASNI绘图字符显示树状图

tree ./ -I "node_modules" -C
# 给输出加上颜色辨识  与-n相反 -n为不输出颜色

 ```


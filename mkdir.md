## mkdir

### 概述
mkdir的英文为make directory的缩写,功能为创建目录

### 释义

| 命令 | 英文释义 |   参数  |
| :---  |   :---:    |   :---:   |
| mkdir | make directory | -p -m  |


```bash
mkdir javascript
# 在当前目录创建了一个名为javascript的目录

mkdir -p javascript/asset/js/
# -p或--parents 若创建的目录上层目录未创建则一并创建

mkdir -m 700 a.txt
# -m或--mode 为为a.txt指定mode权限
```
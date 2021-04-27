## cp

### 概述
cp的英文为copy,显而易见就是copy的意思,拷贝源文件/文件夹到指定目录

### 释义

| 命令 | 英文释义 |   参数  |
| :---  |   :---:    |   :---:   |
| cp | copy | -r/-R -f -i -u  |

```bash
# cp 后跟[option]参数和两个目录 第一个为源文件目录 第二个为目标目录  相对目录和绝对目录都可以

cp ./index.js ../css/
# 意思为把当前目录的index.js 拷贝到上级目录的css文件夹下

cp -r ./js/ /home/work/
# -r是递归的意思 上面的命令意思为把当前js文件夹下的文件全部拷贝到 绝对目录/home/work目录下

cp -r ./js/m*.js /home/work/
# 可以过滤文件  把js目录下以m头的js文件拷贝
```


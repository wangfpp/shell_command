# pushd



### 概述

pushd用于把操作目录记录, push directroy 一般和popd连用



### 释义

| 命令  |    英文释义    | 参数 |
| :---: | :------------: | :--: |
| pushd | push dorectroy |      |

```bash
cd work
pushd ./build
# 就把build压入了历史记录 期间你可以做其他目录操作  只要你想回到work目录popd就可以了
popd
# popd就可以回到pushd之前的目录了 


```


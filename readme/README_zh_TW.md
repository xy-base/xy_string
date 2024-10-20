<!--
 * @Author: yuyanget 845262968@qq.com
 * @Date: 2024-10-17 20:43:23
 * @LastEditors: yuyanget 845262968@qq.com
 * @LastEditTime: 2024-10-17 20:50:21
 * @FilePath: /xy_string/readme/README_zh_TW.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# xy_string

- [简体中文](README_zh_CN.md)
- [繁体中文](README_zh_TW.md)
- [English](README_en.md)

# 说明
字串工具.

## 程式碼庫

- <a href="https://github.com/xy-base/xy_string.git" target="_blank">Github位址</a>  
- <a href="https://gitee.com/xy-base/xy_string.git" target="_blank">Gitee位址</a>


## 安装

```bash
pip install xy_string
```

## 开始

```python
from xy_string.utils import is_empty_string, empty_string, contains_zh

is_empty_string("")
# true

is_empty_string("empty")
# false

empty_string("empty")
# empty

empty_string(None, default="empty")
# empty

empty_string(None)
# None

contains_zh("中文")
# True

contains_zh("Chinese")
# False

```

## 捐贈

如果小夥伴們覺得這些工具還不錯的話，能否請咱喝一杯咖啡呢?  

![Pay-Total](./Pay-Total.png)

## 聯繫方式

```
微信: yuyangiit
郵箱: 845262968@qq.com
```
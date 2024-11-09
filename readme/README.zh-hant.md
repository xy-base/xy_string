<!--
 * @Author: yuyangit yuyangit.0515@qq.com
 * @Date: 2024-10-17 20:43:23
 * @LastEditors: yuyangit yuyangit.0515@qq.com
 * @LastEditTime: 2024-10-24 10:44:05
 * @FilePath: /xy_string/readme/README.zh-hant.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# xy_string

- [简体中文](../README.md)
- [繁體中文](README.zh-hant.md)
- [English](README.en.md)

# 说明
字串工具.

## 程式碼庫

- <a href="https://github.com/xy-base/xy_string.git" target="_blank">Github位址</a>  
- <a href="https://gitee.com/xy-opensource/xy_string.git" target="_blank">Gitee位址</a>  
- <a href="https://gitcode.com/xy-opensource/xy_string.git" target="_blank">GitCode位址</a>  


## 安装

```bash
# bash
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

## 許可證
xy_string 根據 <木蘭寬鬆許可證, 第2版> 獲得許可。有關詳細信息，請參閱 [LICENSE](../LICENSE) 文件。

## 捐贈

如果小夥伴們覺得這些工具還不錯的話，能否請咱喝一杯咖啡呢?  

![Pay-Total](./Pay-Total.png)

## 聯繫方式

```
微信: yuyangiit
郵箱: yuyangit.0515@qq.com
```
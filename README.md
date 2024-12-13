<!--
 * @Author: yuyangit yuyangit.0515@qq.com
 * @Date: 2024-10-24 09:45:50
 * @LastEditors: yuyangit yuyangit.0515@qq.com
 * @LastEditTime: 2024-10-24 10:43:25
 * @FilePath: /xy-base/xy_string/README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# xy_string

| [简体中文](./README.md)         | [繁體中文](readme/README.zh-hant.md)        |                      [English](readme/README.en.md)          |
| ----------- | -------------|---------------------------------------|


# 说明
字符串工具.

## 源码仓库

| [Github](https://github.com/xy-base/xy_string.git)         | [Gitee](https://gitee.com/xy-opensource/xy_string.git)        |                      [GitCode](https://gitcode.com/xy-opensource/xy_string.git)          |
| ----------- | -------------|---------------------------------------|


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

## 许可证
xy_string 根据 <木兰宽松许可证, 第2版> 获得许可。有关详细信息，请参阅 [LICENSE](LICENSE) 文件。


## 捐赠

如果小伙伴们觉得这些工具还不错的话，能否请咱喝一杯咖啡呢?  

![Pay-Total](./readme/Pay-Total.png)


## 联系方式

```
微信: yuyangiit
邮箱: yuyangit.0515@qq.com
```
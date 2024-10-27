<!--
 * @Author: yuyangit yuyangit.0515@qq.com
 * @Date: 2024-10-17 20:43:23
 * @LastEditors: yuyangit yuyangit.0515@qq.com
 * @LastEditTime: 2024-10-24 10:43:51
 * @FilePath: /xy_string/readme/README_en.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# xy_string

- [简体中文](README_zh_CN.md)
- [繁体中文](README_zh_TW.md)
- [English](README_en.md)

# Description
String tool.

## Source Code Repositories

- <a href="https://github.com/xy-base/xy_string.git" target="_blank">Github</a>  
- <a href="https://gitee.com/xy-base/xy_string.git" target="_blank">Gitee</a>

## Install

```bash
# bash
pip install xy_string
```

## Start

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

## License
xy_string is licensed under the <Mulan Permissive Software License，Version 2>. See the [LICENSE](../LICENSE) file for more info.

## Donate

If you think these tools are pretty good, Can you please have a cup of coffee?  

![Pay-Total](./Pay-Total.png)  


## Contact

```
WeChat: yuyangiit
Mail: yuyangit.0515@qq.com
```
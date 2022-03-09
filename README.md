# proj157-wayland-forbidden-screencopy
### 项目名称
麒麟系统下基于wayland的截图管控

### 支持单位
麒麟软件有限公司

### 项目描述

在银行、国防、政府领域中越来越多使用麒麟操作系统，但目前在系统下用户可以截取屏幕任意区域图像。在某些特定场景中，因为信息安全的需求，需要对截图内容或区域进行一定限制。比如屏幕中某一程序存在用户信息时，在截图时就要进行限制，防止信息泄露。此次目的就是编写实现一个wayland显示协议下的截图管控协议，通过对截图应用、截图范围的限制，从而保护用户隐私数据的安全。

### 所属赛道

2022全国大学生操作系统比赛的“OS功能挑战”赛道


### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生/研究生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求


### 项目导师


陈霖翔:
github id: kylin0061
email: chenlinxiang@kylinos.cn

周磊:
email: zhoulei@kylinos.cn



### 难度

中等


### 特征

- 支持麒麟操作系统
- 基于wayland协议实现
- 截图内容实现应用隐私保护，防止用户信息泄露
- 支持用户自定义设置需保护的应用或需保护的区域



### 参考资料

- https://www.wayland.freedesktop.org
- https://wayland-book.com
- https://xorg.freedesktop.org
- https://www.qt.io

### License

GPL-3.0


## 预期目标

### 说明

题目共分4个子题目，参赛者需要依次完成题目。完成数目越多，质量越高，最终得分越高。

- 题目1：编写wayland下截图管控协议。
- 题目2：实现上述协议，实现在wayland版麒麟影音软件中控制其不能被截图。
- 题目3：实现对外管控接口，便于用户自行进行设置，设置内容包括但不限于功能开启关闭，添加限定区域。并开发管控设置工具，调用管控接口，完成管控设置。管控接口需具有可信校验功能，设置工具通过可信校验后方可进行设置。
- 题目4：基于xwayland，在xwayland中实现题目一中协议，实现对X应用的截图管控。


# 已弃用

左转[Just-Prog/Bilibili_show_ticket_auto_order](https://github.com/Just-Prog/Bilibili_show_ticket_auto_order)

## 说明

Bilibili会员购cp29门票购买脚本,适合蹲退票,只能抢一个人的

脚本不是很完善,只是为了方便购买,在使用时根据自己需求修改

本脚本仅供学习交流使用,不得用于商业用途,如有侵权请联系删除

## 已发现的问题及解决方法

1. 无限显示小电视，哪怕刷新后也是：这种是点击频率过快被banip了，大概要二三十分钟时间解封，在此之前想办法换ip，例如开代理，用流量
2. 验证已过期，请返回详情页重新下单：详见<https://github.com/Hobr/cp_deprecate/blob/main/解决验证问题的方法.pdf>

## 如何使用

1. 下载该项目ZIP文件 <https://github.com/Hobr/cp_deprecate> （Code->Download ZIP）并解压得到文件夹“cp_deprecate” 双击进入文件夹目录
2. 安装Chrome <https://www.google.cn/chrome/>
3. 安装Python 打开<https://www.python.org/downloads/> ,然后点击黄色按钮下载Python
4. 安装时选中“Add Python to PATH”紧接着点击“Customize installation”确保勾选所有可选项后 “Next”
5. 打开终端（Cmd或者Powershell）输入命令``pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple & pip install selenium``
6. 检查您使用的浏览器版本 （打开设置->关于来检查您的浏览器版本）
7. 改完后 在刚刚打开的cmd窗口内输入指令python .\bilibili.py,根据提示操作

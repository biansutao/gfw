# gfw

Shadowsocks PAC 规则
英文：https://adblockplus.org/en/filter-cheatsheet
中文：https://adblockplus.org/zh_CN/filters

# ShadowSocks 自定义规则

如果 GFWList 的自带规则无法满足你的需求，你可以点击 ShadowSocks 选择『编辑GFWList的用户规则』项，使用编辑器打开user-rule.txt文件，在文件中加入你的规则，格式如下：

! Put user rules line by line in this file.
! See https://adblockplus.org/en/filter-cheatsheet
||amazonaws.com
||atom.io

例外规则 @@，如 @@*.example.com/* 满足@@后规则的地址不使用代理

# My Parsers for Clash-for-Windows
参考各路大神的教程和示例，按照自己需求制作的一个预处理（Parsers）配置，与大家共享使用❤️️，有建议的欢迎留言~😄
# 主要功能特色
- 完全重新设计节点线路规划
    - 去除繁杂的设计，返璞归真，该走代理走代理，该直连就直连
    - 各种自动选择模式，省心省力
    - ⚠️注意！会完全删掉你订阅的原本代理也就是节点路线规划（只保留订阅的节点信息）
- 完全个性化对节点进行增删改查
    - 自定义添加节点
    - 自定义删掉节点
    - 自定义节点改名（删掉/替换关键词）
    - 自定义各种节点组合
- 完全个性化对节点组进行组合
    - 可以完全按照自己的需求，对各个节点组进行整理组合
    - 包含/排除+正则形式
    - 自定义安排高倍率节点，不会白白浪费你的流量
    - 若没有相关结点，会出现'🈚️ 无相关节点'提醒并自动添加默认代理
- 美化节点和节点组
    - 因CFW使用默认字体的话，无法完美显示🇨🇳国旗emoji图标，故统一替换成😺动物emoji图标
    - 用emoji表情包美化节点和节点组，一目了然，醒目好看
- 优化规则
    - 结合各路大神的设计，提供更快更好的规则优化
    - 使用大神们提供的规则集（rule-providers），省却自己配置时间和精力
    - 个人自定义规则，方便自己增删改查
- 更多有趣有用的功能，期待你的发掘和提供……

# 界面效果
![QQ截图20240816012425](https://github.com/user-attachments/assets/18e0cafd-2988-42a4-8f47-c402e4ce247e)
![QQ截图20240816015658](https://github.com/user-attachments/assets/3172616c-6da7-4d4b-9848-d2c4b2c38617)

# 使用软件
我用的是Clash for Windows汉化版，理论上支持CFW配置文件预处理的版本均可使用
[下载地址](https://github.com/Z-Siqi/Clash-for-Windows_Chinese)


# 使用用法
直接复制clash parsers.yaml里面的内容到clash的“设置--配置--配置文件预处理”/“setting--profiles--parsers”进行粘贴，执行“配置”/“profiles”页面的更新即可

![QQ截图20240816001436](https://github.com/user-attachments/assets/542f81de-30cd-40ed-ad36-3df83f5f1359)
![QQ截图20240816014338](https://github.com/user-attachments/assets/5fc959d6-fed3-43d9-8274-f5bbfc070ed9)
![QQ截图20240816014519](https://github.com/user-attachments/assets/d8c3b7ce-5e48-4b62-b6e4-02a2bb10af53)

# 删除用法
直接把clash的“设置--配置--配置文件预处理”/“setting--profiles--parsers”里面内容全部删掉，再执行一次“配置”/“profiles”页面的更新即可


# 可能出现的错误和BUG
- 出现rule-providers报错
    - 这种情况一般出现在首次安装使用。原因是一些rule-providers的新建和更新本身就需要代理。
    - 解决方法：先使用CFW默认设置成功代理上网，能够科学上网了再把Parsers配置按照使用方法进行操作，后续使用一般就不会出现了
- 暂时没有了，如果发现欢迎留言交流~


# 特别鸣谢
来自网络的各方力量

[Clash for Windows 汉化版](https://github.com/Z-Siqi/Clash-for-Windows_Chinese)

[CFW配置文件预处理](https://docs.gtk.pw/contents/parser.html)

@blackmatrix7 [blackmatrix7/ios_rule_script: 分流规则、重写写规则及脚本。](https://github.com/blackmatrix7/ios_rule_script)

@Loyalsoldier [Loyalsoldier规则集](https://github.com/Loyalsoldier/clash-rules)


# 特别声明
本软件仅供学习和研究网络技术之用，用户必须遵守所在地区的法律法规，不得用于非法用途，本软件不对任何人的行为负责。 

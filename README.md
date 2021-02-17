# 注意
### 请注意，Git不包含魔改数据库文件，DLC数据文件，需要到群内自行下载。
### 有部分人问如何分离unit目录，如果您是使用我的魔改版，您可以自行到chara_duel中修改，搜索unit，相信您能明白
### 如果您有任何问题，欢迎提issues！如果您对本游戏有好的想法，也可以提，可能的话我会并入主分支亦或是为您开放一个单独的分支
### 我只是在原版基础上进行了一些粗陋的改动，框架是由大佬编写的，在此感谢！
#### 如果您git clone时过慢，也可以使用我自己的gitlab
`git clone http://feite.asia:8099/sdyxxjj123/Pcr_Duel.git`
#### 如果您Releases下载过慢，更推荐去群内或者百度云下载




## 原版注意事项
### 目前为了方便，通过决斗获得女友是可以超过爵位上限的，这个可以自己修改。
### 游戏可能存在bug，python新手多包涵。
### 领金币和查金币指令，与赛跑是一样的，二者的金币也是互通的，如果两个都安可以注释掉一个。
### 贵族签到的每日次数由于hoshino默认，不是跨群独立的，想修改可以自己修改。
### 女友列表就是你自己的_pcr_data列表，减去黑名单列表，可以自己调整不想出现的女友。
### ~~氪金功能没有写在说明书中，最好不要开启，开启氪金十分无聊。~~ 我写了嘤嘤嘤  
### 新增的dlc需相应的pcrdata和unit头像包，我会放在github的release里，我用的pcrdata为旧版，请根据自己的调整。
### ~~如果想自己创建dlc，请在源码中dlc部分，按格式添加，json文件里也需要加个空列表。(这里后续应该会优化)~~ 这个问题已经被解决了
### 新增了在招募时发送角色立绘功能，这个需要角色有立绘包。如果有的话，请在同目录下的fullcard文件夹里，按文件夹中范例，{角色id}31.png的格式添加立绘，如果没有角色立绘，则发送角色头像。

## 贵族决斗指令表
### 注意：仅适用于魔改版，如有改动，请以实际为准
| 关键词     | 作用     |
| :-------------: | :-------------:|
|创建贵族       | 可以在本群创建自己的贵族，会被随机分配一个PCR女友。       |  
|查询贵族 |可以查询自己的贵族状态。
|贵族约会/招募女友 |可以花费500金币招募一个女友，女友数不能超过爵位上限。
|升级贵族/升级爵位 |可以花费金币提升自己的爵位,提升爵位时女友数需已达到上限。
|贵族决斗+@成员 |可以向另一个贵族发起决斗，两个人必须都是贵族且已拥有女友，输者会随机被抢走一个女友。
|领金币 |可以在金币归零时领取150金币。
|查金币 |可以查询自己现在的金币数。
|贵族签到 |可以领取金币和声望，数量与爵位和运气有关。
|为(用户qq)充值xx金币 |可以为该用户充值金币
|重置决斗 |可以解锁决斗开关。(限管理员以上，这个仅用于决斗卡死无法再开的时候)
|查女友+角色名 |可以查询某位角色的归属。
|分手+角色名 |可以和角色分手(需要支付分手费和声望)。
|贵族帮助 |可以查看游戏说明书。
|dlc帮助 |可以查看dlc系统功能
|本群贵族 |可以查看本群贵族统计，剩余女友，及加载dlc的状况
|加冕称帝 |可以由国王提升至皇帝
|飞升成神 |可以由皇帝提升至神
|贵族等级表 |可以查看贵族提升消耗及权利
|为@某人转账xxx金币 |用以向某人转账金币，需要扣除手续费
|用xxx金币与@qq交易女友+角色名|进行女友交易，需要扣除买入方的声望，需要扣除手续费
|声望/金币/女友排行|查看排行榜
|查询庆典|查看目前正在进行的庆典状况
|梭哈支持XX号|是男人就梭哈！投入所有的金币支持某位选手
|扣除QQ号的XXX声望|特殊情况用，扣除某人声望
|声望招募|使用声望必定招募女友
|免费招募|免费招募必定招募一名女友
|皇室婚礼+角色名|和一名角色结婚
|确认离婚|和自己的妻子离婚
|确认重开|删除自己的角色，从头再来
|重置角色qq|删除一名玩家的数据库，令其重新开始
|重置金币qq|清空一名玩家的金币
|设定群XXX为X号死|操盘（这个功能十分无聊，但可以防止人脱坑）
|初始化本群庆典|按照配置内的设置，快速初始化本群庆典
|开启/关闭本群XX庆典|群内开关庆典
|好感帮助|可以查看好感系统帮助
|购买上限 |可以增加女友上限(国王以上可用)

## 魔改版注意事项  
### 原作者地址:https://github.com/Rs794613/PcrDuel
### 魔改版仓库地址:https://github.com/sdyxxjj123/PcrDuel
### 魔改版个人仓库地址:http://feite.asia:8099/sdyxxjj123/Pcr_Duel
### 魔改内容：
- 1.细化了等级分类  
- 2.升级从6级（伯爵）开始需要声望   
- 3.追加飞升成神，成神后不可招募女友，只能掠夺，没有女友上限  
- 4.根据输的人爵位等级，追加胜者金币奖励  
#### V2更新
- 5.加入声望充值，方便测试
- 6.加入离婚系统（需20000金币，4000声望，可自行修改)   
#### V3更新
- 7.加入了认输惩罚，防止互相认输刷声望  
- 8.现在初始建号即初始化声望系统  
- 9.完成分离贵族对决和常驻数据库，修复了季落佬在缝合DLC时的一个BUG  
- 10.加入了等级差机制，根据等级差不同会有不同的收益  
- 11.加入声望排行，金币排行，女友排行  
- 12.加入声望兑换金币  
- 13.加入操盘系统  
- 14.加入梭哈支持  
- 15.现在分手需要声望了，避免一直分手约会刷人物（机器人容易冻结）
- 16.在等级7以上，声望<0时，不能招募女友的声望惩罚  
- 17.提升了声望的获取量  
#### V3.0-fix1更新
- 18.修正了数据库上传的错误 修正了成神可以招募女友的错误  
#### V4.0更新  
- 19.完全重构了庆典系统，现在可以方便的开启庆典，并让群友查询正在进行的庆典信息
**下一步考虑使用群消息就能开关庆典**  
- 20.将部分变量前置，将部分msg的文本改为变量，方便自行修改  
- 21.转账追加手续费系统，手续费的量可以自行设置  
- 22.魔改版兼容原版数据库，不需要再删库了（嘤嘤嘤）  
- 23.增加重开系统 ~~看看有没有绝望的人remake~~    
- 24.加入声望招募系统  
- 25.加入免费~~十连~~招募系统  
- 26.删除了之前版本一些不必要的代码，带来不便还请谅解，之后会将自用代码和发布代码分开  
#### V4.1更新
- 27.chara分离，保证原有自动更新卡池，下载头像正常运行，DLC角色不再尝试下载头像，避免头像不存在时卡机器人  
**分离chara后，如果需要whois插件能查询DLC角色，请自行添加from .. import chara_duel as chara**
- 28.修正了升级贵族不能用的问题~~代码删多了~~嘤嘤嘤
#### V5.0更新
- 29.缝合原版好感度系统，仓库系统（基于原版V0.7-FIX1)
- 30.直接将庆典系统使用数据库实现跨群独立，群内开关。使用前请先**初始化本群庆典**，否则可能会出现问题（测试功能）
**由于我不是很会数据库部分，Python水平也水，代码很乱，如果需要自行迁移，还请搜索开关部分**
- 31.移除了数据库中重名的情况（优先级PCR＞DLC，本名＞别名，别名较多＞别名较少）
- 32.重构了一部分代码
#### 目前在做
成神系统改版方面  
代码优化方面  
开关好感度系统方面  
签到庆典追加好感度礼物方面  
……
#### 由于我和季落佬的一些魔改风格及一些设置不太一样，还请自行改动。部分功能可能禁用。
### 季落佬魔改内容：
1.添加转账功能    
2.添加声望兑换功能    
3.添加女友交易功能   
4.添加扩充女友上限功能  
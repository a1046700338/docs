## 功能列表
|            模块            |               详情               |
|:--------------------------:|:--------------------------------:|
|          botmanage         |              bot管理             |
|            dice            |              掷骰子              |
|         groupmaster        |              群管理              |
|        pcrclanbattle       |             会战管理             |
|      clanbattle_report     |          会战和离职报告          |
|       clanbattle_rank      |             会战排名             |
|         setu_renew         |           new setu插件           |
|           portune          |             运势抽签             |
|         pokemanpcr         |           戳一戳集卡pcr          |
|           aircon           |              群空调              |
|            music           |               点歌               |
|         voiceguess         |        猜语音小游戏cygames       |
|        pcrdescguess        |              猜头像              |
|       pcravatarguess       |              猜群友              |
|        hiumsentences       |              网抑云              |
|          priconne          |                                  |
|      [pcr_calendar](/zh-cn/config?id=pcr_calendar)     |            图形化活动日历插件           |
|         #whattoeat         |             今天吃啥             |
|          #hourcall         |               报时               |
|           #mikan           |            蜜柑计划rss           |

* `#`代表未使用或未实装


## lssv服务一览：
* [x] _feedback_
* [x] antiqks
* [x] asill
* [x] avatarguess
* [x] clanbattle
* [x] clanbattle_rank
* [x] clanbattle_report
* [x] descguess
* [x] dice
* [x] gacha
* [x] github_reminder
* [x] github_reminder_poller
* [x] group-leave-notice
* [x] group-welcome
* [x] hiumsentences
* [x] music
* [x] pcr-arena
* [x] pcr-avatar-guess
* [x] pcr-cherugo
* [x] pcr-comic
* [x] pcr-desc-guess
* [x] pcr-duel
* [x] pcr-login-bonus
* [x] pcr-news-bili
* [x] pcr-news-tw
* [x] pcr-query
* [x] pcr_calendar
* [x] portune
* [x] random-repeater
* [x] sleeping-set
* [x] voiceguess
* [x] 人生重来模拟器
* [x] 戳一戳
* [x] 涩图
* [x] 猜群友
* [x] 空调
* [ ] anti-holo				默认关闭
* [ ] anti-msg-recall		默认关闭
* [ ] pcr-arena-reminder-jp	默认关闭
* [ ] pcr-arena-reminder-tw	默认关闭

lssv查看开启/关闭功能列表
具体应用如下：
开启+空格+功能名称
### 查询角色谁是的问题
具体应用如下：
格式—–谁是xxx
谁是nnk
栞栞会回答似似花

### 猜头像
```
猜头像
```
栞栞会随机发一张PCR角色头像的一部分的图片让你猜，20s后自动公布答案
### 猜角色
```
猜角色
```
栞栞会5秒后每隔12秒我会给出某位角色的一个描述，根据这些描述猜猜她是PCR里的谁，没人答对会公布正确答案
### 猜群友
```
猜群友
```
栞栞会采集群里一位群友头像的一部分让你猜
### 戳一戳
PCR戳一戳集卡，手机QQ双击机器人头像"戳一戳"
### clanbattle_report
```
生成离职报告
生成会战报告
```
使用Yobot API数据生成离职报告和会战报告的HoshinoBot插件,由用户自行指定API地址,可使用任意远程服务器的Yobot数据生成报告.
考虑变更为这个 https://github.com/yoooowi/pcr_autocb
### clanbattle_rank
#### 使用方法
- 查询排名 公会名 [会长名] : 查询指定公会排名
- 查询分段 : 查询分段信息
- 查询关注 : 查询关注的公会信息
- 添加关注 公会名 [会长名] : (需要管理员权限)将指定公会加入关注列表,如有重名需要附加会长名
- 删除关注 公会名 : (需要管理员权限)将指定公会从关注列表中删除
- 清空关注 : (需要管理员权限)清空关注列表
#### 如果要查询或添加关注的公会名或会长名带有空格, 请使用 [] 把名字包起来, 例如 添加关注 [公会名] [会长名], 注意公会名和会长名都要加.
```
查询排名 美少女战士
查询排名 美少女战士 布丁可可
添加关注 美少女战士 布丁可可
添加关注 [内鬼连接] [佑树 挖矿中 刺必还]
查询关注
```
查询公会战排名信息的HoshinoBot插件,使用 wiki.biligame.com API获取数据.
### portune

### music
点歌
```
[点歌 好日子] 点一首歌。
[搜网易云 好日子] 从网易云音乐点一首歌。
[搜QQ音乐 好日子] 从QQ音乐点一首歌。
[搜咪咕音乐 好日子] 从咪咕音乐点一首歌。
[选择 0] 从点歌结果中选择一首。
```
### voiceguess
猜PCR角色语音小游戏，栞栞会发出一段PCR角色语音30s后公布答案
```
猜语音
```
### hiumsentences
以下关键词触发: 上号, 生而为人, 生不出人, 网抑云, 已黑化, 到点了  
会发送一条网抑云语录加一张表情包, 没有表情包也可以发送纯文字  
### aircon

### RSS
订阅

### 群广播
1.g-开头，群号用反斜杠'/'分隔，进行广播  

2.exg-开头，群号用反斜杠'/'分隔，表示除了这几个群不广播，其他群进行广播  

指令：bc/广播 服务名 广播内容，全群广播则输入all bc_recall/广播撤回 撤回两分钟内的所有广播  

```
[bc|广播] [服务名 | g-群号/群号/群号 | exg-群号/群号/群号] 广播内容

```
举两个栗子：
```
栗子1：
bc g-132456456/34851651/25165165 广播内容
```
> 这个会广播132456456/34851651/25165165，这三个群

```
栗子2：
bc exg-1561561351/156161451 广播内容
```
> 这个会广播除了1561561351/156161451以外的所有群  

- 私聊机器人发送'群列表'，可以获得所有加入的群和群号，方便你复制群号

### aichat
人工智障  

|指令|说明|
|-----|-----|
|调整AI概率+数字|调整ai接话的概率|
|关闭人工智障|机器人不再接话|  

at机器人对话必定回复,使用`关闭人工智障`指令后依旧回复,若要彻底关闭使用`禁用 人工智障`指令  

### aircon
空调  
- [开空调] 打开空调（第一次使用时会自动安装空调）
- [关空调] 关闭空调
- [当前温度] 查看当前风速、设定温度、环境温度
- [设置温度 <温度>] 设置空调温度
- [设置风速 <1/2/3> (或者低/中/高)] 设置空调风速（共有三档）
- [设置环境温度 <温度>] 设置环境温度
- [升级空调] 升级空调（家用空调👉中央空调）
- [降级空调] 降级空调（中央空调👉家用空调）
- [空调类型] 查看空调类型（家用空调/中央空调）

### Asill 
A-soul 发病小作文  

真情实感发病小作文选自[枝江作文展](https://asoulcnki.asia/rank)  

感谢[@蓝红心](https://github.com/LHXnois)追加的[小作文查重功能](https://github.com/RMYHY/RBot/pull/1)  

#### 安装
将 `data.json` 与 `asill.py` 至于同一个文件夹并放在 `HoshinoBot/hoshino/modules` 目录下  

修改 `HoshinoBot/hoshino/config/__bot__.py` 文件，在 `MODULES_ON = {}` 配置中添加`'asill'`
```python
# 启用的模块
MODULES_ON = {
    ...
    'asill',
    ...
}
```

#### 使用指南
| 指令 | 说明 |
| --- | --- |
|发病 对象|	发送一篇写给对象的发病小作文
|小作文|	随机发送一篇库存发病小作文
|病情加重 对象/小作文|	将一篇发病小作文添加到数据库中
|病情查重 小作文|	小作文查重
|<回复一个小作文> 病情查重|	小作文查重

添加小作文时对象为小作文中对方的称呼（暂不支持多称呼）且斜杠“/”不可省略  

在群聊中添加小作文可能导致json文件预览无法显示汉字（实际功能正常）建议直接修改原文件  

#### 修改作文
修改`data.json`可自定义修改小作文  
```json
[
    {
        "person":"发病对象1",
        "text":"小作文内容1"
    },
    {
        "person":"发病对象2",
        "text":"小作文内容2"
    }, 
    ...
    ...
    {
        "person":"发病对象n",
        "text":"小作文内容n"
    }
]
```


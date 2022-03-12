# 配置
## hoshinobot插件
### botmanage

### voiceguess
插件地址：
### pcr_calendar
插件地址：https://github.com/zyujs/pcr_calendar
公主连结图形化活动日历插件, 适用于 HoshinoBot v2。  
使用pcr_calendar要将yobot的日程表推送功能给删除否则会引起冲突，而yobot需要使用[源码版](/#/zh-cn/config?id=yobot源码版)而不是[便携版](http://yobot.win/install/Windows-gocqhttp/)。  
- 删掉目录下`...\src\client\ybplugins`的calender.py文件,再修改同目录下的__init__文件,删掉calender字样
- `...\src\client`下的yobot.py文件也要修改，删掉calender  

- **安装方法**

1. 在HoshinoBot的插件目录modules下clone本项目 `git clone https://github.com/zyujs/pcr_calendar.git`
1. 在 `config/__bot__.py`的模块列表里加入 `pcr_calendar`
1. 重启HoshinoBot

- **指令列表**

- `日历` : 查看本群订阅服务器日历
- `[国台日]服日历` : 查看指定服务器日程
- `[国台日]服日历 on/off` : 订阅/取消订阅指定服务器的日历推送
- `日历 time 时:分` : 设置日历推送时间
- `日历 status` : 查看本群日历推送设置
- `日历 cardimage` : (go-cqhttp限定)切换是否使用cardimage模式发送日历图片

## yobot源码版
### 下载
github：https://github.com/yuudi/yobot.git  
压缩包（2021/5/23）：https://cloud.189.cn/t/BreInuZFvy6b (访问码:lq5b)
### 解压缩文件
请使用 py -V 命令确认 python 版本，yobot 支持的 python 版本为 3.6 以上
使用 stable 稳定版分支，下载完毕后解压
https://github.com/yuudi/yobot/archive/refs/heads/stable.zip

进入 （刚 克隆/解压 出的文件夹）\src\client\ 目录，在空白处Shift+右键，点击“在此处打开 PowerShell 窗口”（或者命令提示符）
### 安装依赖  

```
pip3 install -r requirements.txt --user
# 国内可加上参数 -i https://pypi.tuna.tsinghua.edu.cn/simple
```
### 如果hoshinobot报错

```
Ps c: \(users \Administrator\Desktop\kankan\HoshinoBot> py run.py
Traceback (most recent cal7 Tast):
File "run.py",7ine 1. in <moduieimport hoshino
File "c:\(users\Administrator\Desktop\kankan\HoshinoBot\hoshinol_init.py"，1ine 4，in <module>import nonebot
File c: Users\Administrator AppData \LocaT\Programs\Python\Python38 \1ib site-packages [nonebotl_initm.py", 1ine 123,in <moduTe>
def on_websocket_connect(func: Ca1lable[[aiocqhttp.Event],，Awaitable[None])AttributeError: moduTe 'aiocqhttp' has no attribute 'Event'
```
**输入**  

```
py -m pip install -U aiocqhttp
```
### 启动yobot

```
py main.py
```
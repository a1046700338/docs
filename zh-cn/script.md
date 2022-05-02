# 写个小脚本
项目立项  
我学校每天都要健康打卡，很烦，又必须做，每天都在做重复的事情，为什么不写一个脚本帮我完成了呢？  
ProjectName:ClockInHealth  
思路：每天18点，进入微信，右上角点击搜索，搜索“四川工业科技学院”，点击进入公众号，右下角“服务大厅”选择“疫情防控"，选择“学生每日健康填报”，

## adb
查看手机上应用包名
```shell
adb shell pm list packages
```
这个指令会罗列出手机已经安装的所有应用包的名称，如果后缀加上参数-s，则会列出所有的系统应用的名称，而加上后缀参数-3则会列出所有第三方应用名称，如下：
```shell
adb shell pm list package -3
```
显示活动程序
```shell
adb shell dumpsys activity activities
```
图![]()
通过adb启动微信
```
adb shell am start -n com.tencent.mm/.ui.LauncherUI
```
[](https://www.jianshu.com/p/e15b02f07ff2)
[](https://cloud.tencent.com/developer/article/1592050)

## Python操作Android APP
```python
def execute(cmd):
  adb_str="adb shell {}".format(cmd)
  print(adb_str)
  os.system(adb_str)

if __name__ == '__main__':
  execute("am start -n com.tencent.mm/.ui.LauncherUI")
  time.sleep(3)
  execute("input tap 263 515")
  ```

  ## Airtest
  https://airtest.doc.io.netease.com/IDEdocs/3.3record_script/1_how_to_get_started/
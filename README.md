# adb-shell
## 
手机截图： adb exec-out screencap -p > [filename]
进入shell：adb shell
查看当前正在运行的apk包名：adb shell dumpsys window | findstr mCurrentFocus
查看所有已安装的包：
```
adb shell
adb list packages
```

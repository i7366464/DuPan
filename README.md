# DuPan
百度网盘会员签到

参考项目：[tunecc/DuPan](https://github.com/tunecc/DuPan)

# 更改内容

将原项目中使用Telegram机器人通知的代码改为钉钉机器人通知。

# 钉钉通知示例

## 当天第一次成功签到

在这次签到过程中没有回答问题获得经验值的任务，所有显示未找到日常问题或答案。

![image](https://github.com/i7366464/DuPan/blob/main/resources/photo/first.png)

成功完成签到及答题获得经验值。

![image](https://github.com/i7366464/DuPan/blob/main/resources/photo/first-1.png)

## 当天重复签到

![image](https://github.com/i7366464/DuPan/blob/main/resources/photo/repeat.png)

## 连续签到一周每天17点成长值

![image](https://github.com/i7366464/DuPan/blob/main/resources/photo/week.png)

# Cookie获取

打开：https://pan.baidu.com ，F12，网络，main文档里面把cookie，全部弄到变量里面，我的变量为 `XFI=***......ab_sr=***`（只列出了开头和结尾两个变量）。

# 注意

基于Python，需要Cookie。

建议在本地或固定登录百度网盘的设备（包括Windows服务器、Alist）使用，避免多IP风控。

不建议使用云函数，因为动态IP。

虽然百度的大部分风控不影响签到，但是会影响你下载。

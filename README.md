# DIYLocation
虚拟定位，免root，基于太极框架，Android操作指南

内容详情
背景：`FakeLocation`其实很好用，但是需要root/开会员才能避开企业微信钉钉，这类检查比较严格的软件。
下了无数虚拟定位的软件，被无数次忽悠以后不相信所谓的定位软件了，不开会员别想用。
在github找了一些半成品软件对手机兼容性做的又很差，不具备通用性。
后来发现太极的使用非常容易且具有普适性，将操作记录下来，供大家学习参考。在手机折腾圈这个应该是基操了。

手机软件准备：

**1.太极**

[taichi.cool/download.html](https://taichi.cool/download.html)

**2.模块**（cataclysm[包名]/lataclysm[软件名]）

我提供一个云盘链接下载备用 https://wwhr.lanzoul.com/iyXfy136dt9c 密码:9b09

流程：
- **打开**太极，`创建应用`中找到企业微信，点击后会重新下载安装
- `模块管理`中**勾选**lataclysm ；**长按**lataclysm，**点击**`设置生效范围`，**勾选**企业微信
- `模块管理`中点击lataclysm进入模块配置，忽略弹出的提示框
- **点击**`设置` ，**任务一包名添加**`,tencent`;全删了直接输入`tencent`也可以，此处为了识别企业微信
- **点击**`位置`，拉到底选择`00-WGS84`，此选项为自定义地图选点
- **退回到模块主界面**，**点击**`高德地图` ，选取你需要的打卡点，显示保存至`位置00`
- **关闭手机定位**，从太极中打开企业微信，进入打卡，点击外出打卡，识别打卡地点，坐标存在偏差，可以反复纠偏
- 如果定位没有更新：1. 检查以上步骤是否开启；2. 后台关闭企业微信，重新打开

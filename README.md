# GoogleAssistant-smart-home
谷歌语音助手智能家居

## What is GoogleAssistant-smart-home?
you can use google home mini control our smart device - 使用谷歌智能音响控制智能家电设备

### 官方文档
[官方文档-需要翻墙](https://console.actions.google.com/project/smarthomeproject-for-myself001/overview)


### 音响使用步骤

#### 一 google home mini 入网
[配网教程案例-wifi需要翻墙](https://www.znj.com/news/1631.html)

1. google home mini 上电开机，四个灯在闪烁-进入配网状态
2. 在手机上下载 Google Home App，打开app并且登入google账号，app会自动搜索到mini。 (此步骤比较难连接，多试几次)
3. 试一试吧！（四个灯变表示）
   Ok Google !或者 Hey Google !来唤醒她

#### 二 google home mini 添加需要控制的智能家居设备
1. 找到set up （+） 按钮，找到对应的skill。
2. 进行账户授权登录。
3. 给设备分配不同的地点。（厨房，大厅等）
4. 开始控制设备
  例如: turn on light
  
### 开发干货
#### 一 进入Actions Aconsele开发界面
1. 新建一个smart home project
2. 配置需要授权的Auth2.0的登录H5页面、token获取接口、fulfillment接口地址
3. 提供服务接口即可。
4. 测试完毕即可发布，等待谷歌工作人员审核，审核成功之后，Google Home App即可找到自己创建的技能

#### 二 开发实现
[开发文档-需要翻墙](https://developers.google.com/assistant/smarthome/concepts)
1. Authentication: Links your users' Google accounts with user accounts in your authentication system. See fulfillment and authentication.
2. Smart home intent: Simple messaging objects that describe how to perform a smart home Action such as turn on a light or cast audio to a speaker. See smart home intents
3. Fulfillment : A service that handles a smart home intent and carries out the corresponding Action. See fulfillment and authentication. (提供API服务)




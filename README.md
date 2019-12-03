# WeChat_Resource

<img src="snapshots/logo.png" width="256px" height="256px" />

### 一、概述

- 业余时间整理原生`微信App`页面所用到的所有素材（`.png`、`.jpg`、`.svg`、`.js`、`.html`、`iconfont`...），也会从[Iconfont-阿里巴巴矢量图标库](https://www.iconfont.cn/)这里搜刮一些符合`微信App`要求的资源，并且按模块将其归类处理。其目的是：方便日后查询，且能快速定位，节约大量`万里挑一`的时间。

- 自定义(`mock`)一些有趣的`.json`文件（PS：笔者不会后端~），方便开发者能模拟网络请求加载数据，达到和现实开发中同等的需求体验~ 且不需要服务器、不依赖网络连接、不报`500`错误...

  - `user.json`：用户数据, 主要用于用于`登录/注册/我`模块。
  - `world_zone_code.json`：全球手机区号数据，例如：`+86`代表`中国大陆`。 主要用于手机号`登录/注册`，选择区号的模块。
  - `mainframe.json`： `微信`模块的列表数据。主要用于`微信`模块。
  - `contacts.json`： 联系人数据（ps：玩着荣耀所有英雄数据）。 主要用于`联系人`模块。
  - ...

- UI 设计图，来源于笔者`iPhone 7 Plus`真机截屏，以及利用[马克鳗](http://www.getmarkman.com/)设计稿标注、测量。当然，笔者标注的未必页准确，其初心就是方便大家在开发过程中有一个 UI 图参考，以便大家代码编程后的最终呈现效果，达到与你手机 App 的效果无限接近罢了。

- 本仓库创建的目的主要是解决：`当我们学习一门新的编程语言时，苦于没有一个素材资源完整、UI设计图清晰的项目来实战的烦恼`。笔者希望`WeChat_Resource`这个仓库能够消除大家的烦恼，并且能让大家把充足的时间和精力用在编程上，而不是用在素材查找和 UI 设计上。

- 本仓库的所提供的所有资源，都只能用于学习！一切商用都是违法！**别让你肮脏的利欲，熏坏笔者纯洁的初心**

### 项目实战

以下项目的所有 UI 实现，都是利用本仓库提供的资源的实现的，虽然涉及编程语言涵盖：`iOS Objective-C`、`vue.js`、`Flutter`等，但是丝毫不影响最终的呈现效果。同时也说明了，本项目提供的资源的有效性和实用性，消除大家的疑惑和顾虑。

当然，笔者并非是将`微信`App 所有的 UI 界面都标注了，只是标注了平常常用的模块罢了，而且也不是每个模块都会去实现，其初心就是为了学习新的编程语言时，有一个比较完整的项目去实战罢了。当然笔者敢保证的是：若能把笔者提供的 UI 设计图全部实现，那么你所学习的新的编程语言必定能轻车熟路！

- [WeChat](https://github.com/CoderMikeHe/WeChat)：**iOS Objective-C 实现的微信 App**
- [vue-wechat](https://github.com/CoderMikeHe/vue-wechat)：**vue 2.x 实现的微信 App**
- [flutter_wechat](https://github.com/CoderMikeHe/flutter_wechat)： **Flutter 实现的微信 App**

### 参考链接

- [国际区号 json（含国家中英文名称、简称、区号、首拼）](https://blog.csdn.net/qq_42532128/article/details/100072000)

### 预览

###### 闪屏模块

| ![](./snapshots/splash/splash_page_0.png) | ![](./snapshots/splash/splash_page_1.png) | ![](./snapshots/splash/splash_page_2.png) |
| :---------------------------------------: | :---------------------------------------: | :---------------------------------------: |


###### 登陆/注册模块

|    ![](./snapshots/login/login_page.png)    |   ![](./snapshots/login/register_page.png)    |   ![](./snapshots/login/other_login_page.png)   |
| :-----------------------------------------: | :-------------------------------------------: | :---------------------------------------------: |
| ![](./snapshots/login/phone_login_page.png) | ![](./snapshots/login/current_login_page.png) | ![](./snapshots/login/language_picker_page.png) |

###### 微信模块

| ![](./snapshots/mainframe/mainframe_page_0.png) | 虚位以待 | 虚位以待 |
| :---------------------------------------------: | :------: | :------: |


###### 通讯录模块

| ![](./snapshots/contacts/contacts_page_0.png) | ![](./snapshots/contacts/contacts_page_1.png) | ![](./snapshots/contacts/contacts_page_2.png) |
| :-------------------------------------------: | :-------------------------------------------: | :-------------------------------------------: |


###### 发现模块

| ![](./snapshots/discover/discover_page_0.png) | 虚位以待 | 虚位以待 |
| :-------------------------------------------: | :------: | :------: |


###### 我模块

| ![](./snapshots/profile/profile_page_0.png) | ![](./snapshots/profile/user_info_page.png) | ![](./snapshots/profile/more_info_page.png) |
| :-----------------------------------------: | :-----------------------------------------: | :-----------------------------------------: |


###### 设置模块

| ![](./snapshots/setting/setting_page.png)  | ![](./snapshots/setting/account_security_page.png) | ![](./snapshots/setting/message_notify_page.png) |
| :----------------------------------------: | :------------------------------------------------: | :----------------------------------------------: |
| ![](./snapshots/setting/privates_page.png) |     ![](./snapshots/setting/general_page.png)      |  ![](./snapshots/setting/about_wechat_page.png)  |

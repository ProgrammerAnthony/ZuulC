博客原地址： [Android即时通讯和sns开源项目汇总](http://www.jianshu.com/p/b2ca52337fe5)

这是一个整理即时通讯（IM）和社交系统（SNS）优秀开源项目的文档，项目上传github欢迎提交更新。
github地址：[https://github.com/CameloeAnthony/Perfect_IM_SNS](https://github.com/CameloeAnthony/Perfect_IM_SNS)

# 一 国内即时通讯和社交系统平台
排名不分先后！
##### 1 [LeanCloud](https://leancloud.cn/docs/realtime_guide-android.html)
##### 2 [环信](http://www.easemob.com/product/cs?utm_source=baidu-pp)
##### 3 [网易云信](http://netease.im/?&from=bdjjqita0327)
##### 4 [阿里百川 云旺OpenIM](http://im.taobao.com/product_function.html?spm=a1z6j.7801022.0.12.uoMkmF)
##### 5 [腾讯云](https://www.qcloud.com/product/im.html)
##### 6 [融云](http://www.rongcloud.cn/)
##### 7 [Bomb IM](http://docs.bmob.cn/im/faststart/index.html?menukey=fast_start&key=start_im)
##### 8 [OpenSNS](http://www.opensns.cn/)

# 二 基于LeanCloud的开源项目
 
##### 1 [LeanCloud SDK Demos 分类汇总，请点击查看](https://github.com/leancloud/leancloud-demos)
 
# 三 基于环信的即时通讯开源项目
 
数据整理自环信官网，网络数据和github。更多信息请参考[环信官方网站](http://www.easemob.com/product/cs?utm_source=baidu-pp)和[ImGeek](http://www.imgeek.org/)
#### 1 高仿微信：基于环信SDK高仿微信（推荐）
**介绍:**大家见过的网络各种高仿微信，但是这个是真的实现了功能的。群聊，朋友圈，单聊......  这才是你该关注的代码。所以我把它放在第一位，推荐。

**功能模块:**
>消息：订阅号、列表滑动删除、TitleBar弹出菜单单聊，群聊（发送文字，语音，位置，视频，文件，语音电话，视频通话）微信表情、
通讯录：按字母索引排序、添加手机通讯录好友、
发现：二维码扫描添加好友、二维码扫描加入群聊、扫码微信支付、生成自己二维码图片
朋友圈、发布朋友圈信息、购物、游戏、设置WebView与Javascript交互、播放视频、加载HTML5页面FastJson Json转换神器、Imageloader图片加载库、android-async-http 网络请求库、图片缩放查看、加密解密

**效果展示:**

![](http://upload-images.jianshu.io/upload_images/1833901-970232044dbbb466.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
**源码链接:**
https://github.com/motianhuo/wechat
（之前源码链接是我fork的一个链接，请大家直接关注原来的作者的github地址）

#### 2 Baby（推荐）
**介绍:**
这是一款使用了Material　Design和MVP的情侣之间使用的app。这两天把代码看了一下。作者的很多思想很赞，推荐。
**功能模块:**
>属于两个人的朋友圈，
两个人聊天，
登陆注册

**效果展示:**

![](http://upload-images.jianshu.io/upload_images/1833901-84153e8bf12c00c6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
**源码链接:**
https://github.com/rogerou/Baby


#### 3 图忆：基于位置信息的分享与社交应用
**介绍:**图忆是一款基于位置信息的分享与社交应用。实现了将用户记录的不同类型的事件标刻于地图之上，查看自己的记录足迹，同时用户可以轻松查看附近分享的记事，添加好友聊天，建立兴趣圈子，发现志趣相投的好友，并且用户记事可以分享到公共社区平台，分享乐趣的同时也发现了更多的乐趣，社区推荐策略让用户发现更多有价值的乐趣。
**功能模块:**
>【记录记忆】你可以记录自己的生活点滴在地图之上，可以公开给别人看，也可以保存为自己的私有记忆。
【离线记录】没有网络也可以轻松保存离线记录，WIFI连接后直接批量上传，省心
【地图附近】你将通过地图查看到附近用户公开的说有分享记录，当然是直接在地图上展示的哟，很直观的说，还有五个标签分类查询哟，就等你来发现了。
【雷达】发现同时在附近开启雷达的小伙伴，自定义雷达显示的内容，让小伙伴更容易发现你
【聊天圈子】与TA尽情畅聊，兴趣小伙伴建圈子一起聊。
【图忆社区】点赞，评论，分享，收藏Ta的分享

**效果展示:**
![](http://upload-images.jianshu.io/upload_images/1833901-f6ab327e0cff9951.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
**源码链接:** https://github.com/donlan/Tuyi
#### 4 咚咚：一款高效团队沟通的移动客户端
**介绍:**基于环信平台进行开发，旨在打造的高效团队沟通的移动客户端，供企业内部协作使用、适应移动办公需要，提升企业沟通协同效率，增强企业办公管理效率。（当前仅实现了用户登入登出功能、通讯功能、投票功能。）具体功能说明
**功能模块:**
>一、用户登录注册功能
1.系统登录界面
2系统注册界面  
  注册功能实现：限制账号长度必须为11位，出生日期选择，头像选择（从系统自带头像中选择）
3.系统首页    登陆成功，即进入系统主页面
4.个人信息查看及修改    进入主页面后点击个人信息查看，即可查看相关信息，并对其进行修改  
  主界面    
（1）头像修改功能实现   
 （2）名字修改功能实现   
 （3）部门修改功能实现    
（4）性别选择功能实现   
（5）个性签名修改功能实现
二、通讯功能   
 主界面   
 功能实现：群组聊天，单对单私人聊天，查看好友列表，查看好友详情，查看群组详情
三、投票功能    
主界面   
功能实现：展示用户发起的投票列表，新增投票，投票提交。

**效果展示:**
![](http://upload-images.jianshu.io/upload_images/1833901-940809568221bdab.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
**源码链接:**https://github.com/caisiyi/SYTeamApp


#### 5 美肤GO：专注于个人海外代购及护肤咨询分享的APP
**介绍:**希望给爱美向往美的你一个全方位的秘密基地，也希望给想要做全职代购或者兼职代购甚至只是旅游顺便想代购挣回机票钱的我一个平台，源于这个初衷，美肤GO提供高品质的代购机制和最亲民线下般体验的护肤资讯，只为让你更美丽！ 
**功能模块:**
>个人海外代购
美妆美肤课程
社区分享互动等

**效果展示:**

![](http://upload-images.jianshu.io/upload_images/1833901-3fe704a3d2cc909a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
**源码链接:**
https://github.com/Rabbit00/MeifuGO


#### 6 方圆十里：关注方圆十里内的人和事
**介绍:**
基于IM(环信通信云)+LBS(百度地图SDK+GeoHash距离算法)的社交APP
**功能模块:**
>一、功能列表：
1、登录、注册（采用后端授权注册的方式绑定环信id，更安全）
2、用户资料：头像、昵称、性别、生日、地区（本地arrays.xml存储地区数据库）、个性签名
3、Tab1.-“人”---- 百度地图中显示十公里内的人（如果用户位置集中或者人数过少会导致无法测试，因此“更远”选项，搜寻更多，并且本身的十公里概念也未进行筛选）
4、Tab2.“事”----十公里内的动态--文字、图片、位置的动态（发布、回帖、通知提醒）
5、Tab3.“聊”----IM会话
6、Tab4. “友”---通讯录及好友申请
7、我的动态
8、二维码---通过扫二维码加好友
二、特点备注：
1、本项目中采用geohash算法编码用户的位置坐标，达到位置的粗分区，而后进行精确精算实现十公里之内的人和事的概念。
2、创建自定义的百度地图标注。
3、一套将环信IM系统和开发者自身的用户体系融合的解决方案（当前的解决方案在多个项目中得到检验，成熟稳定）。
4、常见的发帖回复模块的处理解决。
5、利用环信的透传消息进行用户的帖子发布、回复等提醒通知。（待更新）
6、UI优化，如电话聊天背景的取自用户头像的毛玻璃特效--参考微信电话聊天背景（待更新）

**效果展示:**
![](http://upload-images.jianshu.io/upload_images/1833901-98c2ddfed06bd2c5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**源码链接:**
https://github.com/huangfangyi/fangyuanshili


#### 7 在哪：基于环信sdk的陌生人交友android版本
**介绍:**图忆是一款基于位置信息的分享与社交应用。实现了将用户记录的不同类型的事件标刻于地图之上，查看自己的记录足迹，同时用户可以轻松查看附近分享的记事，添加好友聊天，建立兴趣圈子，发现志趣相投的好友，并且用户记事可以分享到公共社区平台，分享乐趣的同时也发现了更多的乐趣，社区推荐策略让用户发现更多有价值的乐趣。
**功能模块:**
>**基于环信sdk的陌生人交友android版本开源了---在哪（微话聊）** 该项目是改编自[环信即时通讯云的demo](http://www.easemob.com/demo/)改编，新增了一些功能 环信即时通讯云demo包含了一个接近微信的完整的聊天app的所有功能, 包括发文字，表情，图片，语音，位置，群聊，登录，注册，退出登录等。

**效果展示:**

![](http://upload-images.jianshu.io/upload_images/1833901-93ba317a56d16e5c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**源码链接:**
https://github.com/vasth/zaina

#### 8 店话：基于react native 和 环信的实时通话
**介绍:**用“店话”搜索想要找的店铺电话，也可以上传自己的店铺信息和在线的客户免费语音通话，语音通话的流量仅仅需要3-5kb/s啊，还不快快下载！
**功能模块:**
>免费语音通话

**效果展示:**
![](http://upload-images.jianshu.io/upload_images/1833901-d46fda7d04d0ccf8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
**源码链接:**
https://github.com/vasth/dianhua




#### 9 “约个球”：作者本人的开源项目，目前正在开发中。后续将会使用环信SDK作为即时通讯支持，目前使用的是阿里百川的云旺。也会不断完善项目架构的搭建。全程博客更新，github项目维护。
**介绍:**
“约个球”APP是一款基于android系统开发的以球类运动为主题的社交app平台，注册“约个球”，你可以同自己的联系人进行沟通交流。你也可以在这里找到附近喜欢打球的人，填写自己的信息（如：选择自己喜欢的球类运动，打哪个位置，打了几年球之类的）。迅速发现附近各种球类运动场所。更重要的是，在“约个球”你随时都可以知道附近有哪些朋友正在战斗，你可以加入进去，也可以自行组建自己的战队。你也可以发起“约架”，邀请附近联系人队伍来一场精彩的篮球赛、足球赛……为球类运动爱好者提供一个在线交友的平台，为线下的球类运动助力。
**功能模块:**
>1 聊天模块
2 联系人模块
3 附近信息模块
4 资讯模块
5 个人信息模块

**效果展示:**
![](http://upload-images.jianshu.io/upload_images/1833901-8d9b346df48b8d7d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
**源码链接:**
https://github.com/CameloeAnthony/MVPCommon

# 四 其他文章或github
https://github.com/yigit/dev-summit-architecture-demo

#### ！！！！如果你有更好的即时通讯项目和社交app，欢迎提交到github。

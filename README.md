简历
--------

### 基本信息

+ 姓名：**张亦俊**
+ 性别：**男**
+ 出生年月：**1990年10月**
+ 手机：**18616836876**
+ 邮箱：**twoleft.zhang@outlook.com**

### 教育经历

+ 2016年6月 东南大学 计算机科学与技术 硕士
+ 2013年6月 东南大学 软件工程 学士


### 核心竞争力

+ 优秀的源码阅读能力，可以无障碍阅读各种代码，阅读过部分AOSP、OkHttp、fresco代码
+ 持续学习能力，始终关注业界动态
+ 可以熟练使用kotlin
+ 原理层面熟悉各类数据库
+ 有基本的native（C&C++）开发能力，熟悉native基本概念
+ 比较熟悉gradle、可以编写groovy/kotlin脚本
+ 有基础逆向能力
+ 有基础多媒体知识
+ 大前端技术栈
+ GEEK精神，喜好折腾


### 工作经历

#### 2021年10月 至 今 百度 Android研发工程师（百度App语音房）（T6）
因为业务调整，一局不再更新，我则在百度App语音房做一些基础架构工作，主要包括

1. 代码体积优化：因为直播的体积主要集中在代码上，我提出了一系列kotlin代码体积优化实践，目前已优化30K
2. redux架构科普：像团队成员介绍直播基础的redux架构

#### 2020年10月 至 2021年10月 百度 Android技术负责人（音啵、一局）（T6） 
因为业务调整，全民小视频交接给其他同学维护，我主要参与孵化了两个创新项目

##### 音啵
该项目是一个语音房App，项目孵化周期120人天（24天），后因为YY并购原因下线

##### 一局
该项目是一个游戏语音交友App，希望能够赶上 among us 风口，项目孵化周期80人天（16天）
我在该项目中主要负责项目协调、游戏外包对接、语音对接、自研游戏开发，其中比较重要的是

1. 快速入门cocos creator游戏开发
2. 基于百度插件框架改造cocos creator游戏引擎，将apk体积从80M降低到25M
3. 将游戏引擎改造成多进程渲染，缓解游戏崩溃问题，该工作输出专利一篇
4. 在游戏引擎引入离屏渲染，优化游戏启动性能，肉眼可见启动时间从3s降低到不超过1s，该工作输出专利一篇


#### 2020年5月 至 2020年10月 百度 Android技术负责人（全民小视频）（T5）
因为业务调整，团队整体转向创新业务孵化，我也成为了Android技术负责人

在此期间，我主要负责全民小视频的开发与项目协调工作，主要包括

1. 分配项目需求，追踪项目进度，跟进灰度
2. 面向快速孵化提出法务需求组件，主要涵盖隐私合规与青少年模式，这些组件可以节省孵化期约10人天工作量
3. 全面推广 kotlin 工作，同时担任部门技术委员会 kotlin方向主席
4. 推动“团队内中台客服计划”：因为中台对接沟通成本较高，我安排团队内专人负责对接特定中台，降低中台使用过程中的沟通成本


#### 2017年12月 至 2020年4月 百度 Android工程师（全民小视频）（T4、T5）

在此期间，主要负责全民小视频的各项开发工作，主要包括

1. 界面开发：日常的界面开发工作
2. 网页浏览器相关工作：支持FE开发，提供FE和客户端交互的基础解决方案
3. 外部SDK接入（插件、小程序、账号、网络等）：主要是对接公司各个SDK，给他们提出需求与反馈问题
4. 安装包体积优化与治理：通过引入插件和资源下载，把apk体积从28M一路减少到15M；同时引入一系列gradle task用来监管体积增长，避免有体积大量增长的操作
5. 组件化工作：给团队内各项迭代和新app孵化提供了一系列基础组件

除此之外，还推动了一系列基础架构变更，包括

1. 端内流量统一出口与管控：通过修改OkHttp的默认实现，将端内的流量尽可能集中起来，进行网络状态检测和QUIC等一系列后续优化
2. Glide向Fresco切换：因为项目需要webp动画，所以从最早的Glide切换Fresco，基本上是随各版本迭代随手进行，没有明显的人力投入
3. kotlin推广：推广kotlin使用，主要是为了减少NPE
4. AndroidX升级：因为我们主要的开源依赖新版本都已经不再支持support，所以需要整个客户端升级AndroidX，以支撑这些开源依赖升级

同时，我还是构建系统的主要维护人，团队使用的apk签名工具、插件打包工具、配置生成工具均出自我手。

#### 2016年7月 至 2017年12月 百度 前端工程师（全民小视频）（T3、T4）

在此期间，工作基本分两条线，视频抓取工作与常规前端工程师工作。抓取工作基本上是一套用脚本通过DevTools Protocol驱动Chrome的系统，由我自己搭建。系统上线一个月以后，puppeteer才开源，所以来不及用，不过puppeteer的代码倒是解决了不少困惑。普通前端工程师的工作基本上是各种内部系统项目，主要就用React，后来参与到一个React Native项目中，深感React Native设计上毛病太多，才转去做Android。

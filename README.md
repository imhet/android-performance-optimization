### 网站博客

以组织或人为单位的教程资源

- Android 官方教程，关于[性能优化的主题](http://developer.android.com/training/best-performance.html)，[中文翻译](http://hukai.me/android-training-course-in-chinese/best-performance.html) 
- [Android Developers](https://www.youtube.com/channel/UCVHFbqXqoYvEWM1Ddxl0QDg) Android 官方开发者频道
- 微信终端开发团队博客，公众号 WeMobileDev ，也可访问[腾讯云专栏](https://cloud.tencent.com/developer/column/1362)
- [Facebook Android 专栏](https://engineering.fb.com/category/android/)
- 《性能之巅》作者 [Brendan D.Gregg 的网站](http://www.brendangregg.com)
- [ClassShark](https://github.com/google/android-classyshark) 作者 Boris Farber 的[个人网站](https://borisfarber.com/)
- [Weishu's Notes](http://weishu.me) 维术博客文章很精彩，对虚拟机、插件化研究的很深入 
- [androidperformance 博客文章目录](https://www.androidperformance.com/2019/12/01/BlogMap/) 
- [markzhai's home](https://blog.zhaiyifan.cn/) BlockCanary 作者的博客
- [Trinea 的性能优化系列文章](https://www.trinea.cn/android/performance/)
- [Deep into Android](https://jsonchao.github.io/) 里面源码剖析和性能总结文章不错



### 书籍培训

相关书籍

- [《性能之巅：洞悉系统、企业与云计算》](https://book.douban.com/subject/26586598/) Linux 系统优化必看的书，Andoid 开发者可从中借鉴性能优化工具和思路
- [《Android移动性能实战》](https://book.douban.com/subject/27021800/) 腾讯SNG专项测试团队 2017 年出的性能优化案例集锦，基本都是手Q、手空和 QQ音乐的实际例子
- [《移动App性能评测与优化》](https://book.douban.com/subject/26891415/) 腾讯TMQ专项测试团队 2016 年出的实战案例精选，还讲了 [GT](https://github.com/Tencent/GT) 的使用
- [《高性能Android应用开发》](https://book.douban.com/subject/26891270/) AT&T 开发者计划中的性能推广领导者 Doug Sillars 2016 年出的书，涉及面广，值得一看
- [《Android应用性能优化》](https://book.douban.com/subject/19976838/) 联发科员工 2012 年写的书，其中的 jni 相关优化还是很有用的
- [《深入探索Android热修复技术原理》](https://book.douban.com/subject/30302319/) 阿里 Android 热修复方案 Sophix 背后的原理，对理解 Android 虚拟机很有帮助，大型 app 的性能优化难免涉及热修复
- [《Android插件化开发指南》](https://book.douban.com/subject/30306949/) 大型 app 的性能优化难免涉及插件化，老包的这本书可以帮助你了解 Android 插件化基础
- [《Web性能权威指南》](https://book.douban.com/subject/25856314/) 谷歌高性能团队核心成员写的书，网络方向的优化必看
- [《程序员的自我修养：链接、装载与库》](https://book.douban.com/subject/3652388/) 讲述代码编译之后是如何链接的，做 native 优化必看
- [《深入理解计算机系统》](https://book.douban.com/subject/26912767/) 性能优化是一个系统工程，了解计算机系统如何设计和工作很有必要

视频教程

- [Android 性能优化典范 1-6 季](https://www.youtube.com/playlist?list=PLWz5rJ2EKKc9CBxr3BVjPTPoDPLdPIFCE)，[中文翻译](https://androidperformance.com/2015/04/19/Android-Performance-Patterns/)
- 极客时间 [Android开发高手课](https://time.geekbang.org/column/intro/142) 前微信高级工程师 和 Tinker负责人讲解如何做性能优化，教程质量很高
- 极客时间 [深入浅出计算机组成原理](https://time.geekbang.org/column/intro/170)
- 极客时间 [性能工程高手课](https://time.geekbang.org/column/intro/259)


### 工具类库

#### APM 

- [Matrix](https://github.com/Tencent/matrix) 微信团队开源的应用性能接入框架
- [ArgusAPM](https://github.com/Qihoo360/ArgusAPM) 360 开源的移动性能监控项目
- [LeakCanary](https://github.com/square/leakcanary) square 开源的内存泄漏监控
- [BlockCanaryEx](https://github.com/seiginonakama/BlockCanaryEx) 基于 [BlockCanary](https://github.com/markzhai/AndroidPerformanceMonitor) ，记录主线程中执行的所有方法和它们的执行时间
- [DroidTelescope](https://github.com/zkwlx/DroidTelescope)
- [ANR-WatchDog](https://github.com/SalomonBrys/ANR-WatchDog) 检测 ANR 并抛出有意义的堆栈


#### 类库

- [Redex](https://fbredex.com/) Facebook 开源的 Android 字节码优化类库
- [Hardcoder](https://github.com/Tencent/Hardcoder) 微信开源的 Android APP 与系统间的通信解决方案，可以让 APP 充分调度系统资源来提升 APP 性能
- [Booster](https://github.com/didi/booster) 滴滴开源的质量优化框架
- [Alpha](https://github.com/alibaba/alpha) 阿里开源的基于PERT图构建的Android异步启动框架，启动优化时可参考
- [ADI](https://github.com/zkwlx/ADI) 通过 JVMTI 实现的 Android 应用开发调试的增强工具集
- [AndroidGodEye](https://github.com/Kyson/AndroidGodEye) 携程工程师开源类库，可以在PC浏览器中实时监控Android性能数据指标
- [DoraemonKit](https://github.com/didi/DoraemonKit) 滴滴开源的常用开发工具集应用，里面的性能检测可视化部分值得看看
- [AndroidDevMetrics](https://github.com/frogermcs/AndroidDevMetrics) Android 性能度量，可用于排查一些性能问题
- [MethodTraceMan](https://github.com/zhengcx/MethodTraceMan) 通过插桩统计方法耗时，解决Android App卡顿问题
- [Pury](https://github.com/NikitaKozlov/Pury) 基于注解的耗时方法监控 
- [nanoscope](https://github.com/uber/nanoscope) uber 开源的精确的方法统计工具
- [Battery-Metrics](https://github.com/facebookincubator/Battery-Metrics) Facebook 开源的电量监控
- [profilo](https://github.com/facebookincubator/profilo) Facebook 开源的性能检测工具，里面有个 plthook 的实现方案还不错


#### 工具

- TraceView
- SysTrace
    - [性能工具Systrace](http://gityuan.com/2016/01/17/systrace/) 
    - [Head First Systrace](https://hujiaweibujidao.github.io/blog/2016/10/03/head-first-systrace/)
- Android Profiler
- Hierarchyviewer
- MAT (Memory Analysis Tool)
- Simpleperf
    - [如何读懂火焰图？](https://www.ruanyifeng.com/blog/2017/09/flame-graph.html) 阮一峰把火焰图讲解得很清楚
    - [Flame Graphs](http://www.brendangregg.com/flamegraphs.html) 火焰图官方
- StrictMode
- Oprofile

### 主题文章


#### 性能优化文章集合贴

- [Android 性能优化必知必会](https://androidperformance.com/2018/05/07/Android-performance-optimization-skills-and-tools/) 收集了 Android 业界很多性能优化资料，值得慢慢消化
- [Awesome-Android-Performance](https://github.com/JsonChao/Awesome-Android-Performance) JsonChao 按性能各方向综述了市面上各种优化思路
- [awesome-android-performance](https://github.com/Juude/awesome-android-performance) Juude 整理的性能优化视频和文章
- [awesome-android-complete-reference](https://github.com/amitshekhariitbhu/awesome-android-complete-reference) Android 教程文章集合，里面有性能优化部分的文章可参考


#### 性能方法论

- [如何回答性能优化的问题，才能打动阿里面试官？](https://zhuanlan.zhihu.com/p/92910466) 
- [性能优化模式](https://tech.meituan.com/2015/12/10/performance-tuning-pattern.html) 性能优化的原则、反模式、模式...这个思路很不错，虽然是在java服务端，但迁移到 Android 端也适用
- [“性能问题终结者”Olympic，解决用户痛点背后的秘密是......](https://mp.weixin.qq.com/s/YJJdh3220y7TvBu3hAE3dQ) 手淘性能定位系统 Olympic
- [剖析应用性能](https://developer.android.com/studio/profile) Android 官方教程，介绍如何使用工具定位性能问题


#### 性能优化经验

- [加速你的 Android 应用](https://juejin.im/entry/563ae1b560b216575c53c3d6) 国外程序员优化经验，还有配套[视频](https://www.youtube.com/watch?v=v3DlGOQAIbw)，主要介绍 systrace 等工具使用
- [Android性能优化来龙去脉总结](https://wetest.qq.com/lab/view/390.html) 鹅厂程序员总结性能优化
- [移动端性能监控方案Hertz](https://tech.meituan.com/2016/12/19/hertz.html) 美团性能监控方案 Hertz 简介


#### 启动速度 & 页面打开速度

- [抖音BoostMultiDex优化实践：Android低版本上APP首次启动时间减少80%（一）](https://mp.weixin.qq.com/s/jINCbTJ5qMaD6NdeGBHEwQ) 从 Android Dalvik 机制入手，解决安装后首次执行 MultiDex 耗时过长问题
- [抖音BoostMultiDex优化实践：Android低版本上APP首次启动时间减少80%（二）](https://mp.weixin.qq.com/s/ILDTykAwR0xIkW-d1YzRHw)
- [支付宝 App 构建优化解析：通过安装包重排布优化 Android 端启动性能](https://mp.weixin.qq.com/s/79tAFx6zi3JRG-ewoapIVQ) 对支付宝 Android Apk 文件进行重新布局，来改善 IO 性能，从而提升启动速度
- [抖音研发实践：基于二进制文件重排的解决方案 APP启动速度提升超15%](https://mp.weixin.qq.com/s/Drmmx5JtjG3UtTFksL6Q8Q) 抖音iOS二进制文件的重新，Android 启动重排可参考
- [手淘全链路性能优化（上）](https://mp.weixin.qq.com/s/PiqnHezWKWUU0byEhrboRg) 手淘启动速度优化相关技术：启动框架，网络链路优化，自动化测试
- [手淘全链路性能优化下篇--容器极速之路](https://mp.weixin.qq.com/s/ATOSB8hc1woAObVP3Dtadw) 手淘容器化页面如 H5 及 Weex 相关的优化实践
- [Android App 启动优化全记录](https://zhuanlan.zhihu.com/p/92497570) 汇集多篇大厂文章的启动思路，可以参考
- [Facebook MobileLab:防止性能退化的高精测试](https://zhuanlan.zhihu.com/p/64495184) 优化防退化思路值得参考

#### 流畅度

- [内存泄露从入门到精通三部曲之常见原因与用户实践](https://cloud.tencent.com/developer/article/1070780 )
- [优化安卓应用内存的神秘方法以及背后的原理，一般人我不告诉他](https://cloud.tencent.com/developer/article/1070616) 主动收紧内存背后的原理


#### 内存

- [Android O的ART在性能方面的改进简介](https://zhuanlan.zhihu.com/p/27019789)
- [Android性能优化之内存优化](https://juejin.im/post/5e72b2d151882549236f9cb8)


### 包体积

- [抖音包大小优化-资源优化](https://mp.weixin.qq.com/s/xxrvRKXXDquJaezjrOlLwA)
- [zip 文件格式说明](https://blog.csdn.net/a200710716/article/details/51644421) apk 其实就是 zip 格式，了解 zip 文件格式很有必要

#### 耗电

- [Android应用耗电量的统计分析方法和工具](https://hujiaweibujidao.github.io/blog/2017/01/24/how-to-know-your-applications-battery-stats/) 


#### 存储

- [Android 中 SQLite 性能优化](https://droidyue.com/blog/2015/12/13/android-sqlite-tuning/)


#### 系统优化

- [那些年，我们一起经历过的 Android 系统性能优化](https://mp.weixin.qq.com/s/RqywGvblWi29irkXO2oM1g) 各大手机厂商的系统性能优化技术介绍
- [Android 中低内存对性能的影响](https://zhuanlan.zhihu.com/p/84687400) 低端机很重要的部分是要优化内存
- [当手机厂商说在 Android 底层做优化的时候，它们到底在做什么?](https://www.zhihu.com/question/31043755/answer/51955426)
- [Android性能优化之虚拟机调优](http://weishu.me/2016/12/23/dive-into-android-optimize-vm-heap/)
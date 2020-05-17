### 网站博客

以组织或人为单位的教程资源

- Android 官方教程
    - 关于[性能优化的培训](http://developer.android.com/training/best-performance.html)，[中文翻译](http://hukai.me/android-training-course-in-chinese/best-performance.html) 
    - [Android Developers](https://www.youtube.com/channel/UCVHFbqXqoYvEWM1Ddxl0QDg) Android 官方开发者频道
    - [Android 官方性能优化话题](https://developer.android.google.cn/topic/performance)
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
- [Anchors](https://github.com/YummyLau/Anchors) 支持同异步依赖任务初始化 Android 启动框架
- [ADI](https://github.com/zkwlx/ADI) 通过 JVMTI 实现的 Android 应用开发调试的增强工具集
- [AndroidGodEye](https://github.com/Kyson/AndroidGodEye) 携程工程师开源类库，可以在PC浏览器中实时监控Android性能数据指标
- [DoraemonKit](https://github.com/didi/DoraemonKit) 滴滴开源的常用开发工具集应用，里面的性能检测部分值得借鉴
- [AndroidDevMetrics](https://github.com/frogermcs/AndroidDevMetrics) Android 性能度量，可用于排查一些性能问题
- [MethodTraceMan](https://github.com/zhengcx/MethodTraceMan) 通过插桩统计方法耗时，解决Android App卡顿问题
- [Pury](https://github.com/NikitaKozlov/Pury) 基于注解的耗时方法监控 
- [nanoscope](https://github.com/uber/nanoscope) uber 开源的精确的方法统计工具
- [Battery-Metrics](https://github.com/facebookincubator/Battery-Metrics) Facebook 开源的电量监控
- [profilo](https://github.com/facebookincubator/profilo) Facebook 开源的性能检测工具，里面有个 plthook 的实现方案还不错
- [PreLoader](https://github.com/luckybilly/PreLoader) 预加载数据框架
- [ThreadDebugger](https://github.com/Jacksgong/ThreadDebugger) 线程监控


#### 工具

- TraceView
- SysTrace
    - [性能工具Systrace](http://gityuan.com/2016/01/17/systrace/) 
    - [Head First Systrace](https://hujiaweibujidao.github.io/blog/2016/10/03/head-first-systrace/)
    - [了解 Systrace](https://source.android.com/devices/tech/debug/systrace)
- Android Profiler
- Hierarchyviewer
- MAT (Memory Analysis Tool)
- Simpleperf
    - [如何读懂火焰图？](https://www.ruanyifeng.com/blog/2017/09/flame-graph.html) 阮一峰把火焰图讲解得很清楚
    - [Flame Graphs](http://www.brendangregg.com/flamegraphs.html) 火焰图官方
- StrictMode
- Oprofile

### 主题文章


性能优化文章集合贴

- [Android 性能优化必知必会](https://androidperformance.com/2018/05/07/Android-performance-optimization-skills-and-tools/) 收集了 Android 业界很多性能优化资料，值得慢慢消化
- [Awesome-Android-Performance](https://github.com/JsonChao/Awesome-Android-Performance) JsonChao 按性能各方向综述了市面上各种优化思路
- [awesome-android-performance](https://github.com/Juude/awesome-android-performance) Juude 整理的性能优化视频和文章
- [awesome-android-complete-reference](https://github.com/amitshekhariitbhu/awesome-android-complete-reference) Android 教程文章集合，里面有性能优化部分的文章可参考


性能方法论

- [如何回答性能优化的问题，才能打动阿里面试官？](https://zhuanlan.zhihu.com/p/92910466) 
- [Data science for mobile OS system optimization](http://www.caveman.work/2019/06/01/Data-science-for-mobile-OS-system-optimization/)
- [性能优化模式](https://tech.meituan.com/2015/12/10/performance-tuning-pattern.html) 性能优化的原则、反模式、模式...这个思路很不错，虽然是在java服务端，但迁移到 Android 端也适用
- [“性能问题终结者”Olympic，解决用户痛点背后的秘密是......](https://mp.weixin.qq.com/s/YJJdh3220y7TvBu3hAE3dQ) 手淘性能定位系统 Olympic
- [剖析应用性能](https://developer.android.com/studio/profile) Android 官方教程，介绍如何使用工具定位性能问题


性能优化经验

- [加速你的 Android 应用](https://juejin.im/entry/563ae1b560b216575c53c3d6) 国外程序员优化经验，还有配套[视频](https://www.youtube.com/watch?v=v3DlGOQAIbw)，主要介绍 systrace 等工具使用
- [Android性能优化来龙去脉总结](https://wetest.qq.com/lab/view/390.html) 鹅厂程序员总结性能优化
- [移动端性能监控方案Hertz](https://tech.meituan.com/2016/12/19/hertz.html) 美团性能监控方案 Hertz 简介


启动速度 & 页面打开速度

- [抖音BoostMultiDex优化实践：Android低版本上APP首次启动时间减少80%（一）](https://mp.weixin.qq.com/s/jINCbTJ5qMaD6NdeGBHEwQ) 从 Android Dalvik 机制入手，解决安装后首次执行 MultiDex 耗时过长问题
- [抖音BoostMultiDex优化实践：Android低版本上APP首次启动时间减少80%（二）](https://mp.weixin.qq.com/s/ILDTykAwR0xIkW-d1YzRHw)
- [支付宝 App 构建优化解析：通过安装包重排布优化 Android 端启动性能](https://mp.weixin.qq.com/s/79tAFx6zi3JRG-ewoapIVQ) 对支付宝 Android Apk 文件进行重新布局，来改善 IO 性能，从而提升启动速度
- [Redex 初探与 Interdex：Andorid 冷启动优化](https://mp.weixin.qq.com/s/Bf41Kez_OLZTyty4EondHA?) 插桩与调整类分布互斥
- [抖音研发实践：基于二进制文件重排的解决方案 APP启动速度提升超15%](https://mp.weixin.qq.com/s/Drmmx5JtjG3UtTFksL6Q8Q) 抖音iOS二进制文件的重新，Android 启动重排可参考
- [滴滴DoKit Android核心原理揭秘之函数耗时](https://juejin.im/post/5eba5ce15188256d6f268c98) 滴滴开源类库 DoraemonKit 中函数耗时插桩原理：gradle 插件 + ASM + Transform
- [DoKit支持Activity启动耗时统计方案](https://juejin.im/post/5d70bc3051882571ed61e407)  滴滴开源类库 DoraemonKit 统计页面打开耗时的原理
- [手淘全链路性能优化（上）](https://mp.weixin.qq.com/s/PiqnHezWKWUU0byEhrboRg) 手淘启动速度优化相关技术：启动框架，网络链路优化，自动化测试
- [手淘全链路性能优化下篇--容器极速之路](https://mp.weixin.qq.com/s/ATOSB8hc1woAObVP3Dtadw) 手淘容器化页面如 H5 及 Weex 相关的优化实践
- [Android App 启动优化全记录](https://zhuanlan.zhihu.com/p/92497570) 汇集多篇大厂文章的启动思路
- [Facebook MobileLab:防止性能退化的高精测试](https://zhuanlan.zhihu.com/p/64495184) 性能防退化思路值得参考
- [支付宝客户端架构解析：Android 客户端启动速度优化之「垃圾回收」](https://juejin.im/post/5be1077d518825171140dbfa) 启动时 GC 抑制，允许堆一直增长，直到开发人员主动停止
- [Android性能优化之虚拟机调优](http://weishu.me/2016/12/23/dive-into-android-optimize-vm-heap/) 启动过程中 GC 抑制的原理，可与上面支付宝的那篇对照着看
- [Android App 启动优化全记录](https://www.androidperformance.com/2019/11/18/Android-App-Lunch-Optimize/) 汇总了市面上大部分启动优化思路
- [今日头条启动很快，你觉得可能是做了哪些优化？](https://www.jianshu.com/p/d0fe74f4e9c4)

流畅 & 卡顿优化

- [Matrix TraceCanary -- 初恋·卡顿](https://cloud.tencent.com/developer/article/1382771) 微信 Matrix 卡顿监控原理
- [手Q Android线程死锁监控与自动化分析实践](https://cloud.tencent.com/developer/article/1064396) 通过上报系统产生的 Traces.txt 和自动化分析实现线程死锁监控
- [Android UI 性能优化](https://zhuanlan.zhihu.com/p/27065828) [Google IO 2017上的视频](https://www.youtube.com/watch?v=9HtTL_RO2wI)的翻译，值得一看
- [微信读书（Android）阅读引擎卡顿监控测试](https://www.infoq.cn/article/weixin-reading-stuck-monitor-and-test)
- [见微知著，Google Photos Web UI 完善之旅](https://zhuanlan.zhihu.com/p/50280008)
- [Android 无障碍服务导致的整机卡顿案例分析](https://www.androidperformance.com/2019/01/21/android-performance-case-jank-accessbility/)
- [识别与抖动相关的卡顿](https://source.android.com/devices/tech/debug/jank_jitter)
- [那些年我们用过的显示性能指标](https://blog.csdn.net/tencent_bugly/article/details/51354517)
- [Android 中的卡顿丢帧原因概述-方法论](https://www.androidperformance.com/2019/09/05/Android-Jank-Debug/) 同系列文章还有[应用篇](https://www.androidperformance.com/2019/09/05/Android-Jank-Due-To-App/)和[系统篇](https://www.androidperformance.com/2019/09/05/Android-Jank-Due-To-System/) ，内有很多案例可参考
- [一线大厂资深APP性能优化系列-卡顿定位](https://juejin.im/post/5eb44efd6fb9a043890a2b4c) 介绍了traceView的四个视图：Call Chart，Flame Chart，Top Down，Bottom Up


内存

- [微信 Android 终端内存优化实践](https://mp.weixin.qq.com/s/KtGfi5th-4YHOZsEmTOsjg) 介绍微信内存优化思路，其中包含微信 Matrix 的 ResourceCanary 等多种内存检测手段
- [手Q Android缓存监控与优化实践](https://cloud.tencent.com/developer/article/1110473) 监控图片缓存和业务对象缓存，清理ClassLoader引用的内存和系统预加载图片缓存
- [内存泄露从入门到精通三部曲之常见原因与用户实践](https://cloud.tencent.com/developer/article/1070780) 
- [优化安卓应用内存的神秘方法以及背后的原理，一般人我不告诉他](https://cloud.tencent.com/developer/article/1070616) 主动收紧内存背后的原理
- [Android O的ART在性能方面的改进简介](https://zhuanlan.zhihu.com/p/27019789) 17 年 [IO 视频](https://www.youtube.com/watch?v=iFE2Utbv1Oo)的翻译，介绍了 Android 7.0 热点代码（对启动优化很有帮助）和 GC 方面的改进
- [Android性能优化之内存优化](https://juejin.im/post/5e72b2d151882549236f9cb8) 网友整理的内存优化知识点算是很全了
- [分析并优化 Android 应用内存占用](https://juejin.im/post/5c2841cde51d45673971d03f) Google Android Runtime 开发工程师 Rechard Uhler 的[内存优化经验视频](https://www.youtube.com/watch?v=w7K0jio8afM&list=PLpvKQarSfUV0l-fMxTrJIDF3IvwoXlGOA)的翻译
- [Android 内存泄漏分析心得](https://cloud.tencent.com/developer/article/1006293) 手空内存泄漏监控与分析案例
- [Probe：Android线上OOM问题定位组件](https://mp.weixin.qq.com/s/tO1yxFs2qNQlQ2bJ8vGzQA) 美团 OOM 监控框架介绍，可定位线上Java堆内存不足、FD泄漏以及线程溢出的等OOM问题
- [Bitmap优化详谈](https://juejin.im/post/5bfbd5406fb9a049be5d2a20)
- [看完这篇文章,至少解决 APP 中 90 % 的内存异常问题](https://juejin.im/post/5cd82a3ee51d456e781f20ce#heading-32)


包体积

- [抖音包大小优化-资源优化](https://mp.weixin.qq.com/s/xxrvRKXXDquJaezjrOlLwA)
- [zip 文件格式说明](https://blog.csdn.net/a200710716/article/details/51644421) apk 其实就是 zip 格式，了解 zip 文件格式很有必要

耗电

- [Android battery and memory optimizations](https://youtube.com/watch?v=VC2Hlb22mZM) Google I/O 2016 关于电池和内存优化的视频
- [Android应用耗电量的统计分析方法和工具](https://hujiaweibujidao.github.io/blog/2017/01/24/how-to-know-your-applications-battery-stats/) 
- [Android功耗改进](https://paul.pub/android-power/) Android 5.0 ~ 8.0 对功耗方面的改进


存储 & IO

- [Matrix IOCanary -- I/O 质量监控](https://cloud.tencent.com/developer/article/1381540) 微信 Matrix IO 监控原理
- [Android 中 SQLite 性能优化](https://droidyue.com/blog/2015/12/13/android-sqlite-tuning/)


系统优化

- [那些年，我们一起经历过的 Android 系统性能优化](https://mp.weixin.qq.com/s/RqywGvblWi29irkXO2oM1g) 各大手机厂商的系统性能优化技术介绍
- [Android 中低内存对性能的影响](https://zhuanlan.zhihu.com/p/84687400) 低端机很重要的部分是要优化内存
- [当手机厂商说在 Android 底层做优化的时候，它们到底在做什么?](https://www.zhihu.com/question/31043755/answer/51955426)
- [Android性能优化之虚拟机调优](http://weishu.me/2016/12/23/dive-into-android-optimize-vm-heap/)
- [揭秘在安卓平台上奇慢无比的 ClassLoader.getResourceAsStream](https://blog.nimbledroid.com/2016/04/06/slow-ClassLoader.getResourceAsStream-zh.html)
- [Android 设备优化启动时间](https://source.android.com/devices/tech/perf/boot-times)
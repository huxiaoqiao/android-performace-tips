# android-performace-tips

###android 性能优化相关文章整理

-------------------------------

###1.性能优化资料

[Android 官方资料 Android 性能优化典范- 第1季][0]

[Android 官方资料 Android性能优化典范 - 第2季][1]

[Android 官方资料 Android性能优化典范 - 第3季](http://hukai.me/android-performance-patterns-season-3/)

[Android 官方资料 Android性能优化典范 - 第4季](http://hukai.me/android-performance-patterns-season-4/)

[Android 官方资料 Android性能优化典范 - 第5季](http://hukai.me/android-performance-patterns-season-5/)

[Android 官方资料 Android性能优化典范 - 第6季](http://hukai.me/android-performance-patterns-season-6/)

[Android app 性能设计技巧][2]

[Facebook的Android调试工具Stetho介绍][3]

[Android Lint(官方代码优化利器)][4]

[Android Training Best Practices for Performance](https://developer.android.com/training/articles/perf-tips.html)

[Android Studio Monitor 使用指南](https://developer.android.com/studio/profile/android-monitor.html)

[Google官方 详解 Android 性能优化【史诗巨著之内存篇】](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247484153&idx=1&sn=eecb8a4587354b39c03fa6e1eadae0a4&chksm=eae1f7abdd967ebd36e65a03117cd6e986bc3bd642ce9506b124904ec9c5871c466437293783&mpshare=1&scene=1&srcid=1103qjWHQbN0bJ4gslH9S596#rd)

##### 其中有关于如何使用 Monitor 分析内存，CPU，GPU的教程。

[DDMS使用教程](https://developer.android.com/studio/profile/ddms.html)
[TraceView 使用教程](http://bxbxbai.github.io/2014/10/25/use-trace-view/)

[MAT使用](http://blog.csdn.net/huxiaoqiao163/article/details/72731017)


###2.View优化

[Android中View绘制优化之一---- 优化布局层次][5]

[Android中View绘制优化二一---- 使用<include />标签复用布局文件][6]

[Android中View绘制优化之三---- 优化View][7]

[Android 性能优化之ViewSub](http://www.cnblogs.com/lwbqqyumidi/p/4047108.html)

[Android UI性能优化实战 识别绘制中的性能问题](http://blog.csdn.net/lmj623565791/article/details/45556391)


### 3.GC 与内存泄漏
[GC root分析内存泄漏](http://www.jianshu.com/p/f5582d9a0f73)

[理解Java垃圾回收机制](http://jayfeng.com/2016/03/11/%E7%90%86%E8%A7%A3Java%E5%9E%83%E5%9C%BE%E5%9B%9E%E6%94%B6%E6%9C%BA%E5%88%B6/)

[Java中引用和垃圾回收](http://buptguo.com/2016/03/30/gc-and-reference-in-java/)

[深入Android内存泄露](http://blog.csdn.net/ccj659/article/details/53032683)

[内存泄露实例分析](http://www.jianshu.com/p/cbe2ee08ca02)

[常见的八种导致 APP 内存泄漏的问题](http://www.apkbus.com/blog-705730-60636.html)


### 4.卡顿优化
[一触即发——App启动优化最佳实践](http://blog.csdn.net/eclipsexys/article/details/53044990)


### 5.性能优化综合

[张明云-应用开发进阶必经之路之性能优化](https://github.com/OpenDevTeam/OpenBox/blob/master/topic/%5BAndroid技术专题%5D应用开发进阶必经之路之性能优化.md)

[Android应用开发性能优化完全分析](http://blog.csdn.net/yanbober/article/details/48394201)

[Android应用性能优化个人总结--图形优化](https://mp.weixin.qq.com/s?__biz=MzAxMzYyNDkyNA==&mid=403778409&idx=1&sn=2955f5209f2cb46c327167e9f558013c&scene=0&key=710a5d99946419d93bd87693b2fb201a979a3f06f49072f49e0e5dd05b91de2dbe204e56cbcd8c71cac94e931791f5f3&ascene=0&uin=ODU2NjQ0ODgx&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.4+build(15E65)&version=11020201&pass_ticket=NpyEx%2Bv110qEyBfX%2FXCGo55tZw3peFfAhXrILZbS0gX3U7PSt2FR04BNIg%2BNPeQA)
[Android App 内存优化系列](http://www.jianshu.com/p/48475df838d9)

[Android 内存优化](http://blog.csdn.net/a396901990/article/details/38904543)

[Android 性能优化之内存篇](http://hukai.me/android-performance-memory/)
[Android Training 管理应用的内存](http://hukai.me/android-training-managing_your_app_memory/)

[Glow Android 优化实践](http://www.diycode.cc/topics/394)

[途牛APK压缩最佳实践](http://mp.weixin.qq.com/s?__biz=MzAwOTE0ODEwMQ==&mid=2650686686&idx=1&sn=192f968e71621fa9fdf20f22c014e893&chksm=836ee774b4196e624e57308b1807fd5328271c80af7393b34f96e392ed4dcf30bc62b389d6b0&mpshare=1&scene=1&srcid=11047fPZims2Q9KIEfojkjCU#rd)




[0]:http://hukai.me/android-performance-patterns/
[1]:http://hukai.me/android-performance-patterns-season-2/

[2]:http://www.onsandroid.com/2014/10/android-application-designing-for.html
[3]:http://www.androidcn.org/topic/552fabaa8ca8a1e07687e999
[4]:http://blog.csdn.net/sunchaoenter/article/details/7319933
[5]:http://blog.csdn.net/qinjuning/article/details/7944148
[6]:http://blog.csdn.net/qinjuning/article/details/7957858
[7]:http://blog.csdn.net/qinjuning/article/details/7972991

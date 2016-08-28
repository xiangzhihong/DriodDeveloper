# DriodDeveloper 微信公众号文章
主要用于记录微信公众号所推送的所有文章，公众号：DriodDeveloper


## 已推送文章列表

###<font color ="#FF6347">插件总结</font>

#####[\[\[已推送\]插件开发之360 DroidPlugin源码分析（五）Service预注册占坑\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483792&idx=1&sn=9abb3b16f46b65608bf71c52a9fce9c0#rd)
- AndroidMainfest.xml中概览
- Service中关键方法被hook时机
- startService被hook
- 瞒天过海流程图
- 认识ServiceManager

---

#####[\[\[已推送\]插件开发之360 DroidPlugin源码分析（四）Activity预注册占坑\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483787&idx=1&sn=f0110e88e5c817bfb2ee12f25896eb76#rd)
- AndroidMainfest.xml中概览
- Activity中关键方法被hook时机
- startActivity被hook
- handelPerformActivity被hook
- Activity预注册占坑整体流程图
- 瞒天过海，冒充真实身份，欺骗AMS

---

#####[\[\[已推送\]插件占坑，四大组件动态注册前奏（三） 系统BroadCast的注册发送流程\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483766&idx=1&sn=9bceb7c35295a72389cf66c6a3e7bb5b#rd)

---


#####[\[\[已推送\]插件占坑，四大组件动态注册前奏（二） 系统Service的启动流程\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483763&idx=1&sn=9e922c1d34373d2f93203f2e0863c491#rd)

---

#####[\[\[已推送\]插件占坑，四大组件动态注册前奏（一） 系统Activity的启动流程\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483757&idx=1&sn=3b82c91b68a6073e03a8cbee53cf635a#rd)

---

#####[\[\[已推送\]插件开发之360 DroidPlugin源码分析（三）Binder代理\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483718&idx=1&sn=c8785c9196a2be9b0e5890a5b43883c0#rd)
- Hook机制中Binder代理类关系图
- Hook机制中Binder代理时序图
- MyServiceManager
- ServiceManagerCacheBinderHook
- ServiceManagerBinderHook
- BinderHook

---

#####[\[\[已推送\]插件开发之360 DroidPlugin源码分析（二）Hook机制\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483714&idx=1&sn=55cee6a7f5871d3c4d14c0c87409d688#rd)
- Hook机制的包结构关系
- Hook机制的类图关系
- Hook机制的时序图关系
- Manifest权制申请
- 基类Hook做了什么？
- HookedMethodHandler
- 基类BaseHookHandle和Hook有什么关系？
- ProxyHook能干什么？
- 实例-如何hook IPackageManager

---

#####[\[\[已推送\]插件开发之360 DroidPlugin源码分析（一）初识\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483714&idx=2&sn=1f293aa4330c02249add70f7f90c82dd#rd)
- DroidPlugin是什么？
- DroidPlugin的优缺点？
- DroidPlugin的的基本原理是什么？

---

###<font color ="#FF6347">View框架总结</font>


#####[\[\[已推送\]Android View框架总结（九）KeyEvent事件分发机制\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483816&idx=1&sn=e2a35e174bb73026a2ee642a84e46075#rd)

- ViewRootImpl中的dispatchInputEvent方法
- View.dispatchKeyEvent方法
- ViewGroup.dispatchKeyEvent方法
- Activity.dispatchKeyEvent方法
- 按键消息事件时序图

---

#####[\[\[已推送\]Android View框架总结（八）ViewGroup事件分发机制\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483797&idx=1&sn=c18c95be026359a2c194f1c91d95b301#rd)

- dispatchTouchEvent
- onInterceptTouchEvent
- onTouchEvent
- ViewGroup 事件的分发机制流程图
- 案例
- 案例流程图

---


#####[\[\[已推送\]Android View框架总结（七）View事件分发机制\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483797&idx=1&sn=c18c95be026359a2c194f1c91d95b301#rd)
- View 事件的分发机制
- dispatchTouchEvent
- onInterceptTouchEvent
- onTouchEvent
- 案例

---


#####[\[\[已推送\]Android View框架总结（六）View布局流程之Draw过程\]](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483780&idx=1&sn=38ef3ac55e550a711a1e76a62001310a#rd)
- View的Layout时序图
- ViewRootImpl.performTraversals过程
- ViewRootImpl.performDraw过程
- View.draw方法
- View.dispatchDraw过程
- LinearLayout的onDraw过程

---


#####[[已推送]Android View框架总结（五）View布局流程之Layout](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483770&idx=1&sn=fb8e51d61e457fd80598216035e6a484#rd)

- View树的Layout流程
- View的Layout时序图
- View布局流程之Layout 
- ViewGroup的Layout过程
- setFrame方法
- View的Layout过程
- FrameLayout的Layout过程

---


#####[[已推送]Android View框架总结（四）View布局流程之Measure](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483760&idx=1&sn=a4ad257255548ddba7451a773044df8c#rd)

- View树的measure流程
- View的measures时序图
- View布局流程之measure 
- View的measure过程
- ViewGroup的measure过程
- FrameLayout的measure过程
- measure过程 

---


#####[[已推送]Android View框架总结（三）View工作原理](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483751&idx=1&sn=b620ccfbe68b5093808f3dafbb507ba1#rd)

- 测量/布局/绘制顺序
- 如何引起View的测量/布局/绘制？
- PerformTraversales()
- ViewRoot
- View工作基本流程 
 - SpecMode
 - MeasureSpec和LayoutParams
 - RootMeasureSpec
 - MeasureSpec 

---


#####[[已推送]Android View框架总结（二）View焦点](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483746&idx=1&sn=ebfa9f14ff710e432e0c68c3da6d5fd3#rd)

- ViewRoot
- View的焦点
- ViewGroup的焦点
- 父容器焦点的处理
- 失去焦点或清除焦点
- 焦点移动
- FocusFinder查找焦点
- 总结

---

#####[[已推送]Android View框架总结（一）](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483702&idx=1&sn=1ae20f8dbd38cbfa02ab3a7512da6a46#rd)

---


#####[[已推送]插件前奏-android黑科技 hook介绍](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483693&idx=1&sn=062f24d78cc53c388ad601b468fbdc43#rd)

<hr/>

#####[[已推送]android studio快捷键与Eclipse快捷键对比-没有之一](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483693&idx=2&sn=7720bf34454b0a6af7c5b9142e3d343b#rd)

---


#####[[已推送]早期微信抢红包插件项目分享(红包精灵源码)](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483710&idx=1&sn=83c326510ad99543c7aea693ce9f174e#rd)

---


#####[[已推送]如何优化你的布局层级结构之RelativeLayout和LinearLayout及FrameLayout性能分析（一）](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483674&idx=1&sn=1b40efb15049f4f5555a8d8be235cfe5#rd)

---


#####[[已推送]如何优化你的布局层级结构之RelativeLayout和LinearLayout及FrameLayout性能分析（二）](http://mp.weixin.qq.com/s?__biz=MzI2OTQxMTM4OQ==&mid=2247483674&idx=2&sn=91cff622beac9bce53509e965da641d1#rd)

---


## 公众号二维码
个人原创 android 技术干货，问题深度总结，FrameWork源码解析，插件化研究，最新开源项目推荐

<img  src="http://img.my.csdn.net/uploads/201607/31/1469961798_9398.jpg" width="200px"/>

``` xml
MIT License

Copyright (c) 2016 hejunlin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

Android开源项目分类汇总
====================

####<a href="http://codekk.com/open-source-project-analysis" target="_blank">Android 开源项目源码解析(Volley、UIL、Dagger、EventBus、xUtils 等分析)</a>  
####<a href="http://codekk.com/jobs" target="_blank">Android 职位内部推荐(阿里、百度、美团、点评、魅族等)</a>  

`codeKK`专注于开源项目源码解析、开源项目分享、Android 职位推荐。  
> 我们的网站：[www.codekk.com](http://codekk.com)  
 我们的微博：[code-kk](http://weibo.com/codek2)  
 微信公众号：codekk，二维码如下：  
 ![img](https://raw.githubusercontent.com/aosp-exchange-group/about/master/weixin-qrcode.jpg) 

欢迎大家推荐好的Android开源项目，可直接[Commit](https://github.com/Trinea/android-open-project/wiki "请遵守<内容添加及编辑规范>")，欢迎`Star`、`Fork` :)  
> **关于我，欢迎关注**  
 微博：<a title="Android 技术及移动互联网分享" href="http://weibo.com/trinea?s=6cm7D0" target="_blank">Trinea</a>&nbsp;&nbsp;&nbsp;&nbsp;主页：<a title="关注于 Android、Java、性能优化、开源项目" href="http://www.trinea.cn/" target="_blank">trinea.cn</a>&nbsp;&nbsp;&nbsp;&nbsp;邮箱：<a title="欢迎邮件与我交流" href="mailto:trinea.cn@gmail.com" target="_blank">trinea.cn#gmail.com</a>&nbsp;&nbsp;&nbsp;&nbsp;微信：[codek2](# "二维码就是上面那个")  


更多：[Android 开源库获取途径整理](http://www.trinea.cn/android/android-open-project-summary/)  
分享：<a href="http://service.weibo.com/share/share.php?url=https%3A%2F%2Fgithub.com%2FTrinea%2Fandroid-open-project&title=Android%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%E5%88%86%E7%B1%BB%E6%B1%87%E6%80%BB%EF%BC%8C%E6%B1%87%E9%9B%86250%E5%A4%9A%E4%B8%AA%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%EF%BC%8C%E5%8C%85%E6%8cB%AC%E4%B8%AA%E6%80%A7%E5%8C%96%E6%8E%A7%E4%BB%B6%E3%80%81%E5%B7%A5%E5%85%B7%E5%BA%93%E3%80%81%E4%BC%98%E7%A7%80%E9%A1%B9%E7%9B%AE%E3%80%81%E5%BC%80%E5%8F%91%E5%8F%8A%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7%E3%80%81%E4%BC%98%E7%A7%80%E4%B8%AA%E4%BA%BA%E5%92%8C%E5%9B%A2%E4%BD%93%40Trinea+&appkey=1657413438&searchPic=true" target="_blank" title="分享到新浪微博" style="width:100%"><img src="http://farm8.staticflickr.com/7342/13103239365_e5cd37fbac_o.png" title="分享到新浪微博"/></a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="http://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey?url=https%3A%2F%2Fgithub.com%2FTrinea%2Fandroid-open-project&title=Android%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%E5%88%86%E7%B1%BB%E6%B1%87%E6%80%BB%EF%BC%8C%E6%B1%87%E9%9B%86250%E5%A4%9A%E4%B8%AA%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%EF%BC%8C%E5%8C%85%E6%8B%AC%E4%B8%AA%E6%80%A7%E5%8C%96%E6%8E%A7%E4%BB%B6%E3%80%81%E5%B7%A5%E5%85%B7%E5%BA%93%E3%80%81%E4%BC%98%E7%A7%80%E9%A1%B9%E7%9B%AE%E3%80%81%E5%BC%80%E5%8F%91%E5%8F%8A%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7%E3%80%81%E4%BC%98%E7%A7%80%E4%B8%AA%E4%BA%BA%E5%92%8C%E5%9B%A2%E4%BD%93%40Trinea+&desc=&summary=&site=www.trinea.cn" target="_blank" title="分享到QQ空间" style="width:100%"><img src="http://farm8.staticflickr.com/7418/13103935825_209bd521f0_o.jpg"/></a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="http://share.v.t.qq.com/index.php?c=share&a=index&url=https%3A%2F%2Fgithub.com%2FTrinea%2Fandroid-open-project&title=Android%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%E5%88%86%E7%B1%BB%E6%B1%87%E6%80%BB%EF%BC%8C%E6%B1%87%E9%9B%86250%E5%A4%9A%E4%B8%AA%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%EF%BC%8C%E5%8C%85%E6%8B%AC%E4%B8%AA%E6%80%A7%E5%8C%96%E6%8E%A7%E4%BB%B6%E3%80%81%E5%B7%A5%E5%85%B7%E5%BA%93%E3%80%81%E4%BC%98%E7%A7%80%E9%A1%B9%E7%9B%AE%E3%80%81%E5%BC%80%E5%8F%91%E5%8F%8A%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7%E3%80%81%E4%BC%98%E7%A7%80%E4%B8%AA%E4%BA%BA%E5%92%8C%E5%9B%A2%E4%BD%93%40Trinea+&appkey=801404464" target="_blank" title="分享到腾讯微博" style="width:100%"><img src="http://farm8.staticflickr.com/7452/13104204564_f867971a13_o.png"/></a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://twitter.com/intent/tweet?text=Android%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%E5%88%86%E7%B1%BB%E6%B1%87%E6%80%BB%EF%BC%8C%E6%B1%87%E9%9B%86250%E5%A4%9A%E4%B8%AA%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%EF%BC%8C%E5%8C%85%E6%8B%AC%E4%B8%AA%E6%80%A7%E5%8C%96%E6%8E%A7%E4%BB%B6%E3%80%81%E5%B7%A5%E5%85%B7%E5%BA%93%E3%80%81%E4%BC%98%E7%A7%80%E9%A1%B9%E7%9B%AE%E3%80%81%E5%BC%80%E5%8F%91%E5%8F%8A%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7%E3%80%81%E4%BC%98%E7%A7%80%E4%B8%AA%E4%BA%BA%E5%92%8C%E5%9B%A2%E4%BD%93%40trinea_cn+https%3A%2F%2Fgithub.com%2FTrinea%2Fandroid-open-project&pic=" target="_blank" title="Share on twitter" style="width:100%"><img src="http://farm4.staticflickr.com/3764/13104038813_03933d4394_o.png"/></a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fgithub.com%2FTrinea%2Fandroid-open-project&t=Android%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%E5%88%86%E7%B1%BB%E6%B1%87%E6%80%BB%EF%BC%8C%E6%B1%87%E9%9B%86250%E5%A4%9A%E4%B8%AA%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%EF%BC%8C%E5%8C%85%E6%8B%AC%E4%B8%AA%E6%80%A7%E5%8C%96%E6%8E%A7%E4%BB%B6%E3%80%81%E5%B7%A5%E5%85%B7%E5%BA%93%E3%80%81%E4%BC%98%E7%A7%80%E9%A1%B9%E7%9B%AE%E3%80%81%E5%BC%80%E5%8F%91%E5%8F%8A%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7%E3%80%81%E4%BC%98%E7%A7%80%E4%B8%AA%E4%BA%BA%E5%92%8C%E5%9B%A2%E4%BD%93%40Trinea+&pic" target="_blank" title="Share on facebook" style="width:100%"><img src="http://farm4.staticflickr.com/3801/13104038583_b03d5cafac_o.png"/></a>  
  
## 目前包括：  
>[Android开源项目第一篇——个性化控件(View)篇](https://github.com/Trinea/android-open-project#%E7%AC%AC%E4%B8%80%E9%83%A8%E5%88%86-%E4%B8%AA%E6%80%A7%E5%8C%96%E6%8E%A7%E4%BB%B6view)  
*&nbsp;&nbsp;包括[ListView](https://github.com/Trinea/android-open-project#%E4%B8%80listview)、[ActionBar](https://github.com/Trinea/android-open-project#%E4%BA%8Cactionbar)、[Menu](https://github.com/Trinea/android-open-project#%E4%B8%89menu)、[ViewPager](https://github.com/Trinea/android-open-project#%E5%9B%9Bviewpager-gallery)、[Gallery](https://github.com/Trinea/android-open-project#%E5%9B%9Bviewpager-gallery)、[GridView](https://github.com/Trinea/android-open-project#%E4%BA%94gridview)、[ImageView](https://github.com/Trinea/android-open-project#%E5%85%ADimageview)、[ProgressBar](https://github.com/Trinea/android-open-project#%E4%B8%83progressbar)、[TextView](https://github.com/Trinea/android-open-project#%E5%85%ABtextview)、[ScrollView](https://github.com/Trinea/android-open-project#%E4%B9%9Dscrollview)、[TimeView](https://github.com/Trinea/android-open-project#%E5%8D%81timeview)、[TipView](https://github.com/Trinea/android-open-project#%E5%8D%81%E4%B8%80tipview)、[FlipView](https://github.com/Trinea/android-open-project#%E5%8D%81%E4%BA%8Cflipview)、[ColorPickView](https://github.com/Trinea/android-open-project#%E5%8D%81%E4%B8%89colorpickview)、[GraphView](https://github.com/Trinea/android-open-project#%E5%8D%81%E5%9B%9Bgraphview)、[UI Style](https://github.com/Trinea/android-open-project#%E5%8D%81%E4%BA%94ui-style)、[其他](https://github.com/Trinea/android-open-project#%E5%8D%81%E5%85%AD%E5%85%B6%E4%BB%96)*  
[Android开源项目第二篇——工具库篇](https://github.com/Trinea/android-open-project#%E7%AC%AC%E4%BA%8C%E9%83%A8%E5%88%86-%E5%B7%A5%E5%85%B7%E5%BA%93)  
*&nbsp;&nbsp;包括[依赖注入](https://github.com/Trinea/android-open-project#%E4%B8%80%E4%BE%9D%E8%B5%96%E6%B3%A8%E5%85%A5di)、[图片缓存](https://github.com/Trinea/android-open-project#%E4%BA%8C%E5%9B%BE%E7%89%87%E7%BC%93%E5%AD%98)、[网络相关](https://github.com/Trinea/android-open-project#%E4%B8%89%E7%BD%91%E7%BB%9C%E7%9B%B8%E5%85%B3)、[数据库ORM工具包](https://github.com/Trinea/android-open-project#%E5%9B%9B%E6%95%B0%E6%8D%AE%E5%BA%93-orm%E5%B7%A5%E5%85%B7%E5%8C%85)、[Android公共库](https://github.com/Trinea/android-open-project#%E4%BA%94android%E5%85%AC%E5%85%B1%E5%BA%93)、[高版本向低版本兼容库](https://github.com/Trinea/android-open-project#%E5%85%ADandroid-%E9%AB%98%E7%89%88%E6%9C%AC%E5%90%91%E4%BD%8E%E7%89%88%E6%9C%AC%E5%85%BC%E5%AE%B9)、[多媒体](https://github.com/Trinea/android-open-project#%E4%B8%83%E5%A4%9A%E5%AA%92%E4%BD%93%E7%9B%B8%E5%85%B3)、[事件总线](https://github.com/Trinea/android-open-project#%E5%85%AB%E4%BA%8B%E4%BB%B6%E6%80%BB%E7%BA%BF%E8%AE%A2%E9%98%85%E8%80%85%E6%A8%A1%E5%BC%8F)、[传感器](https://github.com/Trinea/android-open-project#%E4%B9%9D%E4%BC%A0%E6%84%9F%E5%99%A8)、[安全](https://github.com/Trinea/android-open-project#%E5%8D%81%E5%AE%89%E5%85%A8)、[插件化](https://github.com/Trinea/android-open-project#%E5%8D%81%E4%B8%80%E6%8F%92%E4%BB%B6%E5%8C%96)、[文件](https://github.com/Trinea/android-open-project#%E5%8D%81%E4%BA%8C%E6%96%87%E4%BB%B6)、[其他](https://github.com/Trinea/android-open-project#%E5%8D%81%E4%B8%89%E5%85%B6%E4%BB%96)*  
[Android开源项目第三篇——优秀项目篇](https://github.com/Trinea/android-open-project#%E7%AC%AC%E4%B8%89%E9%83%A8%E5%88%86-%E4%BC%98%E7%A7%80%E9%A1%B9%E7%9B%AE)  
*&nbsp;&nbsp;比较有意思的完整的Android项目*  
[Android开源项目第四篇——开发及测试工具篇](https://github.com/Trinea/android-open-project#%E7%AC%AC%E5%9B%9B%E9%83%A8%E5%88%86-%E5%BC%80%E5%8F%91%E5%B7%A5%E5%85%B7%E5%8F%8A%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7)  
*&nbsp;&nbsp;包括[开发效率工具](https://github.com/Trinea/android-open-project#%E4%B8%80%E5%BC%80%E5%8F%91%E6%95%88%E7%8E%87%E5%B7%A5%E5%85%B7)、[开发自测相关](https://github.com/Trinea/android-open-project#%E4%BA%8C%E5%BC%80%E5%8F%91%E8%87%AA%E6%B5%8B%E7%9B%B8%E5%85%B3)、[测试工具](https://github.com/Trinea/android-open-project#%E4%B8%89%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7)、[开发及编译环境](https://github.com/Trinea/android-open-project#%E5%9B%9B%E5%BC%80%E5%8F%91%E5%8F%8A%E7%BC%96%E8%AF%91%E7%8E%AF%E5%A2%83)、[其他](https://github.com/Trinea/android-open-project#%E4%BA%94%E5%85%B6%E4%BB%96)*  
[Android开源项目第五篇——优秀个人和团体篇](https://github.com/Trinea/android-open-project#%E7%AC%AC%E4%BA%94%E9%83%A8%E5%88%86)  
*&nbsp;&nbsp;乐于分享并且有一些很不错的开源项目的[个人](https://github.com/Trinea/android-open-project#%E4%B8%80%E4%B8%AA%E4%BA%BA)和[组织](https://github.com/Trinea/android-open-project#%E4%BA%8C%E7%BB%84%E7%BB%87)，包括JakeWharton、Chris Banes、Koushik Dutta等大牛*  

## 第一部分 个性化控件(View)  
主要介绍那些不错个性化的View，包括ListView、ActionBar、Menu、ViewPager、Gallery、GridView、ImageView、ProgressBar、TextView、ScrollView、TimeView、TipView、FlipView、ColorPickView、GraphView、UI Style等等。  

#### 一、ListView  
1. android-pulltorefresh  
一个强大的拉动刷新开源项目，支持各种控件下拉刷新，ListView、ViewPager、WebView、ExpandableListView、GridView、ScrollView、Horizontal  ScrollView、Fragment上下左右拉动刷新，比下面johannilsson那个只支持ListView的强大的多。并且它实现的下拉刷新ListView在item不足一屏情况下也不会显示刷新提示，体验更好。  
项目地址：https://github.com/chrisbanes/Android-PullToRefresh  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/pull-to-refreshview-demo.apk?raw=true  
APP示例：新浪微博各个页面  

1. android-pulltorefresh-listview  
下拉刷新ListView，这个被很多人使用的项目实际有不少bug，推荐使用上面的android-pulltorefresh  
项目地址：https://github.com/johannilsson/android-pulltorefresh  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/pull-to-refresh-listview-demo.apk?raw=true  

1. android-Ultra-Pull-to-Refresh  
下拉刷新，第一个项目已经停止维护了，并且使用起来相对复杂，定制性也差。这个是替代和改良方案。这个继承于ViewGroup可以包含任何View。功能甚至比SwipeRefreshLayout强大。使用起来非常简单。良好的设计，如果你想定制自己的UI样式，非常简单，就像给ListView加一个Header View那么简单。支持 `API LEVEL >= 8`  
项目地址：https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh  
Demo地址：https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh/blob/master/ptr-demo/target/ultra-ptr-demo.apk?raw=true  
效果图：  
<div>  
  <img src='http://srain-github.qiniudn.com/ultra-ptr/contains-all-of-views.gif' width="150px"/>  
  <img src='http://srain-github.qiniudn.com/ultra-ptr/release-to-refresh.gif' width="150px"/>  
  <img src='http://srain-github.qiniudn.com/ultra-ptr/auto-refresh.gif' width="150px"/>  
  <img src='http://srain-github.qiniudn.com/ultra-ptr/store-house-string-array.gif' width="150px"/>  
</div>  

1. DropDownListView  
下拉刷新及滑动到底部加载更多ListView  
项目地址：https://github.com/Trinea/AndroidCommon  
Demo地址：https://play.google.com/store/apps/details?id=cn.trinea.android.demo  
文档介绍：http://www.trinea.cn/android/dropdown-to-refresh-and-bottom-load-more-listview/  

1. DragSortListView  
拖动排序的ListView，同时支持ListView滑动item删除，各个Item高度不一、单选、复选、CursorAdapter做为适配器、拖动背景变化等  
项目地址：https://github.com/bauerca/drag-sort-listview  
Demo地址：https://play.google.com/store/apps/details?id=com.mobeta.android.demodslv  
APP示例：Wordpress Android  

1. SwipeListView  
支持定义ListView左右滑动事件，支持左右滑动位移，支持定义动画时间  
项目地址：https://github.com/47deg/android-swipelistview  
Demo地址：https://play.google.com/store/apps/details?id=com.fortysevendeg.android.swipelistview  
APP示例：微信  

1. Android-SwipeToDismiss  
滑动Item消失ListView，支持3.0以下版本见：https://github.com/JakeWharton/SwipeToDismissNOA  
项目地址：https://github.com/romannurik/Android-SwipeToDismiss  
Demo地址：https://github.com/JakeWharton/SwipeToDismissNOA/SwipeToDismissNOA.apk/qr_code  

1. PinnedHeaderExpandableListView  
首先它是一个ExpandableListView，但是它的头部可以固定，其次，在它的上面还有一个头部可以来回伸缩  
项目地址：https://github.com/singwhatiwanna/PinnedHeaderExpandableListView  
效果图：![Renderings](https://camo.githubusercontent.com/fa7f516b0b6e2921007a17cbc359b3f661f32226/687474703a2f2f696d672e626c6f672e6373646e2e6e65742f32303134303531313135313534363834333f77617465726d61726b2f322f746578742f6148523063446f764c324a736232637559334e6b626935755a58517663326c755a33646f5958527064324675626d453d2f666f6e742f3561364c354c32542f666f6e7473697a652f3430302f66696c6c2f49304a42516b46434d413d3d2f646973736f6c76652f37302f677261766974792f536f75746845617374)  
APP示例：百度手机卫士垃圾清理界面  

1. StickyListHeaders  
GroupName滑动到顶端时会固定不动直到另外一个GroupName到达顶端的ExpandListView，支持快速滑动，支持Android2.3及以上  
项目地址：https://github.com/emilsjolander/StickyListHeaders  
效果图：![Renderings](https://raw.github.com/emilsjolander/StickyListHeaders/master/demo.gif)  
APP示例：Android 4.0联系人  

1. pinned-section-listview  
GroupName滑动到顶端时会固定不动直到另外一个GroupName到达顶端的ExpandListView  
项目地址：https://github.com/beworker/pinned-section-listview  
效果图：![Renderings](https://raw.github.com/beworker/pinned-section-listview/master/screen1.png)  

1. PinnedHeaderListView  
GroupName滑动到顶端时会固定不动直到另外一个GroupName到达顶端的ExpandListView  
项目地址：https://github.com/JimiSmith/PinnedHeaderListView  

1. QuickReturn  
ListView/ScrollView的header或footer，当向下滚动时消失，向上滚动时出现  
项目地址：https://github.com/lawloretienne/QuickReturn  
Demo地址：https://play.google.com/store/apps/details?id=com.etiennelawlor.quickreturn  

1. QuickReturnHeader  
ListView/ScrollView的header或footer，当向下滚动时消失，向上滚动时出现  
项目地址：https://github.com/ManuelPeinado/QuickReturnHeader  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/quick-return-header-demo.apk?raw=true  
APP示例：google plus  

1. IndexableListView  
ListView右侧会显示item首字母快捷索引，点击可快速滑动到某个item  
项目地址：https://github.com/woozzu/IndexableListView  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/indexable-listview.apk?raw=true  
APP示例：微信通讯录、小米联系人  

1. CustomFastScrollView  
ListView快速滑动，同时屏幕中间PopupWindows显示滑动到的item内容或首字母  
项目地址：https://github.com/nolanlawson/CustomFastScrollViewDemo  
效果图：![Renderings](https://raw.github.com/nolanlawson/CustomFastScrollViewDemo/master/example.png)  

1. Android-ScrollBarPanel  
ListView滑动时固定的Panel指示显示在scrollbar旁边  
项目地址：https://github.com/rno/Android-ScrollBarPanel  
效果图：![Renderings](https://github.com/rno/Android-ScrollBarPanel/raw/master/demo_capture.png)  

1. SlideExpandableListView  
用户点击listView item滑出固定区域，其他item的区域收缩  
项目地址：https://github.com/tjerkw/Android-SlideExpandableListView  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/slide-expandable-listView-demo.apk?raw=true  

1. JazzyListView  
ListView及GridView item以特殊动画效果进入屏幕，效果包括grow、cards、curl、wave、flip、fly等等  
项目地址：https://github.com/twotoasters/JazzyListView  
Demo地址：https://play.google.com/store/apps/details?id=com.twotoasters.jazzylistview.sample  
在线演示：http://lab.hakim.se/scroll-effects/  

1. ListViewAnimations  
带Item显示动画的ListView，动画包括底部飞入、其他方向斜飞入、下层飞入、渐变消失、滑动删除等  
项目地址：https://github.com/nhaarman/ListViewAnimations  
Demo地址：https://play.google.com/store/apps/details?id=com.haarman.listviewanimations  
APP示例：Google plus、Google Now卡片式进入、小米系统中应用商店、联系人、游戏中心、音乐、文件管理器的ListView、Ultimate、Light Flow Lite、TreinVerkeer、Running Coach、Pearl Jam Lyrics、Calorie Chart、Car Hire、Super BART、DK FlashCards、Counter Plus、Voorlees Verhaaltjes 2.0  

1. DevsmartLib-Android  
横向ListView  
项目地址：https://github.com/dinocore1/DevsmartLib-Android  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/horizontal-listview-demo.apk?raw=true  

1. TwoWayView  
横向ListView的效果，继承自AdapterView  
项目地址：https://github.com/lucasr/twoway-view  

1. HorizontalVariableListView  
支持Item宽度不一致的ListView  
项目地址：https://github.com/sephiroth74/HorizontalVariableListView  

1. LinearListView  
用LinearLayout实现的ListView，可解决多个ListView并存等问题。目前自己也有需要，等亲自尝试过后会再具体介绍  
项目地址：https://github.com/frankiesardo/LinearListView  

1. MultiChoiceAdapter  
支持多选的ListView Adapter  
项目地址：https://github.com/ManuelPeinado/MultiChoiceAdapter  
Demo地址：https://play.google.com/store/apps/details?id=com.manuelpeinado.multichoiceadapter.demo  

1. EnhancedListView  
支持横向滑动删除列表项以及撤销删除的ListView，该项目的前身是[SwipeToDismissUndoList](https://github.com/timroes/SwipeToDismissUndoList)  
项目地址：https://github.com/timroes/EnhancedListView  
Demo地址：https://play.google.com/store/apps/details?id=de.timroes.android.listviewdemo&rdid=de.timroes.android.listviewdemo  

1. ListBuddies  
自动滚动的双列ListView ，两个ListView滚动速度不一致，有视差效果  
项目地址：https://github.com/jpardogo/ListBuddies  
Demo地址：https://play.google.com/store/apps/details?id=com.jpardogo.android.listbuddies  
效果图：![Renderings](https://raw.github.com/jpardogo/ListBuddies/master/art/screenshot_listbuddies_2.png)  

1. SwipeMenuListView  
针对ListView item的侧滑菜单  
项目地址：https://github.com/baoyongzhang/SwipeMenuListView  
效果图：![Renderings](https://raw.githubusercontent.com/baoyongzhang/SwipeMenuListView/master/demo.gif)  
APP示例：手机QQV5.0  

1. PagingListView  
分页加载的ListView。当滑动到ListView底部最后一个元素时，显示一个进度行，然后加载下一页数据，并显示。  
项目地址：https://github.com/nicolasjafelle/PagingListView  

1. PullZoomView  
支持下拉时HeaderView缩放的ListView、ScrollView  
项目地址：https://github.com/Frank-Zhu/PullZoomView  
效果图：![Renderings](https://raw.githubusercontent.com/Frank-Zhu/PullZoomView/master/art/pull-to-zoom.gif)  

1. PullToZoomInListView  
滑动ListView时使其HeaderView跟随滑动缩放  
项目地址：https://github.com/matrixxun/PullToZoomInListView  
效果图：![Renderings](https://github.com/matrixxun/PullToZoomInListView/raw/master/art/pull-to-zoom.gif)  

1. CalendarListview  
实现每个月一行日历效果的ListView  
项目地址：https://github.com/traex/CalendarListview  
效果图：![Renderings](https://github.com/traex/CalendarListview/raw/master/demo.gif)  

1. sticky-headers-recyclerview  
GroupName滑动到顶端时会固定不动直到另外一个GroupName到达顶端的ListView，采用support-v7中的RecyclerView实现  
项目地址：https://github.com/timehop/sticky-headers-recyclerview  

1. PullSeparateListView  
到达顶部或底部继续拉动时，实现Item间的相互分离，两种模式：(1) 全部分离的模式，即屏幕内所有Item都会分离 (2)部分分离模式，以点击位置为分界点，部分item分离  
项目地址：https://github.com/chiemy/PullSeparateListView  
效果图：![Renderings](https://github.com/chiemy/PullSeparateListView/raw/master/capture.gif)  

1. ExpandableLayout  
Header 和 Content Item 都可以展开的 ExpandableListview  
项目地址：https://github.com/traex/ExpandableLayout  

1. PagedHeadListView  
支持paginated header以及material page indicator的ListView.  
项目地址：https://github.com/JorgeCastilloPrz/PagedHeadListView  
效果图：![Renderings](https://raw.githubusercontent.com/JorgeCastilloPrz/PagedHeadListView/master/app/src/main/res/raw/preview1.gif)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

1. CustomSwipeListView  
支持左滑弹出自定义菜单，右滑删除且允许撤销，同时可以自定义滑动动画时间和滑动触发事件的时机等。   
项目地址：https://github.com/xyczero/Android-CustomSwipeListView   
效果图：![screenshot](http://7u2jsw.com1.z0.glb.clouddn.com/githubCustomSwipeListview_Set.PNG)   
Demo地址：[Download here](http://7u2jsw.com1.z0.glb.clouddn.com/githubCustomSwipeListView.apk)   

1. Pull-to-Refresh.Rentals-Android  
提供一个简单可以自定义的下拉刷新实现，[Yalantis](http://yalantis.com/) 出品。  
项目地址：https://github.com/Yalantis/Pull-to-Refresh.Rentals-Android  
效果图：![Renderings](https://camo.githubusercontent.com/d406ac5a03a2b1fa5cf41fadc8d2408cb8709bdc/68747470733a2f2f6431337961637572716a676172612e636c6f756466726f6e742e6e65742f75736572732f3132353035362f73637265656e73686f74732f313635303331372f7265616c6573746174652d70756c6c5f312d322d332e676966)  

1. ScrollerCalendar  
实现每行显示一年的12个月份的RecyclerView年历  
项目地址：https://github.com/guanchao/ScrollerCalendar  
效果图：![Renderings](https://raw.githubusercontent.com/guanchao/ScrollerCalendar/master/images/sample2.gif)  

#### 二、ActionBar  
1. ActionBarSherlock  
为Android所有版本提供统一的ActionBar，解决4.0以下ActionBar的适配问题  
项目地址：https://github.com/JakeWharton/ActionBarSherlock  
Demo地址：https://play.google.com/store/apps/details?id=com.actionbarsherlock.sample.demos  
APP示例：太多了。。现在连google都在用  

1. ActionBar-PullToRefresh  
下拉刷新，ActionBar出现加载中提示  
项目地址：https://github.com/chrisbanes/ActionBar-PullToRefresh  
Demo地址：https://play.google.com/store/apps/details?id=uk.co.senab.actionbarpulltorefresh.samples.stock  
APP示例：Gmail，Google plus，知乎等  

1. FadingActionBar  
ListView向下滚动逐渐显现的ActionBar  
项目地址：https://github.com/ManuelPeinado/FadingActionBar  
Demo地址：https://play.google.com/store/apps/details?id=com.manuelpeinado.fadingactionbar.demo  
APP示例：google music，知乎  

1. NotBoringActionBar  
google music下拉收缩的ActionBar  
项目地址：https://github.com/flavienlaurent/NotBoringActionBar  
Demo地址：http://flavienlaurent.com/blog/2013/11/20/making-your-action-bar-not-boring/  
APP示例：Google音乐  

1. RefreshActionItem  
带进度显示和刷新按钮的ActionBar  
项目地址：https://github.com/ManuelPeinado/RefreshActionItem  
Demo地址：https://play.google.com/store/apps/details?id=com.manuelpeinado.refreshactionitem.demo  
APP示例：The New York Times，DevAppsDirect.  

1. GlassActionBar  
类似玻璃的有一定透明度的ActionBar  
项目地址：https://github.com/ManuelPeinado/GlassActionBar  
Demo地址：https://play.google.com/store/apps/details?id=com.manuelpeinado.glassactionbardemo  
APP示例：google music  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 三、Menu  
1. MenuDrawer  
滑出式菜单，通过拖动屏幕边缘滑出菜单，支持屏幕上下左右划出，支持当前View处于上下层，支持Windows边缘、ListView边缘、ViewPager变化划出菜单等。  
项目地址：https://github.com/SimonVT/android-menudrawer  
Demo地址：http://simonvt.github.io/android-menudrawer/  
APP示例：Gmail、Google Music等大部分google app  

1. SlidingMenu  
滑出式菜单，通过拖动屏幕边缘滑出菜单，支持屏幕左右划出，支持菜单zoom、scale、slide up三种动画样式出现。与MenuDrawer相比而言，SlidingMenu支持菜单动画样式出现，MenuDrawer支持菜单view处于内容的上下层  
项目地址：https://github.com/jfeinstein10/SlidingMenu  
Demo地址：https://play.google.com/store/apps/details?id=com.slidingmenu.example  
APP示例：Foursquare, LinkedIn, Zappos, Rdio, Evernote Food, Plume, VLC for Android, ESPN ScoreCenter, MLS MatchDay, 9GAG, Wunderlist 2, The Verge, MTG Familiar, Mantano Reader, Falcon Pro (BETA), MW3 Barracks  

1. ArcMenu  
支持类似Path的左下角动画旋转菜单及横向划出菜单、圆心弹出菜单  
项目地址：https://github.com/daCapricorn/ArcMenu  
效果图：![Renderings](https://dl.dropboxusercontent.com/u/11369687/preview0.png)  
https://dl.dropboxusercontent.com/u/11369687/preview1.png  
https://dl.dropboxusercontent.com/u/11369687/raymenu.png  
APP示例：Path  

1. android-satellite-menu  
类似Path的左下角动画旋转菜单  
项目地址：https://github.com/siyamed/android-satellite-menu  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/satellite-menu-demo.apk?raw=true  
APP示例：Path  

1. radial-menu-widget  
圆形菜单，支持二级菜单  
项目地址：https://code.google.com/p/radial-menu-widget/  
效果图：http://farm8.staticflickr.com/7377/11621125154_d1773c2dcc_o.jpg  

1. Android Wheel Menu  
圆形旋转选取菜单  
项目地址：https://github.com/anupcowkur/Android-Wheel-Menu  
效果图：![Renderings](https://raw.github.com/anupcowkur/Android-Wheel-Menu/master/graphics/wheel.gif)  

1. FoldingNavigationDrawer  
滑动并以折叠方式打开菜单  
项目地址：https://github.com/tibi1712/FoldingNavigationDrawer-Android  
Demo地址：https://play.google.com/store/apps/details?id=com.ptr.folding.sample  
效果图：![Renderings](https://lh6.ggpht.com/VnKUZenAozQ0KFAm5blFTGqMaKFjvX-BK2JH-jrX1sIXVTqciACqRhqFH48hc4pm2Q=h310-rw)  

1. AndroidResideMenu  
仿 Dribbble 的边栏菜单  
项目地址：https://github.com/SpecialCyCi/AndroidResideMenu  
效果图：![Renderings](https://github.com/SpecialCyCi/AndroidResideMenu/raw/master/2.gif)  

1. CircularFloatingActionMenu  
一个可定制的圆形的浮动菜单控件，类似于Path的圆形菜单。这个控件的可定制性更强，可以很容易的定制菜单出现消失时的动画，起始角度和半径。  
项目地址：https://github.com/oguzbilgener/CircularFloatingActionMenu  
Demo地址：https://github.com/oguzbilgener/CircularFloatingActionMenu/tree/master/samples  
效果图：![Renderings](https://raw.githubusercontent.com/oguzbilgener/CircularFloatingActionMenu/master/assets/circularfab.gif)  

1. NavigationDrawerSI  
Navigation Drawer的一个简单实现，滑动并以折叠方式打开菜单  
项目地址：https://github.com/mmBs/NavigationDrawerSI  
Demo地址：https://play.google.com/store/apps/details?id=mmbialas.pl.navigationdrawersi  
效果图：<img height="500px" src="https://raw.githubusercontent.com/mmBs/NavigationDrawerSI/master/images/screens.png" />  
APP示例：https://play.google.com/store/apps/details?id=mmbialas.pl.navigationdrawersi  

1. DragLayout  
使用support.v4包下的ViewDragHelper实现QQ5.0侧滑  
项目地址：https://github.com/BlueMor/DragLayout  
效果图：![Renderings](https://github.com/BlueMor/DragLayout/raw/master/screenshots/123.gif)  

1. LDrawer  
Material Design 形式的展开折叠Icon  
项目地址：https://github.com/ikimuhendis/LDrawer  
效果图：![Renderings](https://raw.githubusercontent.com/IkiMuhendis/LDrawer/master/images/animated.gif)  

1. Floating Action Button  
悬浮的圆形菜单栏，支持组建滚动时自动隐藏及其他设置  
项目地址：https://github.com/shamanland/floating-action-button  
效果图：![Renderings](https://camo.githubusercontent.com/c679cb23cf62830b0d4037e17cf2d8d4090bc3c8/68747470733a2f2f64726976652e676f6f676c652e636f6d2f75633f69643d3042776830534e4c506d6a5142526b466f5a4530345646393051324d)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

1. Side-Menu.Android  
分类侧滑菜单，[Yalantis](http://yalantis.com/) 出品。  
项目地址：https://github.com/Yalantis/Side-Menu.Android  
效果图：![Renderings](https://camo.githubusercontent.com/cb6caa7a392d01d46bca9d9485c01fc173f55fac/68747470733a2f2f6431337961637572716a676172612e636c6f756466726f6e742e6e65742f75736572732f3132353035362f73637265656e73686f74732f313638393932322f6576656e74732d6d656e755f312d312d362e676966)  

1. Context-Menu.Android  
可以方便快速集成漂亮带有动画效果的上下文菜单，[Yalantis](http://yalantis.com/)出品。  
项目地址：https://github.com/Yalantis/Context-Menu.Android  
效果图：![Renderings](https://camo.githubusercontent.com/46c15734b552ce3afefa7efd1518909046b4677e/68747470733a2f2f6431337961637572716a676172612e636c6f756466726f6e742e6e65742f75736572732f3132353035362f73637265656e73686f74732f313738353237342f39396d696c65732d70726f66696c652d6c696768745f312d312d342e676966)  

#### 四、ViewPager 、Gallery  
1. Android-ViewPagerIndicator  
配合ViewPager使用的Indicator，支持各种位置和样式  
项目地址：https://github.com/JakeWharton/Android-ViewPagerIndicator  
Demo地址：https://play.google.com/store/apps/details?id=com.viewpagerindicator.sample  
APP示例：太多了。。  

1. JazzyViewPager  
支持Fragment切换动画的ViewPager，动画包括转盘、淡入淡出、翻页、层叠、旋转、方块、翻转、放大缩小等，效果类似桌面左右切换的各种效果，不过桌面并非用ViewPager实现而已  
项目地址：https://github.com/jfeinstein10/JazzyViewPager  
Demo地址：https://github.com/jfeinstein10/JazzyViewPager/blob/master/JazzyViewPager.apk?raw=true  

1. JellyViewPager  
特殊切换动画的ViewPager  
项目地址：https://github.com/chiemy/JellyViewPager  
效果图：![Renderings](https://github.com/chiemy/JellyViewPager/raw/master/capture.gif)  

1. Android-DirectionalViewPager  
支持横向和纵向(垂直)的ViewPager  
项目地址：https://github.com/JakeWharton/Android-DirectionalViewPager  
Demo地址：https://market.android.com/details?id=com.directionalviewpager.sample  

1. android-pulltorefresh  
支持下拉刷新的ViewPager  
项目地址：https://github.com/chrisbanes/Android-PullToRefresh  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/pull-to-refreshview-demo.apk?raw=true  
APP示例：新浪微博各个页面  

1. FancyCoverFlow  
支持Item切换动画效果的类似Gallery View  
项目地址：https://github.com/davidschreiber/FancyCoverFlow  
Demo地址：https://play.google.com/store/apps/details?id=at.technikum.mti.fancycoverflow.samples  
效果图：![Renderings](https://github-camo.global.ssl.fastly.net/ef5ced52b7b54652b50499521ed797c0188c7a6b/687474703a2f2f64617669647363687265696265722e6769746875622e696f2f46616e6379436f766572466c6f772f73637265656e73686f74322e706e67)  

1. AndroidTouchGallery  
支持双击或双指缩放的Gallery(用ViewPager实现)，相比下面的PhotoView，在被放大后依然能滑到下一个item，并且支持直接从url和文件中获取图片，  
项目地址：https://github.com/Dreddik/AndroidTouchGallery  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/touch-gallery-demo.apk?raw=true  
APP示例：类似微信中查看聊天记录图片时可双击放大，并且放大情况下能正常左右滑动到前后图片  

1. Android Auto Scroll ViewPager  
Android自动滚动 轮播循环的ViewPager  
项目地址：https://github.com/Trinea/android-auto-scroll-view-pager  
Demo地址：https://play.google.com/store/apps/details?id=cn.trinea.android.demo  
文档介绍：http://www.trinea.cn/android/auto-scroll-view-pager/  

1. Salvage view  
带View缓存的Viewpager PagerAdapter，很方便使用  
项目地址：https://github.com/JakeWharton/salvage  

1. Android PagerSlidingTabStrip  
配合ViewPager使用的Indicator，支持ViewPager Scroll时Indicator联动  
项目地址：https://github.com/astuetz/PagerSlidingTabStrip  
Demo地址：https://play.google.com/store/apps/details?id=com.astuetz.viewpager.extensions.sample  

1. ViewPager3D  
ViewPager3D效果  
项目地址：https://github.com/inovex/ViewPager3D  

1. AnimaTabsview  
仿网易云音乐标签切换的动画,带透明小三角  
项目地址：https://github.com/wuyexiong/transparent-over-animtabsview  
在线演示：http://v.youku.com/v_show/id_XNzA4MjY5NjA0.html  

1. LoopingViewPager  
无限循环的ViewPager  
项目地址：https://github.com/imbryk/LoopingViewPager  

1. android_page_curl  
翻书卷曲效果  
项目地址：https://github.com/harism/android_page_curl  
APP示例：iReader  
在线演示：https://www.youtube.com/watch?v=iwu7P5PCpsw  

1. ViewPagerIndicator  
简化并实现android的TabHost效果，顶部滑动tab，引导页，支持自定义tab样式,自定义滑动块样式和位置,自定义切换tab的过渡动画,子界面的预加载和界面缓存,设置界面是否可滑动  
项目地址：https://github.com/LuckyJayce/ViewPagerIndicator  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

1. ScreenSlideIndicator  
轻量级的圆形 Indicadtor，位置可以自由调整，不会对 ViewPager 产生任何影响。  
项目地址：[ScreenSlidePager](https://github.com/LyndonChin/Android-ScreenSlidePager)  
效果图：  
![](https://raw.githubusercontent.com/LyndonChin/Android-ScreenSlidePager/master/screenslidepager.gif)

#### 五、GridView  
1. StaggeredGridView  
允许非对齐行的GridView，类似Pinterest的瀑布流，并且跟ListView一样自带View缓存，继承自ViewGroup  
项目地址：https://github.com/maurycyw/StaggeredGridView  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/staggered-gridview-demo.apk?raw=true  
APP示例：Pinterest等  

1. AndroidStaggeredGrid  
允许非对齐行的GridView，类似Pinterest的瀑布流，继承自AbsListView  
项目地址：https://github.com/etsy/AndroidStaggeredGrid  
APP示例：Pinterest等  

1. PinterestLikeAdapterView  
允许非对齐行的GridView，类似Pinterest的瀑布流，允许下拉刷新  
项目地址：https://github.com/GDG-Korea/PinterestLikeAdapterView  
APP示例：Pinterest等  

1. DraggableGridView  
Item可拖动交换位置的GridView，实际是自己继承ViewGroup实现，类似桌面的单屏效果，可屏幕自动上下滚动进行Item移动交换，多屏效果见下面PagedDragDropGrid  
项目地址：https://github.com/thquinn/DraggableGridView  
Demo地址：https://github.com/thquinn/DraggableGridView/blob/master/bin/DraggableGridViewSample.apk?raw=true  

1. StickyGridHeaders  
GroupName滑动到顶端时会固定不动直到另外一个GroupName到达顶端的GridView  
项目地址：https://github.com/TonicArtos/StickyGridHeaders  
效果图：![Renderings](https://github-camo.global.ssl.fastly.net/90b57e9383704c400706545225d439e057c6fcc0/687474703a2f2f342e62702e626c6f6773706f742e636f6d2f2d535f4262685758367754592f55517057306377554745492f41414141414141414776552f7a7a4a586a2d50635662592f73313630302f73637265656e2d6c616e6473636170652d736d616c6c65722e706e67)  

1. PagedDragDropGrid  
Item可拖动交换位置、拖动删除的自定义控件，实际是自己继承ViewGroup实现，类似桌面的多屏效果，可拖动到屏幕边缘，屏幕自动左右滚动进行Item移动交换，可拖动进行删除，单屏效果见上面DraggableGridView  
项目地址：https://github.com/mrKlar/PagedDragDropGrid  
在线演示：http://youtu.be/FYTSRfthSuQ  

1. Android-DraggableGridViewPager  
Item可拖动交换位置的GridView，实际是自己继承ViewGroup实现，类似桌面的多屏效果，可屏幕自动左右滚动进行Item移动交换，单屏效果见上面DraggableGridView  
项目地址：https://github.com/zzhouj/Android-DraggableGridViewPager  
Demo地址：https://github.com/Trinea/trinea-download/blob/master/draggable-grid-viewpager-demo.apk?raw=true  

1. TwoWayGridView  
可横向滚动的GridView  
项目地址：https://github.com/jess-anders/two-way-gridview  

1. PagingGridView  
分页加载的GridView。当滑动到GridView底部最后一个行时，显示一个进度行，然后加载下一页数据，并显示。  
项目地址：https://github.com/nicolasjafelle/PagingGridView  

1. AsymmetricGridView  
一个支持跨行和跨列可变Item大小的GridView  
项目地址：https://github.com/felipecsl/AsymmetricGridView  
Demo地址：https://play.google.com/store/apps/details?id=com.felipecsl.asymmetricgridview.app  
效果图：![Renderings](https://raw.githubusercontent.com/felipecsl/AsymmetricGridView/master/screenshots/ss_5_cols.png)  

1. GridView with Header and Footer  
和`ListView`一样带头部和底部的`GridView`，用法和`ListView`一样  
项目地址：https://github.com/liaohuqiu/android-GridViewWithHeaderAndFooter  
效果图：![Screen Shot](https://raw.githubusercontent.com/liaohuqiu/android-GridViewWithHeaderAndFooter/master/screen-shot.png)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 六、ImageView  
1. PhotoView  
支持双击或双指缩放的ImageView，在ViewPager等Scrolling view中正常使用，相比上面的AndroidTouchGallery，不仅支持ViewPager，同时支持单个ImageView  
项目地址：https://github.com/chrisbanes/PhotoView  
Demo地址：https://play.google.com/store/apps/details?id=uk.co.senab.photoview.sample  
APP示例：photup  

1. android-gif-drawable  
支持gif显示的view，用jni实现的，编译生成so库后直接xml定义view即可，而且本身不依赖于其他开源项目所以相对下面的ImageViewEx简单的多  
项目地址：https://github.com/koral--/android-gif-drawable  

1. ImageViewEx  
支持Gif显示的ImageView，依赖很多，编译过程很繁琐  
项目地址：https://github.com/frapontillo/ImageViewEx  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/imageviewex-demo.apk?raw=true  

1. RoundedImageView  
带圆角的ImageView  
项目地址：https://github.com/vinc3m1/RoundedImageView  
效果图：![Renderings](https://raw.github.com/makeramen/RoundedImageView/master/screenshot.png)  

1. SelectableRoundedImageView  
ImageView允许四个角的每一个有不同的半径值。也允许椭圆形、圆形的形状或者边  
项目地址：https://github.com/pungrue26/SelectableRoundedImageView  
Demo地址：https://play.google.com/store/apps/details?id=com.joooonho  
效果图：![Renderings](https://camo.githubusercontent.com/25d2e5fb8783b5dd09c00b03091172a79c69350e/687474703a2f2f692e696d6775722e636f6d2f55355653376d322e706e673f31)  

1. ColorArt  
根据图片的均色设置背景色显示文字和图片，类似itune11中效果  
项目地址：https://github.com/MichaelEvans/ColorArt  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/color-art-demo.apk?raw=true  

1. CircleImageView  
圆形的ImageView  
项目地址：https://github.com/hdodenhof/CircleImageView  
效果图：![Renderings](https://raw.github.com/hdodenhof/CircleImageView/master/screenshot.png)  

1. ImageViewZoom  
支持放大和平移的ImageView  
项目地址：https://github.com/sephiroth74/ImageViewZoom  
APP示例：https://play.google.com/store/apps/details?id=com.aviary.android.feather  

1. KenBurnsView  
实现Ken Burns effect效果，达到身临其境效果的ImageView  
项目地址：https://github.com/flavioarfaria/KenBurnsView  

1. CustomShapeImageView  
各种形状的ImageView, 相比上面的圆形ImageView，多了更多形状  
项目地址：https://github.com/MostafaGazar/CustomShapeImageView  
效果图：![Renderings](https://raw.github.com/MostafaGazar/CustomShapeImageView/master/Screenshot_2013-11-05-23-08-12.png)  

1. Shape Image View  
可以自定义各种形状的ImageView, 并且支持边框  
项目地址：https://github.com/siyamed/android-shape-imageview  
效果图：<img height="500px" src="https://github.com/siyamed/android-shape-imageview/raw/master/images/shader-buble.png" /><img height="500px" src="https://github.com/siyamed/android-shape-imageview/raw/master/images/all-samples.png"/>  

1. TextDrawable  
一个用于生成带有文本或者字母的图片的轻量级库。扩展自Drawable，因此可用于现有/自定义/网络等ImageView类，并且包含一个流接口用于创建drawables以及一个定制的ColorGenerator  
项目地址：https://github.com/amulyakhare/TextDrawable  
效果图：![Renderings](https://raw.githubusercontent.com/amulyakhare/TextDrawable/master/screens/screen7.png)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 七、ProgressBar  
1. SmoothProgressBar  
水平进度条  
项目地址：https://github.com/castorflex/SmoothProgressBar  
Demo地址：https://play.google.com/store/apps/details?id=fr.castorflex.android.smoothprogressbar.sample  

1. ProgressWheel  
支持进度显示的圆形ProgressBar  
项目地址：https://github.com/Todd-Davies/ProgressWheel  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/progress-wheel-demo.apk?raw=true  

1. android-square-progressbar  
在图片周围显示进度  
项目地址：https://github.com/mrwonderman/android-square-progressbar  
Demo地址：https://play.google.com/store/apps/details?id=net.yscs.android.square_progressbar_example  
效果图：![Renderings](https://googledrive.com/host/0BwESwPCuXtw7eExwSFVLQkR2TTg/newscreen1.png)  
APP示例：square  

1. HoloCircularProgressBar  
Android4.1 时钟App样式  
项目地址：https://github.com/passsy/android-HoloCircularProgressBar  
效果图：![Renderings](https://raw.github.com/passsy/android-HoloCircularProgressBar/master/raw/screenshot1.png)  
APP示例：Android4.1时钟App  

1. ProgressButton  
通过图钉的不同状态显示进度  
项目地址：https://github.com/f2prateek/progressbutton  
效果图：![Renderings](http://f2prateek.com/progressbutton/static/states.png)  
文档介绍：http://f2prateek.com/progressbutton/  

1. GoogleProgressBar  
类似google 多个圆形卡片翻转的progressBar  
项目地址：https://github.com/jpardogo/GoogleProgressBar  
效果图：![Renderings](https://raw.githubusercontent.com/jpardogo/GoogleProgressBar/master/art/GoogleProgressBar.gif)  

1. TH-ProgressButton  
带圆形进度显示的按钮  
项目地址；https://github.com/torryharris/TH-ProgressButton  
效果图：![Renderings](https://raw.github.com/Vyshakh-K/TH-ProgressButton/master/screenshots/progressshot1.png)  ![Renderings](https://raw.github.com/Vyshakh-K/TH-ProgressButton/master/screenshots/progressshot2.png)  

1. NumberProgressBar  
带数字进度的进度条  
项目地址：https://github.com/daimajia/NumberProgressBar  
效果图：![Renderings](https://camo.githubusercontent.com/0c92568af7ec4e04e2e1503acdd2ca99854ab0b5/687474703a2f2f7777332e73696e61696d672e636e2f6d773639302f36313064633033346a77316566797264386e376937673230637a30326d7135662e676966)  

1. CircularProgressDrawable  
带圆形进度显示的进度条  
项目地址：https://github.com/Sefford/CircularProgressDrawable  
效果图：![Renderings](https://raw.githubusercontent.com/Sefford/CircularProgressDrawable/master/overshoot.gif)  

1. Android-RoundCornerProgressBar  
Android 圆角 ProgressBar，可自定义圆角颜色和半径，包括带 Icon 和不带 Icon 两种类型。  
项目地址：https://github.com/akexorcist/Android-RoundCornerProgressBar  
效果图：![Renderings](https://raw.githubusercontent.com/akexorcist/Android-RoundCornerProgressBar/master/image/screenshot_02.png)  

1. circular-progress-button  
带进度显示的Button  
项目地址：https://github.com/dmytrodanylyk/circular-progress-button  
效果图：![Renderings](https://raw.githubusercontent.com/dmytrodanylyk/circular-progress-button/master/screenshots/intro.gif)  

1. WaveView  
一个波纹效果的 View，可用来做 ProgressBar  
项目地址：https://github.com/john990/WaveView  
Demo地址：https://raw.github.com/john990/WaveView/master/screenshot%26apk/demo.unaligned.apk  
效果图：![Renderings](https://camo.githubusercontent.com/60722e9d4f2d2daa78a8650cb27a32adea82bdd4/68747470733a2f2f7261772e6769746875622e636f6d2f6a6f686e3939302f57617665566965772f6d61737465722f73637265656e73686f7425323661706b2f73637265656e73686f742e676966)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a> 

#### 八、TextView  
包括TextView及所有继承自TextView控件，如EditText、Button、RadioButton  

1. android-flowtextview  
文字自动环绕其他View的Layout  
项目地址：https://github.com/deano2390/FlowTextView  
效果图：http://i949.photobucket.com/albums/ad332/vostroman1500/1.png  

1. Android Form EditText  
验证输入合法性的编辑框，支持输入、英文、ip、url等多种正则验证  
项目地址：https://github.com/vekexasia/android-edittext-validator  
Demo地址：https://play.google.com/store/apps/details?id=com.andreabaccega.edittextformexample  

1. Emojicon  
支持emojis的TextView和EditText  
项目地址：https://github.com/rockerhieu/emojicon  
文档介绍：http://rockerhieu.com/emojicon/  

1. android-circlebutton  
Android圆形按钮，实际实现是继承自ImageView  
项目地址：https://github.com/markushi/android-circlebutton  
Demo地址：https://github.com/markushi/android-circlebutton/blob/master/example/example.apk  

1. Segmented Radio Buttons for Android  
iOS’s segmented controls的实现  
项目地址：https://github.com/vinc3m1/android-segmentedradiobutton  
Demo地址：https://github.com/thquinn/DraggableGridView/blob/master/bin/DraggableGridViewSample.apk?raw=true  
效果图：![Renderings](https://raw.github.com/vinc3m1/android-segmentedradiobutton/master/screens/segmentedradio.png)  

1. Chips EditText Library  
支持国家名字联想从而选择显示该国国旗的EditText，实际就是通过SpannableStringBuilder实现  
项目地址：https://github.com/kpbird/chips-edittext-library  
Demo地址：https://github.com/kpbird/chips-edittext-library/tree/master/ChipsEditTextDemo/bin  

1. AutoFitTextView  
可固定边界内容字体大小自适应的TextView  
项目地址：https://github.com/grantland/android-autofittextview  

1. Shimmer for Android  
文字发淡光的TextView  
项目地址：https://github.com/RomainPiel/Shimmer-android  

1. Titanic  
可以显示水位上升下降(不知道该怎么描述 囧)的TextView  
项目地址：https://github.com/RomainPiel/Titanic  
效果图：![Renderings](https://github.com/RomainPiel/Titanic/raw/master/titanic.gif)  

1. android-iconify  
提供带Icon的TextView,Menu,Button等  
项目地址：https://github.com/JoanZapata/android-iconify  

1. Calligraphy  
让我们在android开发中使用自定义字体变得更加简单  
项目地址 ：https://github.com/chrisjenx/Calligraphy  
效果图：![Renderings](https://github.com/chrisjenx/Calligraphy/raw/master/screenshot.png)  

1. CreditsRoll  
类似星球大战字幕效果的TextView  
项目地址：https://github.com/frakbot/CreditsRoll  

1. android-process-buton  
带加载或提交进度的Button  
项目地址：https://github.com/dmytrodanylyk/android-process-buton  

1. FButton  
扁平化的Button  
项目地址：https://github.com/hoang8f/android-flat-button  
Demo地址：https://play.google.com/store/apps/details?id=info.hoang8f.fbutton.demo  

1. FloatingActionButton  
一个类似Android版Google+浮动功能按钮的控件，可以响应ListView的滚动事件。当列表向上滚动的时候会自动显示，向下滚动的时候自动隐藏。  
项目地址：https://github.com/makovkastar/FloatingActionButton  
Demo地址：https://github.com/makovkastar/FloatingActionButton/tree/master/  
效果图：![Renderings](https://raw.githubusercontent.com/makovkastar/FloatingActionButton/master/art/demo.gif)  

1. Android Saripaar  
Android表单验证  
项目地址：https://github.com/ragunathjawahar/android-saripaar/  

1. JumpingBeans  
文字像 Mexican beans 一样跳动  
项目地址：https://github.com/frakbot/JumpingBeans  
Demo地址：http://play.google.com/store/apps/details?id=net.frakbot.jumpingbeans.demo  
效果图：![Renderings](https://github.com/frakbot/JumpingBeans/blob/master/art/jumpingdots.gif)  

1. FancyButtons  
一个不用图片就可以帮助我们创建出漂亮按钮的库。  
项目地址：https://github.com/medyo/fancybuttons  
Demo地址：https://github.com/medyo/fancybuttons/tree/master/samples  
效果图：![Renderings](https://camo.githubusercontent.com/8c5800ef180f69d302237132906737bf71a52caf/68747470733a2f2f7261772e6769746875622e636f6d2f6d6564796f2f66616e6379627574746f6e732f6d61737465722f73637265656e73686f74732f66616e63792e706e67)
![Renderings](https://raw.githubusercontent.com/medyo/fancybuttons/master/screenshots/fancy2.png)  

1. Android-RobotoTextView  
一个实现了所有Roboto字体的TextView，包括新出的Roboto Slab字体。  
项目地址：https://github.com/johnkil/Android-RobotoTextView  
Demo地址：http://play.google.com/store/apps/details?id=com.devspark.robototextview  
Demo项目：https://github.com/johnkil/Android-RobotoTextView/tree/master/robototextview-sample  
效果图：<img height="400px" src="https://camo.githubusercontent.com/f058c810055e1ff12fa995346059ad399d9c0f95/687474703a2f2f6934362e74696e797069632e636f6d2f6239646736392e706e67" />>  

1. Android-WizardPager  
一个表单向导库  
项目地址：https://github.com/romannurik/android-wizardpager  
Demo项目：https://github.com/str4d/android-wizardpager/tree/textfield  
效果图：<img height="400px" src="https://camo.githubusercontent.com/685a1eee3b9b7eb6a0409061031654ea7d6b0b17/68747470733a2f2f6c68352e676f6f676c6575736572636f6e74656e742e636f6d2f2d664944555a3074514373632f554a4e4c6a6e504c5447492f41414141414141416f4f382f784b63654f61746c6a50302f773431332d683638392d6e6f2f322e706e67" />  

1. RippleView  
一个实现了 Android L 上才引入的点击按钮后出现水波纹效果的按钮  
项目地址：https://github.com/siriscac/RippleView  
Demo项目：https://github.com/siriscac/RippleView/tree/master/RippleViewExample  
效果图：![Renderings](https://camo.githubusercontent.com/eec41193900aad4803dcf18bc9915fafa3f7d1cf/68747470733a2f2f7261772e6769746875622e636f6d2f73697269736361632f526970706c65566965772f6d61737465722f53637265656e732f53637265656e2e676966)  

1. RippleEffect  
一个实现Material Design Ripple效果的库，支持Android API 9+以上版本。  
项目地址：https://github.com/traex/RippleEffect  
Demo项目：https://github.com/traex/RippleEffect/tree/master/sample  
效果图：![Renderings](https://raw.githubusercontent.com/traex/RippleEffect/master/header.png)  

1. Android Floating Label Widgets  
包含一系列控件，这些控件特点是：有默认值，当值不为空时默认值浮动到上面变为提示  
项目地址：https://github.com/marvinlabs/android-floatinglabel-widgets  
Demo地址：https://play.google.com/store/apps/details?id=com.marvinlabs.widget.floatinglabel.demo  
在线演示：http://www.youtube.com/watch?v=hpZD9gJcRg0&feature=youtu.be  

1. MaterialEditText  
EditText 的 Material Design 实现。包含 [Google Material Design Spec](http://www.google.com/design/spec/components/text-fields.html)中的UI效果和一些新增特性。  
项目地址：https://github.com/rengwuxian/MaterialEditText  

1. MultiActionTextView  
可以分别给TextView中的某几个字设置点击事件的TextView  
项目地址：https://github.com/ajaysahani/MultiActionTextView  
效果图：![Renderings](https://camo.githubusercontent.com/1223e37d084e84ec0e22a1b27e7513661d0e1b39/687474703a2f2f692e696d6775722e636f6d2f773934576f53582e706e67)  

1. ToggleButton  
状态切换的 Button，类似 iOS，用 View 实现  
项目地址：https://github.com/zcweng/ToggleButton  
效果图：![Renderings](https://github.com/zcweng/ToggleButton/raw/master/ToggleButtonSample/21879.gif)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  


1. SlideSwitch  
状态切换的开关，可以设置为类似IOS的圆形，也可以设置为矩形，用 View 实现  
项目地址：https://github.com/Leaking/SlideSwitch  
效果图：![Renderings](https://github.com/Leaking/SlideSwitch/blob/master/Example/TestLibs/res/drawable-hdpi/slide_c.gif)  

1. ExpandableTextView  
可展开和收缩内容的TextView。  
项目地址：https://github.com/Manabu-GT/ExpandableTextView  
效果图：<img height="500px" src="https://camo.githubusercontent.com/8bf46083b3bd152c2051ae4c234649dbbb975376/68747470733a2f2f7261772e6769746875622e636f6d2f4d616e6162752d47542f457870616e6461626c6554657874566965772f6d61737465722f6172742f726561646d655f64656d6f2e676966" />
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 九、ScrollView  
1. Discrollview  
支持滚动时Item淡入淡出，平移，缩放效果的ScrollView  
项目地址：https://github.com/flavienlaurent/discrollview  
Demo地址：https://github.com/flavienlaurent/discrollview/raw/master/sample.apk  

1. PullScrollView  
仿照新浪微博Android客户端个人中心的ScrollView，下拉背景伸缩回弹效果。  
项目地址：https://github.com/MarkMjw/PullScrollView  
效果图：![Renderings](https://raw.github.com/MarkMjw/PullScrollView/master/Screenshots/1.png)  

1. ParallaxScrollView  
支持视差滚动的ScrollView ，背景图片的滚动速度小于ScrollView中子控件的滚动速度  
项目地址：https://github.com/chrisjenx/ParallaxScrollView  
Demo地址：http://cloud.github.com/downloads/chrisjenx/ParallaxScrollView/ParallaxScrollViewDemo-v1.0.5.apk  

1. AKParallax-Android  
支持视差滚动的ScrollView  
项目地址：https://github.com/ideaismobile/AKParallax-Android  
Demo地址：https://play.google.com/store/apps/details?id=com.appkraft.parallax_sample  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>   

1. Android-ObservableScrollView   
监听滚动视图滚动事件的库，帮助与Toolbar的交互动效处理与Material Design的实现   
项目地址：https://github.com/ksoichiro/Android-ObservableScrollView    
Demo地址：https://play.google.com/store/apps/details?id=com.github.ksoichiro.android.observablescrollview.samples2  

1. OverScrollView   
有弹性的ScrollView，实现了当手指滑动到ScrollView的顶部、底部时，可以继续的向上、向下拉伸。当释放手指的时候，向上、下回弹   
项目地址：https://github.com/EverythingMe/OverScrollView

#### 十、TimeView  
包括TimePicker、DatePicker、CalendarView、Clock等时间相关控件  

1. android-times-square  
Android日历时间部件，支持选取单个日期，多个日期，及日期区间段和对话框形式显示  
项目地址：https://github.com/square/android-times-square  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/times-square-demo.apk?raw=true  

1. android-calendar-card  
日历  
项目地址：https://github.com/kenumir/android-calendar-card  
Demo地址：https://play.google.com/store/apps/details?id=com.wt.calendarcardsample  
效果图：![Renderings](https://raw.github.com/kenumir/android-calendar-card/master/calendar-card-sample/_work/device-2013-10-12-151801.png)  

1. AndroidWheel  
Android Wheel支持城市、多种日期时间、密码、图片  
项目地址：https://code.google.com/p/android-wheel/  
效果图：![Renderings](http://farm6.staticflickr.com/5532/11621528786_220c040ba5_o.jpg)  

1. GoogleDateTimePickers  
时间选择部件  
项目地址：https://github.com/Mirkoddd/GoogleDateTimePickers  
文档介绍：https://play.google.com/store/apps/details?id=com.mirko.sample&hl=it  

1. DateTimePicker  
日期选择部件(Google Agenda的样式风格)  
项目地址：https://github.com/flavienlaurent/datetimepicker  
Demo地址：https://raw.github.com/biboune/datetimepicker/master/datetimepicker-sample.apk  
效果图：![Renderings](https://camo.githubusercontent.com/493edeea3eb553ad0d0b121dbead0d7ec6a858f2/68747470733a2f2f7261772e6769746875622e636f6d2f6269626f756e652f6461746574696d657069636b65722f6d61737465722f67726170686963732f696d67312e706e67)  

1. android-betterpickers  
提供日期、数字、时间（数字方式和钟表方式）、重复周期（闹钟的周期重复）、HMS（时、分、秒）的选择，支持以DialogFragment的弹窗选择  
项目地址：https://github.com/derekbrameyer/android-betterpickers  
Demo地址：https://play.google.com/store/apps/details?id=com.doomonafireball.betterpickers.sample
效果图：![Renderings](https://camo.githubusercontent.com/897ae3c71b49c4366565f3480719647687b1804a/68747470733a2f2f7261772e6769746875622e636f6d2f646572656b6272616d657965722f616e64726f69642d6265747465727069636b6572732f6d61737465722f73616d706c652f696d61676572792f7765625f666561747572655f677261706869632e706e67)  

1. Android Week View  
日期控件，支持周，天视图，支持自定义样式  
项目地址：https://github.com/alamkanak/Android-Week-View  
效果图：![Renderings](https://github.com/alamkanak/Android-Week-View/blob/master/images/screen-shot.png)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 十一、TipView  
包括Toast、角标、UndoBar等提示性控件  

1. Crouton  
丰富样式的Toast，允许alert、comfirm、info样式及点击消失样式，允许设置Toast显示时间，允许自定义View。 本文32. SuperToasts为其扩展版  
项目地址：https://github.com/keyboardsurfer/Crouton  
Demo地址：http://play.google.com/store/apps/details?id=de.keyboardsurfer.app.demo.crouton  

1. supertooltips  
带动画效果的Tips显示  
项目地址：https://github.com/nhaarman/supertooltips  
Demo地址：https://play.google.com/store/apps/details?id=com.haarman.supertooltips  

1. Android ViewBadger  
为其他View添加角标等  
项目地址：https://github.com/jgilfelt/android-viewbadger  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/android-viewbadger.apk?raw=true  
效果图：![Renderings](https://github-camo.global.ssl.fastly.net/a705a3e88c75ae2394943bd7c56f725697616ea8/687474703a2f2f7777772e6a65666667696c66656c742e636f6d2f766965776261646765722f76622d31612e706e67)  

1. SuperToasts  
更丰富样式的toast，支持Button、Progress、Horizontal Progress样式、支持进入动画、支持撤销及其动画设置  
项目地址：https://github.com/JohnPersano/SuperToasts  
Demo地址：https://play.google.com/store/apps/details?id=com.supertoastsdemo  
效果图：![SuperButtonToast](http://i1331.photobucket.com/albums/w597/JohnPersano/supertoasts_githubimage_zps8a5ceb7c.png)  

1. UndoBar  
屏幕底部显示取消或是确认的PopupWindows  
项目地址：https://github.com/soarcn/UndoBar  
效果图：![Renderings](https://github.com/soarcn/UndoBar/blob/master/art/redo.png?raw=true)  

1. UndoBar  
屏幕底部显示取消或是确认某操作  
项目地址：https://github.com/jenzz/Android-UndoBar  
效果图：![Renderings](https://raw.github.com/jenzz/Android-UndoBar/master/assets/Screenshot2.png)  

1. Android-ActionItemBadge  
可以在ActionBar的MenuItem上显示一个小角标  
项目地址：https://github.com/mikepenz/Android-ActionItemBadge  
效果图：![Renderings](https://raw.githubusercontent.com/mikepenz/Android-ActionItemBadge/master/DEV/screenshot/screenshot1_small.png)  

1. SnackBar  
Material Design 风格的 Toast，类似 Google inbox 中的提示  
项目地址：https://github.com/MrEngineer13/SnackBar  
Demo地址：https://play.google.com/store/apps/details?id=com.mrengineer13.snackbar.sample  
效果图：![Renderings](https://camo.githubusercontent.com/67a39af16f3d46631567c1f7bd7dcddeb3c4c9e9/687474703a2f2f6d6174657269616c2d64657369676e2e73746f726167652e676f6f676c65617069732e636f6d2f696d616765732f636f6d706f6e656e74732d746f617374732d73706563732d737065635f746f6173745f30335f315f6c617267655f6d6470692e706e67)  

1. HeadsUp  
在2.3上使用 android  5.0的 HeadsUp 效果  
项目地址：https://github.com/zzz40500/HeadsUp  
效果图：![heads-up.gif](http://upload-images.jianshu.io/upload_images/166866-543a5d26ab71d0f6.gif)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>   

#### 十二、FlipView  
1. android-flip  
类似Flipboard翻转动画的实现  
项目地址：https://github.com/openaphid/android-flip  
Demo地址：https://github.com/openaphid/android-flip/blob/master/FlipView/Demo/APK/Aphid-FlipView-Demo.apk?raw=true  
APP示例：flipboard  

1. FlipImageView  
支持x、y、z及动画选择的翻转动画的实现  
项目地址：https://github.com/castorflex/FlipImageView  
Demo地址：https://play.google.com/store/apps/details?id=fr.castorflex.android.flipimageview  

1. FoldableLayout  
Flip翻转效果的ListView，目前还不支持ListView缓存  
项目地址：https://github.com/alexvasilkov/FoldableLayout  
Demo地址：http://play.google.com/store/apps/details?id=com.alexvasilkov.foldablelayout.sample  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 十三、ColorPickView  
1. ColorPickerView  
颜色选择器，支持PopupWindows或新的Activity中打开  
项目地址：https://code.google.com/p/color-picker-view/  
效果图：![Renderings](http://oi41.tinypic.com/33c6mm8.jpg)  

1. HoloColorPicker  
颜色选择器  
项目地址：https://github.com/LarsWerkman/HoloColorPicker  
Demo地址：https://docs.google.com/file/d/0BwclyDTlLrdXRzVnTGJvTlRfU2s/edit  

1. ColorPickerPreference  
颜色选择器  
项目地址：https://github.com/attenzione/android-ColorPickerPreference  
效果图：![Renderings](https://github.com/attenzione/android-ColorPickerPreference/raw/master/screen_2.png)  

1. ColorPicker  
颜色选择器（Google Agenda中的样式风格）  
项目地址：https://github.com/flavienlaurent/colorpicker  
Demo地址：https://raw.github.com/biboune/colorpicker/master/colorpicker-sample.apk  
效果图：![Renderings](https://camo.githubusercontent.com/a42581e637ca379004855d69e262d85ea966fa35/68747470733a2f2f7261772e6769746875622e636f6d2f6269626f756e652f636f6c6f727069636b65722f6d61737465722f67726170686963732f696d67312e706e67)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 十四、GraphView  
1. MPAndroidChart  
强大的图表绘制工具，支持折线图、面积图、散点图、时间图、柱状图、条图、饼图、气泡图、圆环图、范围（高至低）条形图、网状图及各种图的结合；支持图的拖拽缩放；支持 Android 2.2 以上，支持横纵轴缩放，多指缩放，展现动画、高亮、保存到 sdcard、从文件读取图表  
项目地址：https://github.com/PhilJay/MPAndroidChart  
Demo地址：https://play.google.com/store/apps/details?id=com.xxmassdeveloper.mpchartexample  
Demo项目：https://github.com/PhilJay/MPAndroidChart/tree/master/MPChartExample  
效果图：<img height="300px" src="https://camo.githubusercontent.com/a9eaa5fc7fb6c1e70b22acd09385055e0f5c4fe7/68747470733a2f2f7261772e6769746875622e636f6d2f5068696c4a61792f4d5043686172742f6d61737465722f73637265656e73686f74732f73696d706c6564657369676e5f6c696e656368617274342e706e67" /><br/><img height="300px" src="https://camo.githubusercontent.com/78b4bc4e50e151970961daf56e81c4c0db72d27c/68747470733a2f2f7261772e6769746875622e636f6d2f5068696c4a61792f4d5043686172742f6d61737465722f73637265656e73686f74732f73696d706c6564657369676e5f6261726368617274332e706e67" /><br/><img  src="https://camo.githubusercontent.com/65f51783ec05038730b481ed614b57a94e867d86/68747470733a2f2f7261772e6769746875622e636f6d2f5068696c4a61792f4d5043686172742f6d61737465722f73637265656e73686f74732f626172636861727432642e706e67" /><br/><img src="https://camo.githubusercontent.com/f66a35bf430b12480d3e2ed8e3bc8d7a17db950f/68747470733a2f2f7261772e6769746875622e636f6d2f5068696c4a61792f4d5043686172742f6d61737465722f73637265656e73686f74732f626172636861727433642e706e67" /><br/><img height="300px" src="https://camo.githubusercontent.com/60bd0d71462ad577df775b956944b191e939728a/68747470733a2f2f7261772e6769746875622e636f6d2f5068696c4a61792f4d50416e64726f696443686172742f6d61737465722f73637265656e73686f74732f70696563686172745f686f6c657261646975735f73706163652e706e67" /><br/><img height="300px" src="https://camo.githubusercontent.com/6b254aa699df7f9464967009129c3017de721b77/68747470733a2f2f7261772e6769746875622e636f6d2f5068696c4a61792f4d50416e64726f696443686172742f6d61737465722f73637265656e73686f74732f7363617474657263686172742e706e67" />  
在线演示：https://www.youtube.com/watch?v=ufaK_Hd6BpI  

1. achartengine  
强大的图表绘制工具，支持折线图、面积图、散点图、时间图、柱状图、条图、饼图、气泡图、圆环图、范围（高至低）条形图、拨号图/表、立方线图及各种图的结合  
项目地址：https://code.google.com/p/achartengine/  
效果图：![Renderings](http://www.achartengine.org/dimages/average_temperature.png)  
http://www.achartengine.org/dimages/sales_line_and_area_chart.png  
http://www.achartengine.org/dimages/temperature_range_chart.png  
http://www.achartengine.org/dimages/combined_chart.png  
http://www.achartengine.org/dimages/budget_chart.png  
官网网址：http://www.achartengine.org/  
APP示例：Wordpress Android，Google Analytics  

1. GraphView  
绘制图表和曲线图的View，可用于Android上的曲形图、柱状图、波浪图展示  
项目地址：https://github.com/jjoe64/GraphView  
Demo项目：https://github.com/jjoe64/GraphView-Demos  
APP示例：Wordpress Android，Google Analytics  

1. HoloGraphLibrary  
绘制现状图、柱状图、饼状图  
项目地址：https://bitbucket.org/danielnadeau/holographlibrary/src  
文档介绍：https://bitbucket.org/danielnadeau/holographlibrary/wiki/Home  

1. XCL-Charts  
XCL-Charts基于原生的Canvas来绘制各种图表,在设计时，尽量在保证开发效率的同时，给使用者提供足够多的定制化能力。因此使用简便,同时具有相当灵活的定制能力。目前支持3D/非3D柱形图(Bar Chart)、3D/非3D饼图(Pie Chart)、堆积图(Stacked Bar Chart)、面积图(Area Chart)、 折线图(Line Chart)、曲线图(Spline Chart)、环形图(Dount Chart)、南丁格尔玫瑰图(Rose Chart)、仪表盘(Dial Chart)、刻度盘(Gauge Chart)、雷达图(Radar Chart)、圆形图(Circle Chart)等图表。其它特性还包括支持图表缩放、手势移动、动画显示效果、高密度柱形显示、图表分界定制线、多图表的混合显示及同数据源不同类型图表切换等。  
项目地址：https://github.com/xcltapestry/XCL-Charts  
Demo地址：https://github.com/xcltapestry/XCL-Charts/blob/master/XCL-Charts-demo/bin/XCL-Charts-demo.apk?raw=true  

1. EazeGraph  
Android 图表库，支持柱状图、分层柱状图、饼状图、线性图  
项目地址：https://github.com/blackfizz/EazeGraph  
Demo地址：https://play.google.com/store/apps/details?id=org.eazegraph.app  

1. WilliamChart  
绘制图表的库，支持LineChartView、BarChartView和StackBarChartView三中图表类型，并且支持 Android 2.2及以上的系统。  
项目地址：https://github.com/diogobernardino/WilliamChart  
Demo地址：https://play.google.com/store/apps/details?id=com.db.williamchartdemo  
Demo项目：https://github.com/diogobernardino/WilliamChart/tree/master/sample  
效果图：![Renderings](https://github.com/diogobernardino/WilliamChart/raw/master/art/linechart.gif)![Renderings](https://github.com/diogobernardino/WilliamChart/raw/master/art/barchart.gif)![Renderings](https://github.com/diogobernardino/WilliamChart/raw/master/art/stackbarchart.gif)  

1. HelloCharts for Android  
支持折线图、柱状图、饼图、气泡图、组合图；支持预览、放大缩小，滚动，部分图表支持动画；支持 Android 2.2 以上  
项目地址：https://github.com/lecho/hellocharts-android  
Demo地址：https://play.google.com/store/apps/details?id=lecho.lib.hellocharts.samples  
在线演示：https://www.youtube.com/watch?v=xbSBjyjH2SY  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 十五、UI Style  
不同样式的系统UI风格，如IOS、Bootstrap风格

1. UITableView  
ios风格控件，包括Button、ListView、TableView  
项目地址：https://github.com/thiagolocatelli/android-uitableview  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/ui-tableview-demo.apk?raw=true  

1. ATableView  
ios风格控件  
项目地址：https://github.com/dmacosta/ATableView  
Demo地址：https://play.google.com/store/apps/details?id=com.nakardo.atableview.demo  

1. Cards-UI  
卡片式View，支持单个卡片，item为卡片的ListView  
项目地址：https://github.com/afollestad/Cards-UI  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/cards-ui-demo.apk?raw=true  

1. cardslib  
卡片式View，支持单个卡片，item为卡片的ListView和GridView  
项目地址：https://github.com/gabrielemariotti/cardslib  
Demo地址：https://play.google.com/store/apps/details?id=it.gmariotti.cardslib.demo  

1. Android-Bootstrap  
Bootstrap 风格的按钮  
项目地址：https://github.com/Bearded-Hen/Android-Bootstrap  
效果图：![Renderings](https://raw.github.com/Bearded-Hen/Android-Bootstrap/master/images/device_image.png)  

1. Material Design Android Library  
Android L 中 Material Design 风格的组件适配到 Android 2.2+  
项目地址：https://github.com/navasmdc/MaterialDesignLibrary  

1. Android FlatUI  
Android 扁平化风格的组件，支持一些自定义样式  
项目地址：https://github.com/eluleci/FlatUI  
效果图：![Renderings](https://camo.githubusercontent.com/590d4a2ac322417b71f83223bd58b83903d58343/68747470733a2f2f7261772e6769746875622e636f6d2f656c756c6563692f466c617455492f6d61737465722f73616d706c652d696d616765732f73686f77636173652e706e67)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 十六、其他  
1. SwipeBackLayout  
左右或向上滑动返回的Activity  
项目地址：https://github.com/Issacw0ng/SwipeBackLayout  
Demo地址：https://play.google.com/store/apps/details?id=me.imid.swipebacklayout.demo  
APP示例：知乎  

1. android-styled-dialogs  
可自定义样式的dialog，默认与Holo主题样式一致，在Android2.2以上同一样式  
项目地址：https://github.com/inmite/android-styled-dialogs  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/styled-dialogs-demo.apk?raw=true  

1. Android Sliding Up Panel  
可拖动的View，能在当前Activity上扶起一个可拖动的Panel  
项目地址：https://github.com/umano/AndroidSlidingUpPanel  
Demo地址：https://play.google.com/store/apps/details?id=com.sothree.umano  
APP示例：Google Music精简播放栏  

1. AndroidWheel  
Android Wheel支持城市、多种日期时间、密码、图片  
项目地址：https://code.google.com/p/android-wheel/  
效果图：![Renderings](http://farm6.staticflickr.com/5532/11621528786_220c040ba5_o.jpg)  

1. TableFixHeaders  
第一列固定的Table  
项目地址：https://github.com/InQBarna/TableFixHeaders  
Demo地址：http://bit.ly/13buAIq  

1. Inscription  
可用于展示应用change和new feature信息  
项目地址：https://github.com/MartinvanZ/Inscription  

1. ActivityTransition  
Activity切换动画，包括渐变、flip、某个位置进入等等  
项目地址：https://github.com/ophilbert/ActivityTransition  
效果图：类似桌面左右切换的各种效果，不过桌面并非用ViewPager实现而已  
文档介绍：https://github.com/jfeinstein10/JazzyViewPager/blob/master/JazzyViewPager.apk?raw=true  

1. EasyAndroidAnimations  
针对View的各种动画  
项目地址：https://github.com/2359media/EasyAndroidAnimations  

1. GlowPadBackport  
将Android4.2的锁屏界面解锁扩展到Android1.6及1.6+  
项目地址：https://github.com/rock3r/GlowPadBackport  
Demo地址：https://play.google.com/store/apps/details?id=net.sebastianopoggi.samples.ui.GlowPadSample  
效果图：![Renderings](https://lh6.ggpht.com/U070b6Lh6cVsVwx4jN-5nq0xqiB1PBzrYABPeJIEe2hZQ5UWOxc-FDUG77wADelToHA=h310-rw)  

1. GlowPadView  
Android4锁屏界面解锁  
项目地址：https://github.com/nadavfima/GlowPadView  
效果图：https://raw.github.com/nadavfima/GlowPadView/master/example.png  

1. android-lockpattern  
Android的图案密码解锁  
项目地址：https://code.google.com/p/android-lockpattern/  
Demo地址：https://play.google.com/store/apps/details?id=group.pals.android.lib.ui.lockpattern.demo  
文档介绍：https://code.google.com/p/android-lockpattern/wiki/QuickUse  
APP示例：Android开机的图案密码解锁，支付宝的密码解锁  

1. PatternLock  
另一个 Android 图案解锁库  
项目地址：https://github.com/DreaminginCodeZH/PatternLock  
Demo 地址：https://github.com/DreaminginCodeZH/PatternLock/raw/master/dist/sample.apk  
效果图：![Renderings](https://github.com/DreaminginCodeZH/PatternLock/raw/master/image/sample_small.png)  
APP示例：Android开机的图案密码解锁，支付宝的密码解锁  

1. RangeBar  
类似于SeekBar，不同的是可以选择一个范围内的值而不是单个值  
项目地址：https://github.com/edmodo/range-bar  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/range-bar-demo.apk?raw=true  
效果图：![Renderings](http://i.imgur.com/q85GhRjl.png)  

1. ChromeView  
利用Chromium实现的WebView，解决各个Android版本WebView不同的问题，同时利用最新Chrome代码  
项目地址：https://github.com/pwnall/chromeview  

1. android-phased-seek-bar  
支持预先定义状态的SeekBar  
项目地址：https://github.com/ademar111190/android-phased-seek-bar  
效果图：![Renderings](https://raw.githubusercontent.com/ademar111190/android-phased-seek-bar/master/images/sample.gif)  

1. Android Slider Preference Library  
可添加到设置中的基于对话框的RankBar小部件  
项目地址：https://github.com/jayschwa/AndroidSliderPreference  

1. ShowcaseView library  
用于高亮显示应用程序的特定部分，从而突出突出重点  
项目地址：https://github.com/amlcurran/ShowcaseView  

1. android-segmented-control  
Android上的Segmented Controls，相当于RadioButton组  
项目地址：https://github.com/hoang8f/android-segmented-control  

1. Swipeable Cards  
类似Tinder的卡片效果，可以加载图片并动画效果展示，向左滑动表示喜欢，向右表示不喜欢  
项目地址：https://github.com/kikoso/Swipeable-Cards  
Demo地址：https://play.google.com/store/apps/details?id=info.hoang8f.fbutton.demo  

1. EdgeEffectOverride  
改变ScrollView, ListView, ExpandableListView, GridView, ViewPager等滚动控件滚动到边缘的颜色效果  
项目地址：https://github.com/AndroidAlliance/EdgeEffectOverride  

1. android-pinned-header-listviews  
使ExpandListView的Group滑动到顶端时会固定不动直到另外一个Group到达顶端  
项目地址：https://github.com/rtyley/android-pinned-header-listviews  

1. AndroidSwipeLayout  
滑动Layout，支持单个View，ListView，GridView  
项目地址：https://github.com/daimajia/AndroidSwipeLayout  
Demo地址：[Download Demo](https://github.com/daimajia/AndroidSwipeLayout/releases/download/v1.0.0/AndroidSwipeLayout-Demo-1.0.1-snapshot.apk)  
效果图：![](http://ww2.sinaimg.cn/mw690/610dc034jw1ejoplapwtqg208n0e74dx.gif)  

1. DynamicCardLayout  
在Android中实现的类似Windows8的瓷片布局  
项目地址：https://github.com/dodola/DynamicCardLayout  
效果图：![Renderings](https://github.com/dodola/DynamicCardLayout/blob/master/pic1.png?raw=true)  

1. Emoticons-Keyboard  
带表情情符号的自定义键盘  
项目地址：https://github.com/chiragjain/Emoticons-Keyboard  
效果图：![Renderings](https://github.com/chiragjain/Emoticons-Keyboard/raw/master/s2.png)  

1. Android Typeface Helper  
可以帮你轻松实现自定义字体的库  
项目地址：https://github.com/norbsoft/android-typeface-helper  
效果图：![Renderings](https://camo.githubusercontent.com/b8e7d4f4ab84ff96a3919ea264e2a83aca46e04e/68747470733a2f2f7261772e6769746875622e636f6d2f6e6f7262736f66742f616e64726f69642d74797065666163652d68656c7065722f6d61737465722f726561646d655f73637265656e2e706e67)  

1. Android-Anim-Playground  
几个动画效果，其中第二个基于android-svg的绘制效果非常好  
项目地址：https://github.com/Tibolte/Android-Anim-Playground  
效果图：![Renderings](https://raw.githubusercontent.com/Tibolte/Android-Anim-Playground/master/androiddemosvg.gif)  

1. NiftyDialogEffects  
支持自定义飞入动画样式的 Dialog  
项目地址：https://github.com/sd6352051/NiftyDialogEffects  
效果图：![Renderings](https://camo.githubusercontent.com/456687ac516bb07f1076928d635bfddf6b90d5ec/687474703a2f2f696d67302e70682e3132362e6e65742f69433436653162586b55316631724966555a6f3939773d3d2f363539373632303632313938343031393430382e676966)  
在线演示：http://tympanus.net/Development/ModalWindowEffects/  

1. PostOffice  
创建 Holo 及 Material Design 样式的 Dialog  
项目地址：https://github.com/r0adkll/PostOffice  
效果图：![Renderings](https://github.com/r0adkll/PostOffice/raw/master/images/po_2.png)  

1. Swipecards  
类似Tinder的卡片效果，可以加载图片并动画效果展示，向左滑动表示喜欢，向右表示不喜欢，根据 Kikoso's Swipeable-Cards 改造而来  
项目地址：https://github.com/Diolor/Swipecards  

1. SeekArc  
圆形的 SeekBar  
项目地址：https://github.com/TriggerTrap/SeekArc  
效果图：![Renderings](https://camo.githubusercontent.com/6a5091cb39a50d4c49b8d2f08684cb260db55aa7/68747470733a2f2f7261772e6769746875622e636f6d2f6e65696c643030312f5365656b4172632f6d61737465722f7261772f6172635f7377656570732e706e67)  

1. BlurDialogFragment  
显示  DialogFragment 时背景模糊效果  
项目地址：https://github.com/tvbarthel/BlurDialogFragment  
Demo地址：https://play.google.com/store/apps/details?id=fr.tvbarthel.lib.blurdialogfragment.sample  

1. range-seek-bar  
随机值选取的 SeekBar  
项目地址：https://github.com/yahoo/android-range-seek-bar  
效果图：![Renderings](https://github.com/yahoo/android-range-seek-bar/raw/master/demo_screenshot.png)  

1. MaterialRangeBar  
可以选择一个范围内的值而不是单个值的 SeekBar，RangeBar 的 Material Design 风格适配  
项目地址：https://github.com/oli107/material-range-bar  
效果图：![Renderings](https://github.com/oli107/material-range-bar/raw/master/Screenshots/pin%20expand.gif)  

1. MaterialList  
Material Design 风格的 CardView  
项目地址：https://github.com/dexafree/MaterialList  
Demo地址：https://play.google.com/store/apps/details?id=com.dexafree.materiallistviewexample  
效果图：![Renderings](https://camo.githubusercontent.com/b71bb064807465b7c9132d7f6072e2064f01fb85/687474703a2f2f692e696d6775722e636f6d2f454e78554741772e706e67)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a> 

1. road-trip  
设置path的各种动画效果，以及如何实现复杂路径动画，类似于ios中的指纹注册界面的指纹动画效果  
项目地址：https://github.com/romainguy/road-trip  
效果图：![Renderings](https://github.com/zhangxin1989/RoadTrip/raw/master/screenshot/Road-Trip-200.gif)  

1. dialogplus  
一个简单的Android对话框，支持不同的弹出模式  
项目地址：https://github.com/orhanobut/dialogplus  
效果图：![Renderings](https://github.com/orhanobut/dialogplus/blob/master/images/d1.png)  

1. FlowLayout  
一个简单的流式布局，用法类似 LinearLayout，但是能够让子元素根据宽度自动换行  
项目地址：[FLowLayout](https://github.com/LyndonChin/AndroidFlowLayout)  
效果图：  
![Renderings](http://img02.taobaocdn.com/imgextra/i2/160310864/TB2MH8.bVXXXXa3XXXXXXXXXXXX_!!160310864.png)

## 第二部分 工具库  
主要包括那些不错的开发库，包括依赖注入框架、图片缓存、网络相关、数据库ORM建模、Android公共库、Android 高版本向低版本兼容、多媒体相关及其他。  <a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  
#### 一、依赖注入DI  
通过依赖注入减少View、服务、资源简化初始化，事件绑定等重复繁琐工作  

1. AndroidAnnotations(Code Diet)  
android快速开发框架  
项目地址：https://github.com/excilys/androidannotations  
文档介绍：https://github.com/excilys/androidannotations/wiki  
官网网址：http://androidannotations.org/  
特点：(1) 依赖注入：包括view，extras，系统服务，资源等等  
(2) 简单的线程模型，通过annotation表示方法运行在ui线程还是后台线程  
(3) 事件绑定：通过annotation表示view的响应事件，不用在写内部类  
(4) REST客户端：定义客户端接口，自动生成REST请求的实现  
(5) 没有你想象的复杂：AndroidAnnotations只是在在编译时生成相应子类  
(6) 不影响应用性能：仅50kb，在编译时完成，不会对运行时有性能影响。  
PS：与roboguice的比较：roboguice通过运行时读取annotations进行反射，所以可能影响应用性能，而AndroidAnnotations在编译时生成子类，所以对性能没有影响  

1. roboguice  
帮你处理了很多代码异常，利用annotation使得更少的代码完成项目  
项目地址：https://github.com/roboguice/roboguice  
文档介绍：https://github.com/roboguice/roboguice/wiki  

1. butterknife  
利用annotation帮你快速完成View的初始化，减少代码  
项目地址：https://github.com/JakeWharton/butterknife  
文档介绍：http://jakewharton.github.io/butterknife/  

1. Dagger  
依赖注入，适用于Android和Java  
项目地址：https://github.com/square/dagger  
文档介绍：http://square.github.io/dagger/  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 二、图片缓存  
1. Android-Universal-Image-Loader  
图片缓存，目前使用最广泛的图片缓存，支持主流图片缓存的绝大多数特性。  
项目地址：https://github.com/nostra13/Android-Universal-Image-Loader  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/universal-imageloader-demo.apk?raw=true  
文档介绍：http://www.intexsoft.com/blog/item/74-universal-image-loader-part-3.html  

1. picasso  
square开源的图片缓存  
项目地址：https://github.com/square/picasso  
文档介绍：http://square.github.io/picasso/  
特点：(1)可以自动检测adapter的重用并取消之前的下载  
(2)图片变换  
(3)可以加载本地资源  
(4)可以设置占位资源  
(5)支持debug模式  

1. ImageCache  
图片缓存，包含内存和Sdcard缓存  
项目地址：https://github.com/Trinea/AndroidCommon  
Demo地址：https://play.google.com/store/apps/details?id=cn.trinea.android.demo  
文档介绍：http://www.trinea.cn/android/android-imagecache/  
特点：(1)支持预取新图片，支持等待队列  
(2)包含二级缓存，可自定义文件名保存规则  
(3)可选择多种缓存算法(FIFO、LIFO、LRU、MRU、LFU、MFU等13种)或自定义缓存算法  
(4)可方便的保存及初始化恢复数据  
(5)支持不同类型网络处理  
(6)可根据系统配置初始化缓存等  

1. Cube ImageLoader  
阿里巴巴一淘使用的图片加载，综合了Android-Universal-Image-Loader 和 square 等组件优点，简单易用，良好的中文文档支持  
项目地址：https://github.com/etao-open-source/cube-sdk  
Demo地址：https://github.com/liaohuqiu/cube-sdk/raw/master/cube-sdk-sample.apk  
效果图：![Screen Shot](https://raw.githubusercontent.com/etao-open-source/cube-sdk/dev/screen-shot.png)
文档介绍：http://cube-sdk.liaohuqiu.net/    

1. fresco  
一款强大的图片缓存工具，由 Facebook开发  
项目地址：https://github.com/facebook/fresco  
文档介绍：http://frescolib.org/  
特点：(1) 两个内存缓存加上磁盘缓存构成了三级缓存  
(2) 支持流式，可以类似网页上模糊渐进式显示图片  
(3) 对多帧动画图片支持更好，如 Gif、WebP  
(4) 更多样的显示，如圆角、进度条、点击重试、自定义对焦点  
(5) 更多样的加载，如支持 EXIF、全面支持 WebP  
(6) 支持 Android 2.3+  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>

#### 三、网络相关  
1. Asynchronous Http Client for Android  
Android异步Http请求  
项目地址：https://github.com/loopj/android-async-http  
文档介绍：http://loopj.com/android-async-http/  
特点：(1) 在匿名回调中处理请求结果  
(2) 在UI线程外进行http请求  
(3) 文件断点上传  
(4) 智能重试  
(5) 默认gzip压缩  
(6) 支持解析成Json格式  
(7) 可将Cookies持久化到SharedPreferences  

1. android-query  
异步加载，更少代码完成Android加载  
项目地址：https://github.com/androidquery/androidquery 或 https://code.google.com/p/android-query/  
Demo地址：https://play.google.com/store/apps/details?id=com.androidquery  
文档介绍：https://code.google.com/p/android-query/#Why_AQuery?  
特点：https://code.google.com/p/android-query/#Why_AQuery?  

1. Async Http Client  
Java异步Http请求  
项目地址：https://github.com/AsyncHttpClient/async-http-client  
文档介绍：http://sonatype.github.io/async-http-client/  

1. Ion  
支持图片、json、http post等异步请求  
项目地址：https://github.com/koush/ion  
文档介绍：https://github.com/koush/ion#more-examples  

1. HttpCache  
Http缓存  
项目地址：https://github.com/Trinea/AndroidCommon  
Demo地址：https://play.google.com/store/apps/details?id=cn.trinea.android.demo  
文档介绍：http://www.trinea.cn/android/android-http-cache  
特点是：(1) 根据cache-control、expires缓存http请求  
(2) 支持同步、异步Http请求  
(3) 在匿名回调中处理请求结果  
(4) 在UI线程外进行http请求  
(5) 默认gzip压缩  

1. Http Request  
项目地址：https://github.com/kevinsawicki/http-request  
文档介绍：https://github.com/kevinsawicki/http-request#examples  

1. okhttp  
square开源的http工具类  
项目地址：https://github.com/square/okhttp  
文档介绍：http://square.github.io/okhttp/  
特点：(1) 支持SPDY( http://zh.wikipedia.org/wiki/SPDY )协议。SPDY协议是Google开发的基于传输控制协议的应用层协议，通过压缩，多路复用(一个TCP链接传送网页和图片等资源)和优先级来缩短加载时间。  
(2) 如果SPDY不可用，利用连接池减少请求延迟  
(3) Gzip压缩  
(4) Response缓存减少不必要的请求  

1. Retrofit  
RESTFUL API设计  
项目地址：https://github.com/square/retrofit  
文档介绍：http://square.github.io/retrofit/  

1. RoboSpice  
Android异步网络请求工具，支持缓存、REST等等  
项目地址：https://github.com/stephanenicolas/robospice  
Demo地址：https://github.com/stephanenicolas/RoboDemo/downloads  

1. Droppy  
支持多种样式的下拉菜单  
项目地址：https://github.com/shehabic/Droppy  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 四、数据库 orm工具包  
orm的db工具类，简化建表、查询、更新、插入、事务、索引的操作  

1. greenDAO  
Android Sqlite orm的db工具类  
项目地址：https://github.com/greenrobot/greenDAO  
文档介绍：http://greendao-orm.com/documentation/  
官网网址：http://greendao-orm.com/  
特点：(1) 性能佳  
(2) 简单易用的API  
(3) 内存小好小  
(4) 库大小小  

1. ActiveAndroid  
Android Sqlite orm的db工具类  
项目地址：https://github.com/pardom/ActiveAndroid  
文档介绍：https://github.com/pardom/ActiveAndroid/wiki/_pages  

1. Sprinkles  
Android Sqlite orm的db工具类，比较显著的特点就是配合 https://github.com/square/retrofit 能保存从服务器获取的数据  
项目地址：https://github.com/emilsjolander/sprinkles  
文档介绍：http://emilsjolander.github.io/blog/2013/12/18/android-with-sprinkles/  

1. Realm  
移动端的数据库，适用于 Phone、Tablet、Wearable，支持 ORM，线程安全、支持连表及数据库加密，比 SQLite 性能更好  
项目地址：https://github.com/realm/realm-java  
文档介绍：http://realm.io/docs/java/0.72.0/  

1. ormlite-android  
项目地址：https://github.com/j256/ormlite-android  
文档介绍：http://ormlite.com/sqlite_java_android_orm.shtml  

1. Schematic  
根据SQLite生成ContentProvider  
项目地址：https://github.com/SimonVT/schematic  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

1. DBFlow  
Android SQLite ORM工具库。综合了 Active Android, Schematic, Ollie,Sprinkles等库的优点；通过注解实现，性能好；能生成ContentProvider。  
项目地址：https://github.com/Raizlabs/DBFlow    
文档介绍：https://github.com/Raizlabs/DBFlow#usage-docs    

#### 五、Android公共库  
1. Guava  
Google的基于java1.6的类库集合的扩展项目，包括collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O等等. 这些高质量的API可以使你的JAVa代码更加优雅，更加简洁  
项目地址：https://code.google.com/p/guava-libraries/  
文档介绍：https://code.google.com/p/guava-libraries/wiki/GuavaExplained  

1. Volley  
Google提供的网络通信库，使得网络请求更简单、更快速  
项目地址：https://android.googlesource.com/platform/frameworks/volley  
文档介绍：http://commondatastorage.googleapis.com/io-2013/presentations/110%20-%20Volley-%20Easy,%20Fast%20Networking%20for%20Android.pdf  

1. AndroidCommon  
Android公共库  
项目地址：https://github.com/Trinea/AndroidCommon  
Demo地址：https://play.google.com/store/apps/details?id=cn.trinea.android.demo  
文档介绍：http://www.trinea.cn/android/android-common-lib/  
包括：(1)缓存(图片缓存、预取缓存、网络缓存)  
(2) 公共View(下拉及底部加载更多ListView、底部加载更多ScrollView、滑动一页Gallery)  
(3) Android常用工具类(网络、下载、Android资源操作、shell、文件、Json、随机数、Collection等等)  

1. shipfaster  
整合了Dagger Otto Retrofit Robolectric Picasso OkHttp，方便快速开发  
项目地址：https://github.com/pyricau/shipfaster  

1. CleanAndroidCode  
整合了Dagger Otto AndroidAnnotations，方便快速开发  
项目地址：https://github.com/pyricau/CleanAndroidCode  

1. xUtils  
基于Afinal，包含DbUtils、ViewUtils、HttpUtils、BitmapUtils四大模块，可用于快速开发  
项目地址：https://github.com/wyouflf/xUtils  

1. Afinal  
Afinal是一个android的ioc，orm框架，内置了四大模块功能：FinalAcitivity,FinalBitmap,FinalDb,FinalHttp。通过finalActivity，我们可以通过注解的方式进行绑定ui和事件。通过finalBitmap，我们可以方便的加载bitmap图片，而无需考虑oom等问题。通过finalDB模块，我们一行代码就可以对android的sqlite数据库进行增删改查。通过FinalHttp模块，我们可以以ajax形式请求http数据  
项目地址：https://github.com/yangfuhai/afinal  
官网网址：http://www.afinal.org  

1. UltimateAndroid  
UltimateAndroid是一个快速开发Android应用的框架，框架目前主要包含的功能有View Injection,ORM,异步网络请求和图片加载，自动化脚本测试,磁盘LRU等功能.同时提供了类似于TripleDes、Webview快速设置、Md5处理、String处理,Https处理等常用工具类，还有超过100多种UI控件效果。  
项目地址：https://github.com/cymcsg/UltimateAndroid  
官网网址：http://blog.marshalchen.com/UltimateAndroid/  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a> 

1. SAF  
SAF(Simple Android Framework)是一个简单的android框架，它为开发Android app提供了基础性组件。  
项目地址：https://github.com/fengzhizi715/SAF  
官网网址：http://www.salesuite.cn/  
包括：(1)Event Bus(事件总线)  
(2) Rest Client(http的框架)  
(3) Image Cache(图片缓存)  
(4) Dependency Injection(依赖注入)  
(5) Sqlite ORM(sqlite的orm)  
(6) Router(Activity、Fragment的Router)  
(7) Utils(各种常用的工具类) 

1. Barber  
Custom View 神器。通过简单的注解帮助你大大减少 Custom View 中的代码量。由于和 ButterKnife 一样使用了 Annotation Proccessor ，所以对程序性能没有影响。  
项目地址：https://github.com/hzsweers/barber  

1. device-year-class  
A library that analyzes an Android device's specifications and calculates which year the device would be considered "high end”.(facebook开发的检测手机主流配置工具)  
项目地址：https://github.com/facebook/device-year-class

#### 六、Android 高版本向低版本兼容  
1. ActionBarSherlock  
为Android所有版本提供统一的ActionBar，解决4.0以下ActionBar的适配问题  
项目地址：https://github.com/JakeWharton/ActionBarSherlock  
Demo地址：https://play.google.com/store/apps/details?id=com.actionbarsherlock.sample.demos  
APP示例：太多了。。现在连google都在用  

1. Nine Old Androids  
将Android 3.0(Honeycomb)所有动画API(ObjectAnimator ValueAnimator等)兼容到Android1.0  
项目地址：https://github.com/JakeWharton/NineOldAndroids  
Demo地址：https://play.google.com/store/apps/details?id=com.jakewharton.nineoldandroids.sample  
文档介绍：http://nineoldandroids.com/  

1. HoloEverywhere  
将Android 3.0的Holo主题兼容到Android2.1++  
项目地址：https://github.com/Prototik/HoloEverywhere  
Demo地址：https://raw.github.com/Prototik/HoloEverywhere/repo/org/holoeverywhere/demo/2.1.0/demo-2.1.0.apk  
文档介绍：http://android-developers.blogspot.com/2012/01/holo-everywhere.html  

1. SherlockNavigationDrawer  
将Android NavigationDrawer和ActionbarSherlock结合，解决4.0以下NavigationDrawer的适配问题  
项目地址：https://github.com/tobykurien/SherlockNavigationDrawer  
文档介绍：http://developer.android.com/training/implementing-navigation/nav-drawer.html  

1. Notifications4EveryWhere  
将Android 4.1的Notification兼容到Android2.2++  
项目地址：https://github.com/youxiachai/Notifications4EveryWhere  

1. Android Switch Widget Backport  
将Android Switch和SwitchPreference的兼容到Android2.1++  
项目地址：https://github.com/BoD/android-switch-backport  
Demo地址：https://play.google.com/store/apps/details?id=org.jraf.android.backport.switchwidget.sample  
文档介绍：https://github.com/BoD/android-switch-backport#using-the-switch  

1. android-datepicker  
将Android 4.0的datepicker兼容到Android2.2++  
项目地址：https://github.com/SimonVT/android-datepicker  

1. GlowPadBackport  
Android 4.2的GlowPadView向后适配到API4以上  
项目地址：https://github.com/frakbot/GlowPadBackport  

1. Transitions Everywhere  
Android 4.4 的 Transitions API 兼容到 Android 2.2 以上  
项目地址：https://github.com/andkulikov/transitions-everywhere  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 七、多媒体相关  
1. cocos2d-x  
跨平台的2d游戏框架，支持Android、IOS、Linux、Windows等众多平台  
项目地址：https://github.com/cocos2d/cocos2d-x  
文档介绍：http://www.cocos2d-x.org/wiki  
官网网址：http://www.cocos2d-x.org/  

1. Vitamio  
是一款Android与iOS平台上的全能多媒体开发框架  
项目地址：https://github.com/yixia/VitamioBundle  
网站介绍：http://www.vitamio.org/docs/  
特点：(1) 全面支持硬件解码与GPU渲染  
(2) 能够流畅播放720P甚至1080P高清MKV，FLV，MP4，MOV，TS，RMVB等常见格式的视频  
(3) 在Android与iOS上跨平台支持 MMS, RTSP, RTMP, HLS(m3u8)等常见的多种视频流媒体协议，包括点播与直播。  

1. PhotoProcessing  
利用ndk处理图片库，支持Instafix、Ansel、Testino、XPro、Retro、BW、Sepia、Cyano、Georgia、Sahara、HDR、Rotate(旋转)、Flip(翻转)等各种特效  
项目地址：https://github.com/lightbox/PhotoProcessing  
Demo地址：https://github.com/Trinea/TrineaDownload/blob/master/photo-processing.apk?raw=true  

1. Android StackBlur  
图片模糊效果工具类  
项目地址：https://github.com/kikoso/android-stackblur  
Demo地址：https://github.com/kikoso/android-stackblur/blob/master/StackBlurDemo/bin/StackBlurDemo.apk?raw=true  
文档介绍：https://github.com/kikoso/android-stackblur#usage  

1. Bitmap Smart Clipping using OpenCV  
图片智能裁剪保留重要部分显示  
项目地址：https://github.com/beartung/tclip-android  
利用淘宝的 http://code.taobao.org/p/tclip/ 库完成  
一淘玩客正在使用的图片裁剪，自动识别图片中的重要区域，并且在图片裁剪时保留重要区域  
特点：(1). 能进行人脸识别。图片中有人脸，将自动视为人脸区域为重要区域，将不会被裁剪掉  
(2).自动其它重要区域。如果图片中未识别出人脸，则会根据特征分布计算出重区域  

1. Cropper  
图片局部剪切工具，可触摸控制选择区域或旋转  
项目地址：https://github.com/edmodo/cropper  
效果图：![Renderings](https://github-camo.global.ssl.fastly.net/e4fde77bf41d4a60b234b4e268e5cfa8c17d9b6f/687474703a2f2f692e696d6775722e636f6d2f334668735467666c2e6a7067)  
文档介绍：https://github.com/edmodo/cropper/wiki  

1. android-crop  
图片裁剪Activity  
项目地址：https://github.com/jdamcd/android-crop  
效果图：![Renderings](https://github.com/jdamcd/android-crop/raw/master/screenshot.png)  

1. TileView  
可分块显示大图，支持2D拖动、双击、双指放大、双指捏合  
项目地址：https://github.com/moagrius/TileView  
Demo地址：http://moagrius.github.io/TileView/TileViewDemo.apk  

1. BlurEffectForAndroidDesign  
图片模糊效果  
项目地址：https://github.com/PomepuyN/BlurEffectForAndroidDesign  

1. android-eye  
PC端网页查看同一局域网内的手机摄像头内容，可以用来监控哦  
项目地址：https://github.com/Teaonly/android-eye  
Demo地址：https://play.google.com/store/apps/details?id=teaonly.droideye  

1. libpng for Android  
PNG图片的jni库，支持几乎png的所有特性  
项目地址：https://github.com/julienr/libpng-android  
文档介绍：http://www.libpng.org/pub/png/libpng.html  

1. android-gpuimage  
基于GPU的图片滤镜  
项目地址：https://github.com/CyberAgent/android-gpuimage  

1. AndroidFaceCropper  
图片脸部自动识别，将识别后的局部图片返回  
项目地址：https://github.com/lafosca/AndroidFaceCropper  

1. Android Video Crop  
利用TextureView播放和剪切视频，类似ImageView.setScaleType  
项目地址：https://github.com/dmytrodanylyk/android-video-crop  
Demo地址：https://github.com/lafosca/AndroidFaceCropper/releases/download/1.0/FaceCropper-sample-debug-unaligned.apk  

1. svg-android  
Android Svg矢量图形支持  
项目地址：https://github.com/japgolly/svg-android https://github.com/japgolly/svg-android  

1. Android Visualizer  
从Android MediaPlayer获得音频，然后像iTunes及WinAmp一样展示音轨  
项目地址：https://github.com/felixpalmer/android-visualizer  

1. ExoPlayer  
包括仪表板和SmoothStreaming自适应回放，缓存持久化和自定义渲染器，方便自定义和扩展，并且可以通过应用商店更新  
项目地址：https://github.com/google/ExoPlayer  

1. DanmakuFlameMaster  
android上开源弹幕解析绘制引擎项目  
项目地址：https://github.com/ctiao/DanmakuFlameMaster  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 八、事件总线(订阅者模式)  
通过发布/订阅事件解耦事件发送和接受，从而简化应用程序组件(Activities, Fragments及后台线程)之间的通信  

1. EventBus  
greenrobot的开源项目  
项目地址：https://github.com/greenrobot/EventBus  
文档介绍：https://github.com/greenrobot/EventBus#general-usage-and-api  
特点：(1) 支持在不同类型的线程中处理订阅，包括发布所在线程，UI线程、单一后台线程、异步线程  
(2) 支持事件优先级定义，支持优先级高的订阅者取消事件继续传递，支持粘性事件，是不是跟系统的有序广播、粘性广播很像啊  
(3) 不是基于annotations  
(4) 性能更优  
(5) 体积小  
(6) 支持单例创建或创建多个对象  
(7) 支持根据事件类型订阅  

1. Otto  
Square的开源项目，基于Guava的Android优化  
项目地址：https://github.com/square/otto  
文档介绍：http://square.github.io/otto/  
[EventBus与Otto的功能及性能对比文档](https://github.com/greenrobot/EventBus#comparison-with-squares-otto)  
[EventBus与Otto性能对比Demo Apk](https://play.google.com/store/apps/details?id=de.greenrobot.eventperf)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 九、传感器  
1. Great Android Sensing Toolkit  
Android感应器工具包，包含示例及使用过程中可能需要的算法  
项目地址：https://github.com/gast-lib/gast-lib  
Demo地址：https://play.google.com/store/apps/details?id=root.gast.playground  
文档介绍：https://github.com/gast-lib/gast-lib#documentation  

1. SensorManager  
Android传感器管理  
项目地址：https://github.com/nlathia/SensorManager  
文档介绍：https://docs.google.com/document/d/1TqThJULb-4e6TGb1gdkAaPCfyuXStjJpbnt7a0OZ9OE/edit  

1. GPSLogger  
记录GPS信息  
项目地址：https://github.com/mendhak/gpslogger  
Demo地址：https://play.google.com/store/apps/details?id=com.mendhak.gpslogger  
文档介绍：http://code.mendhak.com/gpslogger/  

1. Pedometer  
计步器，使用硬件计步感应器  
项目地址：https://github.com/j4velin/Pedometer  

1. leapcast  
ChromeCast模拟器的App  
项目地址：https://github.com/dz0ny/leapcast  

1. Arduino-Communicator  
与Arduino通信的App  
项目地址：https://github.com/jeppsson/Arduino-Communicator  

1. android-pedometer  
Android计步器  
项目地址：https://github.com/bagilevi/android-pedometer  
Demo地址：http://pedometer.googlecode.com/files/Pedometer-1.4.apk  

1. OwnTracks for Android  
自己的轨迹记录  
项目地址：https://github.com/owntracks/android  

1. Shake Detector library for Android  
Android手机震动摇晃检测库，提供供UI线程调用的回调接口  
项目地址：https://github.com/tbouron/ShakeDetector  
Demo地址：https://play.google.com/store/apps/details?id=com.github.tbouron.shakedetector.example  

1. Android heart rate monitor  
Android心跳检测  
项目地址：https://github.com/phishman3579/android-heart-rate-monitor  

1. Bluetooth LE Library for Android  
蓝牙源信息，包括宝库Mac、更新时间、RSSI、UUID、信号源距离、影响范围等信息  
项目地址：https://github.com/alt236/Bluetooth-LE-Library---Android  
Demo地址：https://play.google.com/store/apps/details?id=uk.co.alt236.btlescan  

1. farebot  
通过NFC 从公交卡中读取数据的一个应用  
项目地址：https://github.com/codebutler/farebot  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 十、安全  
1. SQLCipher  
Sqlite加密工具  
项目地址：https://github.com/sqlcipher/sqlcipher  
文档介绍：http://sqlcipher.net/sqlcipher-for-android/  

1. Conceal  
快速高效的进行文件加密解密  
项目地址：https://github.com/facebook/conceal  
文档介绍：https://github.com/facebook/conceal#usage  

1. Android-PasscodeLock  
应用锁，每次启动或从任何Activity启动应用都需要输入四位数字的密码方可进入  
项目地址：https://github.com/wordpress-mobile/Android-PasscodeLock  
Demo地址：https://play.google.com/store/apps/details?id=org.wordpress.android  
APP示例：Wordpress Android，支付宝，挖财  

1. GlowPadBackport  
将Android4.2的锁屏界面解锁扩展到Android1.6及1.6+  
项目地址：https://github.com/rock3r/GlowPadBackport  
Demo地址：https://play.google.com/store/apps/details?id=net.sebastianopoggi.samples.ui.GlowPadSample  
效果图：![Renderings](https://lh6.ggpht.com/U070b6Lh6cVsVwx4jN-5nq0xqiB1PBzrYABPeJIEe2hZQ5UWOxc-FDUG77wADelToHA=h310-rw)  

1. GlowPadView  
Android 4锁屏界面解锁  
项目地址：https://github.com/nadavfima/GlowPadView  
效果图：https://raw.github.com/nadavfima/GlowPadView/master/example.png  

1. android-lockpattern  
Android的图案密码解锁  
项目地址：https://code.google.com/p/android-lockpattern/  
Demo地址：https://play.google.com/store/apps/details?id=group.pals.android.lib.ui.lockpattern.demo  
文档介绍：https://code.google.com/p/android-lockpattern/wiki/QuickUse  

1. Android-InsecureBank  
关于 Android 不安全性的示例  
项目地址：https://github.com/dineshshetty/Android-InsecureBankv2  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 十一、插件化  
更多见：[Android 插件化作用、概念以及不错的资料(包括开源项目)和解决方案](http://www.trinea.cn/android/android-plugin/) 

1. dynamic-load-apk  
Android 动态加载Apk，热部署，利用 ClassLoader 以及 Activity 代理的方式解决  
项目地址：https://github.com/singwhatiwanna/dynamic-load-apk  
文档介绍：http://blog.csdn.net/singwhatiwanna/article/details/22597587  

1. Android Dynamic Loader  
点评的实现方式，和上面不同的是：他不是用代理 Activity 的方式实现而是用 Fragment 以及 Schema 的方式实现  
项目地址：https://github.com/mmin18/AndroidDynamicLoader  
Demo地址：https://github.com/mmin18/AndroidDynamicLoader/raw/master/host.apk  

1. xCombine  
Android App插件式插件开发，插件必须先安装，更推荐看上面两个开源项目  
项目地址：https://github.com/wyouflf/xCombine  
文档介绍：http://my.oschina.net/u/1171837/blog/155377  

1. Android Plugin Framework  
Android插件式开发，开放的源码目前不完整  
项目地址：https://github.com/umeng/apf  

1. multidex  
安装多 dex 的 classloader  
项目地址：https://github.com/casidiablo/multidex  

1. ANR-WatchDog  
Android ANR 监听，通过监听自己的 UI Thread 是否被执行确定是否发生了 ANR，并可以设置相关事件  
项目地址：https://github.com/SalomonBrys/ANR-WatchDog  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 十二、文件  
对不同文档类型的处理，包括PDF、Word、EPub、Html、Zip等

1. purePDF  
允许从任何运行的SWF文件读取和创建PDF文档  
项目地址：https://github.com/sephiroth74/purePDF  

1. android-pdfview  
快速解析pdf的view，默认支持手势缩放和相关动画  
项目地址：https://github.com/JoanZapata/android-pdfview  

1. Office 365 SDK for Android Preview  
可支持Microsoft SharePoint Lists, Microsoft SharePoint Files, Microsoft Exchange Calendar, Microsoft Exchange Contacts, Microsoft Exchange Mail  
项目地址：https://github.com/OfficeDev/Office-365-SDK-for-Android  

1. OpenSpritz-Android  
EPub阅读器  
项目地址：https://github.com/OnlyInAmerica/OpenSpritz-Android  

1. jsoup  
一个解析html的java库，可方便的提取和操作数据  
项目地址：https://github.com/jhy/jsoup  
官网网址：http://jsoup.org/  
作用：(1) 从一个url、文件或string获得html并解析  
(2) 利用dom遍历或css选择器查找、提取数据  
(3) 操作html元素  
(4) 根据白名单去除用于提交的非法数据防止xss攻击  
(5) 输出整齐的html  

1. ZIP  
java压缩和解压库  
项目地址：https://github.com/zeroturnaround/zt-zip  
文档介绍：https://github.com/zeroturnaround/zt-zip#examples  
作用：(1) 解压和压缩，并支持文件夹内递归操作  
(2) 支持包含和排除某些元素  
(3) 支持重命名元素  
(4) 支持遍历zip包内容  
(5) 比较两个zip包等功能  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 十三、其他  
1. Salvage view  
带View缓存的Viewpager PagerAdapter，很方便使用  
项目地址：https://github.com/JakeWharton/salvage  

1. Android Priority Job Queue  
Android后台任务队列  
项目地址：https://github.com/path/android-priority-jobqueue  
文档介绍：https://github.com/path/android-priority-jobqueue#getting-started  

1. Cobub Razor  
开源的mobile行为分析系统，包括web端、android端，支持ios和window phone  
项目地址：https://github.com/cobub/razor  
Demo地址：http://demo.cobub.com/razor  
官网网址：http://dev.cobub.com/  

1. Countly  
Android移动端数据采集分析系统  
项目地址：https://github.com/Countly/countly-sdk-android  
官网网址：https://count.ly/  

1. aFileChooser  
文件选择器，可内嵌到程序中，而无需使用系统或三方文件选择器。  
项目地址：https://github.com/iPaulPro/aFileChooser  

1. androidpn  
基于xmpp协议的消息推送解决方案，包括服务器端和android端。  
项目地址：https://github.com/dannytiehui/androidpn  

1. Bolts  
Android的异步编程模式  
项目地址：https://github.com/BoltsFramework/Bolts-Android/  
与AsyncTask比较：(1) 使用的是无大小限制的线程池  
(2) 任务可组合可级联，防止了代码耦合  

1. CastCompanionLibrary-android  
使Android程序中更快的接入Google Cast  
项目地址：https://github.com/googlecast/CastCompanionLibrary-android  
文档介绍：https://developers.google.com/cast/  

1. CastVideos-android  
从Android设备分享Video通过Google Cast  
项目地址：https://github.com/googlecast/CastVideos-android  
文档介绍：https://developers.google.com/cast/  

1. Uninstall_Statics  
Android应用自身被卸载监听及打开浏览器等反馈功能实现  
项目地址：https://github.com/sevenler/Uninstall_Statics  
文档介绍：http://www.cnblogs.com/zealotrouge/p/3157126.html  http://www.cnblogs.com/zealotrouge/p/3159772.html  

1. Memento  
保证在系统配置改变时，Activity中的某些数据可以简单安全的保持不变  
项目地址：https://github.com/mttkay/memento  
文档介绍：https://github.com/mttkay/memento#usage  

1. FreeFlow  
布局引擎，更简单的创建自定义布局，并且当数据和布局改变时更美观的过渡动画  
项目地址：https://github.com/Comcast/FreeFlow  
Demo地址：https://github.com/Comcast/FreeFlow/releases  

1. Android Gesture Detectors Framework  
Android手势框架，支持双指旋转、移动、平移、缩放等  
项目地址：https://github.com/Almeros/android-gesture-detectors  

1. Mapbox Android SDK  
Android Map的替代版  
项目地址：https://github.com/mapbox/mapbox-android-sdk  

1. Activity animation  
Activity跳转动画，支持各个方向波浪的效果  
项目地址：https://github.com/flavienlaurent/activityanimation  
在线演示：https://www.youtube.com/watch?v=-E0sc6w_Jck  

1. KryoNet  
通过NIO提供客户端和服务器端TCP/UDP网络传输的Java库  
项目地址：https://github.com/EsotericSoftware/kryonet  

1. Rebound  
一个模仿弹簧反弹的Java库，可用于创建动画  
项目地址：https://github.com/facebook/rebound  

1. Android Social Networks  
社交网络接入统一管理器，可方便的从Twitter, LinkedIn, Facebook, Google Plus登陆、获得个人信息、发送消息、发送专篇、添加或删除好友  
项目地址：https://github.com/antonkrasov/AndroidSocialNetworks  
Demo地址：https://play.google.com/store/apps/details?id=com.github.androidsocialnetworks.apidemos  

1. SmartAppUpdates  
Android App 增量升级，包含前后端方案、Demo、以及 so 库，可用于商店或大体积 App 差分升级  
项目地址：https://github.com/cundong/SmartAppUpdates  

1. Magnet  
创建类似 Facebook 聊天桌面悬浮窗的效果  
项目地址：https://github.com/premnirmal/Magnet  

1. Parceler  
通过注解及工具类自动完成实体类 Parcelable及值传递  
项目地址：https://github.com/johncarl81/parceler  

1. AcDisplay  
将 Android 的通知都集中到锁屏显示  
项目地址：https://github.com/AChep/AcDisplay  
Demo地址：https://play.google.com/store/apps/details?id=com.achep.acdisplay  

1. QrCodeScan  
ZXing和ZBar结合的二维码扫描项目，提高了扫描效率  
项目地址：https://github.com/SkillCollege/QrCodeScan  
效果图：![QrCodeScan](http://www.eoeandroid.com/data/attachment/forum/201405/09/124538vteuz4leptgg1te6.png)  

1. Android-ScreenShot  
实现android系统截屏功能  
项目地址：https://github.com/Android-ScreenShot/AndroidScreenShotService  
文档介绍：http://blog.csdn.net/buptgshengod/article/details/39155979  

1. card.io SDK for Android  
信用卡扫描 Android SDK  
项目地址：https://github.com/card-io/card.io-Android-SDK  
Demo项目：https://github.com/card-io/card.io-Android-SDK/tree/master/SampleApp  

1. ASNE  
Twitter, Facebook, Google Plus, LinkedIn, Instagram, Vkontakte, Odnoklassniki 的集成库，包括他们的大多数功能  
项目地址：https://github.com/gorbin/ASNE  
Demo地址：https://play.google.com/store/apps/details?id=com.gorbin.androidsocialnetworksextended.asne  

1. Android Signature Pad  
Android 自定义的签名 View，可自定义笔颜色和大小  
项目地址：https://github.com/gcacace/android-signaturepad  
Demo项目：https://github.com/gcacace/android-signaturepad/tree/master/SignaturePad-Example  

1. Teleport  
Android Wear 数据同步和消息传送库  
项目地址：https://github.com/Mariuxtheone/Teleport  

1. DebugLog  
可以帮你创建更简单和更容易理解的调试日志，能够友好的显示调试信息所在类和函数。  
项目地址：https://github.com/MustafaFerhan/DebugLog  
效果图：![DebugLog](https://camo.githubusercontent.com/37deffede9f9b185886da48e96a4829ebd407260/68747470733a2f2f7261772e6769746875622e636f6d2f4d75737461666146657268616e2f44656275674c6f672f6d61737465722f44656275674c6f672d44656d6f2f6173736574732f7373322e6a7067) 
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

1. Logger  
简单、美观而且十分强大的Android日志工具  
项目地址：https://github.com/orhanobut/logger  
Demo地址：https://github.com/orhanobut/logger/tree/master/app  
效果图：![Renderings](https://github.com/orhanobut/logger/blob/master/images/description.png)  

## 第三部分 优秀项目  
主要介绍那些Android还不错的完整项目，目前包含的项目主要依据是项目有意思或项目分层规范比较好。  
Linux  
项目地址：https://github.com/torvalds/linux  
Android  
项目地址：https://android.googlesource.com/ 或 https://github.com/android  
以上两个项目，不解释  

(1) ZXing  
二维码扫描工具  
项目地址：https://github.com/zxing/zxing 或 https://code.google.com/p/zxing/  
APK地址：https://play.google.com/store/apps/details?id=com.google.zxing.client.android  
PS：现在市面上很多应用的二维码扫描功能都是从这个修改而来  

(2) photup  
编辑机批量上传照片到facebook上  
项目地址：https://github.com/chrisbanes/photup  
APK地址：https://play.google.com/store/apps/details?id=uk.co.senab.photup  
PS：代码分包合理，很棒。不过这个项目依赖的开源项目比较多，比较难编译  
  
(3) github-android  
Github的Android客户端项目  
项目地址：https://github.com/github/android  
APK地址：https://play.google.com/store/apps/details?id=com.github.mobile  

(4) Notes  
MIUI便签  
项目地址：https://github.com/MiCode/Notes  
APK地址：https://github.com/Trinea/TrineaDownload/blob/master/miui-note-demo.apk?raw=true  
PS：项目分包比较合理，相比较miui的文件管理器https://github.com/MiCode/FileExplorer 代码规范较好得多  

(5) weicuiyuan  
四次元-新浪微博客户端  
项目地址：https://github.com/qii/weiciyuan  
APK地址：https://play.google.com/store/apps/details?id=org.qii.weiciyuan  

(6) gnucash-android  
一个记账理财软件  
项目地址：https://github.com/codinguser/gnucash-android  
APK地址：http://play.google.com/store/apps/details?id=org.gnucash.android  

(7) AntennaPod  
支持rss订阅、音乐订阅  
项目地址：https://github.com/danieloeh/AntennaPod  
APK地址：https://play.google.com/store/apps/details?id=de.danoeh.antennapod  

(8) ChaseWhisplyProject  
打鬼游戏  
项目地址：https://github.com/tvbarthel/ChaseWhisplyProject  
APK地址：https://play.google.com/store/apps/details?id=fr.tvbarthel.games.chasewhisply  

(9) Tweet Lanes  
功能完整的Twitter客户端  
项目地址：https://github.com/chrislacy/TweetLanes  
APK地址：https://play.google.com/store/apps/details?id=com.tweetlanes.android  

(10) Financius  
简单易用的记账程序  
项目地址：https://github.com/mvarnagiris/Financius  
APK地址：https://play.google.com/store/apps/details?id=com.code44.finance  

(11) todo.txt-android  
todo.txt的官方Android应用  
项目地址：https://github.com/ginatrapani/todo.txt-android  
APK地址：https://play.google.com/store/apps/details?id=com.todotxt.todotxttouch  

(12) simpletask  
基于todo.txt官方应用的另一个客户端  
项目地址：https://github.com/mpcjanssen/simpletask-android  
APK地址：https://play.google.com/store/apps/details?id=nl.mpcjanssen.todotxtholo  

(13) Muzei Live Wallpaper  
定时更换桌面精美壁纸  
项目地址：https://github.com/romannurik/muzei  
APK地址：https://play.google.com/store/apps/details?id=net.nurik.roman.muzei  

(14) Scanbook  
扫描搜索查询图书信息  
项目地址：https://github.com/JayFang1993/ScanBook  
APK地址：http://www.wandoujia.com/apps/com.scanbook   

(15) iosched
The Google I/O 2014 Android App  
项目地址：https://github.com/google/iosched  
APK地址：https://play.google.com/store/apps/details?id=com.google.samples.apps.iosched  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>

## 第四部分 开发工具及测试工具  
主要介绍和Android开发工具和测试工具相关的开源项目。  <a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  
#### 一、开发效率工具  
1. Parceler  
通过注解及工具类自动完成实体类 Parcelable及值传递  
项目地址：https://github.com/johncarl81/parceler  

1. Json2Java  
根据JSon数据自动生成对应的Java实体类，还支持Parcel、Gson Annotations对应代码自动生成。期待后续的提取父类以及多url构建整个工程的功能  
项目地址：https://github.com/jonfhancock/JsonToJava  
在线演示：http://jsontojava.appspot.com/  

1. IntelliJ Plugin for Android Parcelable boilerplate code generation  
Android studio插件，生成Parcelable代码  
项目地址：https://github.com/mcharmas/android-parcelable-intellij-plugin  
效果图：![Holo Colors Idea](https://github.com/mcharmas/android-parcelable-intellij-plugin/raw/master/screenshot.png)  

1. Android Holo Colors IntelliJ Plugin  
Android studio插件，生成holo样式9 patch图片  
项目地址：https://github.com/jeromevdl/android-holo-colors-idea-plugin  
效果图：![Holo Colors Idea](https://raw.github.com/jeromevdl/android-holo-colors-idea-plugin/master/other/holocolorsidea.png)  

1. Android Drawable Factory  
用于生成各个分辨率的图片  
项目地址：https://github.com/tizionario/AndroidDrawableFactory  
效果图：![Android Drawable Factory](https://github-camo.global.ssl.fastly.net/5c3844b345a9779296f996490070dab0bfc9dbf5/68747470733a2f2f646c2e64726f70626f7875736572636f6e74656e742e636f6d2f752f32363636343637352f416e64726f69644472617761626c65466163746f72792f312e706e67)  

1. SelectorChapek for Android  
Android Studio插件，可根据固定文件名格式资源自动生成drawable selectors xml文件。  
项目地址：https://github.com/inmite/android-selector-chapek  

1. Android Action Bar Style Generator  
Android ActionBar样式生成器，可在线选择ActionBar样式自动生成所需要的图片资源及xml文件  
项目地址：https://github.com/jgilfelt/android-actionbarstylegenerator  
在线演示：http://jgilfelt.github.io/android-actionbarstylegenerator/  

1. ButterKnifeZelezny  
用于快速生成[ButterKnife](https://github.com/JakeWharton/butterknife)View注入代码的Android Studio/IDEA插件  
项目地址：https://github.com/inmite/android-butterknife-zelezny  

1. RoboCoP  
利用Gradle task根据固定格式的json文件生成ContentProvider  
项目地址：https://github.com/mediarain/RoboCoP  

1. appiconsizes  
用于生成各个分辨率的图片  
项目地址：http://www.appiconsizes.com/  

1. Gradle Retrolambda Plugin  
[Retrolambda](https://github.com/orfjackal/retrolambda)是将Java8的Lambdas应用于Java7的工具，本项目是Gradle插件，通过Retrolambda从而使Java或Android项目用Java8的Lambdas编写，将编译后的字节码转换为Java6和7的字节码从而正常运行  
项目地址：https://github.com/evant/gradle-retrolambda  

1. Dagger IntelliJ Plugin  
dagger的intellij插件  
项目地址：https://github.com/square/dagger-intellij-plugin  

1. Android Gen Drawable Maven plugin  
在编译时根据SVG描述文件生成不同分辨率的jpg、png或点9图片  
项目地址：https://github.com/avianey/androidgendrawable-maven-plugin  

1. Android Asset Studio  
各种Android资源自动生成器，包括启动图标、ActionBar图标、通知栏图标、点9等  
项目地址：https://github.com/romannurik/AndroidAssetStudio  
在线演示：http://romannurik.github.io/AndroidAssetStudio/  

1. jsonschema2pojo  
根据Json内容生成java对象，支持jackjson和gson  
项目地址：https://github.com/joelittlejohn/jsonschema2pojo  
在线演示：http://www.jsonschema2pojo.org/  

1. 9-Patch-Resizer  
自动生成 png 及点 9 图片的不同分辨率版本  
项目地址：https://github.com/redwarp/9-Patch-Resizer  

1. AndroidLocalizationer  
可用于将项目中的 string 资源自动翻译为其他语言的 Android Studio/IntelliJ IDEA 插件  
项目地址：https://github.com/westlinkin/AndroidLocalizationer  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 二、开发自测相关  
1. Quality Tools for Android  
Android测试及自测工具集合和示例  
项目地址：https://github.com/stephanenicolas/Quality-Tools-for-Android  

1. android-test-kit  
Google的Android测试工具  
包括GoogleInstrumentationTestRunner(增强版的InstrumentationTestRunner)和Espresso(用于快速写出可靠测试用例的API)  
项目地址：https://code.google.com/p/android-test-kit/  
文档介绍：https://code.google.com/p/android-test-kit/w/list  

1. robolectric  
测试用例编写框架  
项目地址：https://github.com/robolectric/robolectric  
Demo地址：https://github.com/robolectric/robolectricsample  
文档介绍：http://robolectric.org/  
特点：(1). 不需要模拟器在一般JVM就可以运行测试用例  
(2). 能完成在真机上的大部分测试包括感应器  
其他的测试用例及相关模块Mock可见：[android-mock](https://code.google.com/p/android-mock/), [mockito](https://code.google.com/p/mockito/), [easy-mock](https://github.com/easymock/easymock)  

1. Android FEST  
提供一些列方便的断言，可用于提高编写Android自测代码效率  
项目地址：https://github.com/square/fest-android  

1. BoundBox  
可用于测试类各种访问权限的属性、方法。实际是通过BoundBox这个annotation生成一个属性和方法都是public权限的中间类并对此类进行测试完成的  
项目地址：https://github.com/stephanenicolas/boundbox  

1. Hugo  
用于打印函数信息及执行时间的工具，仅在debug模式生效  
项目地址：https://github.com/JakeWharton/hugo  

1. scalpel  
在应用下面添加一层用于界面调试，待详细补充 // TODO  
项目地址：https://github.com/JakeWharton/scalpel  

1. Android Screenshot library  
Android截图工具类，用于在持续集成时截图  
项目地址：https://github.com/rtyley/android-screenshot-lib  

1. sonar-android-lint-plugin  
将android lint的错误在sonar中展现  
项目地址：https://github.com/SonarCommunity/sonar-android  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 三、测试工具  
1. Spoon  
可用于android不同机型设备自动化测试，能将应用apk和测试apk运行在不同机器上并生成相应测试报告。  
项目地址：https://github.com/square/spoon  

1. Tencent APT  
APT是腾讯开源的一个Android平台高效性能测试组件，提供丰富实用的功能，适用于开发自测、定位性能瓶颈；测试人员完成性能基准测试、竞品对比测试  
项目地址：https://github.com/stormzhang/APT  

1. Emmagee  
网易开源的性能测试工具，包括CPU、内存、网络流量、启动时间、电池状态等  
项目地址：https://github.com/NetEase/Emmagee  

1. Android py-uiautomator  
py-uiautomator是一个对Android uiautomator用python进行封装的测试框架.  
项目地址：https://github.com/xiaocong/uiautomator  

1. Augmented Traffic Control  
模拟网络状况，包括带宽、时延抖动、丢包率、错包率、包重排率  
项目地址：https://github.com/facebook/augmented-traffic-control  

1. stetho  
强大的 Android Debug 工具。支持网络请求监控以及数据库查看，可以和 Chrome DevTools 结合或者命令行模式。  
项目地址：https://github.com/facebook/stetho  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 四、开发及编译环境  
1. Buck  
facebook开源的Android编译工具，效率是ant的两倍。主要优点在于：  
(1) 加快编译速度，通过并行利用多核cpu和跟踪不变资源减少增量编译时间实现  
(2) 可以在编译系统中生成编译规则而无须另外的系统生成编译规则文件  
(3) 编译同时可生成单元测试结果  
(4) 既可用于IDE编译也可用于持续集成编译  
(5) facebook持续优化中  
项目地址：https://github.com/facebook/buck  

1. Android Maven Plugin  
Android Maven插件，可用于对android三方依赖进行管理。在J2EE开发中，maven是非常成熟的依赖库管理工具，可统一管理依赖库。  
项目地址：https://github.com/jayway/maven-android-plugin  

1. umeng-muti-channel-build-tool  
渠道打包工具  
项目地址：https://github.com/umeng/umeng-muti-channel-build-tool  
另可参见Google的构建系统Gradle：http://tools.android.com/tech-docs/new-build-system/user-guide  

1. Genymotion  
目前最好用最快的android模拟器  
项目地址：http://www.genymotion.com/  
Android studio集成控件： http://plugins.jetbrains.com/plugin/7269?pr=idea  
Cyril Mottier推荐：http://cyrilmottier.com/2013/06/27/a-productive-android-development-environment/  

1. gradle-mvn-push  
方便的将Gradle的Artifacts上传到Maven仓库  
项目地址：https://github.com/chrisbanes/gradle-mvn-push  
文档介绍：https://github.com/chrisbanes/gradle-mvn-push#usage  

1. Android Emulator Plugin for Jenkins  
Android模拟器 jenkins插件，用于Jenkins做持续集成时跑模拟器测试  
项目地址：https://github.com/jenkinsci/android-emulator-plugin  

1. Android Maven Plugin  
管理应用所需要的依赖库。包括的构建工具有Maven、Gradle、ant、sbt  
项目地址：https://github.com/mosabua/maven-android-sdk-deployer  

1. SDK Manager Plugin  
下载和管理Android SDK的Gradle插件  
项目地址：https://github.com/JakeWharton/sdk-manager-plugin  

1. Gradle Protobuf Plugin  
将.proto文件转换成Java文件的gradle插件  
项目地址：https://github.com/andrewkroh/gradle-protobuf-plugin  

1. ChromeADB  
Chrome 的 Adb 插件，当登录后，能看到所有连接的设备并操作，可以看应用、进程、内存及磁盘使用情况等  
项目地址：https://github.com/importre/chromeadb  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 五、其他  
1. ViewServer  
允许app运行在任何手机上都可以用HierarchyViewer查看  
项目地址：https://github.com/romainguy/ViewServer  

1. GridWichterle for Android  
在整个系统上显示一个grid，用来帮助查看应用布局及使得布局更美观，可设置grid网格大小和颜色，android推荐48dp和8dp，可见 Android Design Guidelines – Metrics and Grids，比起hierarchyviewer相差甚远，不过偶尔可用来作为布局查看工具。  
项目地址：https://github.com/inmite/android-grid-wichterle  
Demo地址：https://play.google.com/store/apps/details?id=eu.inmite.android.gridwichterle  

1. Catlog  
手机端log查看工具，支持不同颜色显示、关键字过滤、级别过滤、进程id过滤、录制功能等  
项目地址：https://github.com/nolanlawson/Catlog  
在线演示：https://play.google.com/store/apps/details?id=com.nolanlawson.logcat  

1. PID Cat  
根据package查看logcat日志  
项目地址：https://github.com/JakeWharton/pidcat  

1. ACRA  
应用崩溃信息日志上报到GoogleDoc工具，网页版展现结果三方开源地址https://github.com/BenoitDuffez/crashreportsviewer  
项目地址：https://github.com/ACRA/acra  
文档介绍：https://github.com/ACRA/acra/wiki/BasicSetup  

1. Crashlytics  
提供丰富的应用崩溃信息日志收集  
轻量级，丰富，可自定义应用崩溃信息收集器，附有邮件通知  
项目地址：http://www.crashlytics.com/  
集成插件：[Android Studio, Eclipse and IntelliJ](http://try.crashlytics.com/sdk-android/?utm_source=blog&utm_medium=blog&utm_campaign=Announcing_android_studio_wp&utm_content=CTA_button)  

1. Android Resource Navigator  
chrome插件，可以方便的查看github上android源码工程的styles.xml和themes.xml。主要功能：  
(1) 快速打开android styles.xml themes.xml  
(2) 方便在资源间跳转。styles.xml themes.xml文件中资源链接跳转，可以方便跳转到某个资源  
(3) 方便查找某个style和theme。chrome地址栏输入arn+tab+搜索内容回车即可  
(4) 自动下载不同分辨率下的drawable  
(5) 通过映射查找那些不是按照固定命名规则命名的style和theme  
项目地址：https://github.com/jgilfelt/android-resource-navigator  
在线演示：https://chrome.google.com/webstore/detail/android-resource-navigato/agoomkionjjbejegcejiefodgbckeebo?hl=en&gl=GB  

1. android-resource-remover  
根据lint的提示删除项目中无用的资源，减少包的大小  
项目地址：https://github.com/KeepSafe/android-resource-remover  

1. Telescope  
通过手势截图以特定主题发送到特定邮箱地址报告Bug  
项目地址：https://github.com/mattprecious/telescope  

1. Complete Android Fragment & Activity Lifecycle  
完整的Android Fragment/Activity生命周期图  
项目地址：https://github.com/xxv/android-lifecycle  

1. Bugsnag Notifier for Android  
通过`Thread.UncaughtExceptionHandler`捕获应用未处理的异常崩溃 Bug 并用 Notification 展示同时上传到后台服务器  
项目地址：https://github.com/bugsnag/bugsnag-android  
文档介绍：https://github.com/bugsnag/bugsnag-android#installation--setup  

1. Material Design Icons  
Google Material Design 规范中的 Icon  
项目地址：https://github.com/google/material-design-icons  

1. scrollscreenshot  
Android 滚动屏幕自动截图 jar 包，支持纵向、横向滚动截屏拼接  
项目地址：https://github.com/PGSSoft/scrollscreenshot  
效果图：![Renderings](https://github.com/PGSSoft/scrollscreenshot/raw/master/samplehorizontal.png)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>   

1. droidicon  
1600+的海量Icon，包括750+的Material Design icons    
项目地址：https://github.com/theDazzler/droidicon   
  
## 第五部分  
主要介绍那些乐于分享并且有一些很不错的开源项目的个人和组织。Follow大神，深挖大神的项目和following，你会发现很多。  

#### 一、个人  
1. JakeWharton  
就职于Square，绝对牛逼的大神，项目主要集中在Android版本兼容，ViewPager及开发工具上  
Github地址：https://github.com/JakeWharton  
代表作：ActionBarSherlock，Android-ViewPagerIndicator，Nine Old Androids，SwipeToDismissNOA，hugo，butterknife，Android-DirectionalViewPager, scalpel    
pidcat另外对square及其他开源项目有很多贡献  
主页：http://jakewharton.com/  

1. Chris Banes  
Github地址：https://github.com/chrisbanes  
代表作：ActionBar-PullToRefresh，PhotoView，Android-BitmapCache，Android-PullToRefresh  
主页：http://chris.banes.me/  

1. Koushik Dutta  
就职于ClockworkMod  
Github地址：https://github.com/koush  
代表作：Superuser，AndroidAsync，UrlImageViewHelper，ion, 另外对https://github.com/CyanogenMod 的开源项目有很多贡献  
主页：http://koush.com/  

1. Simon Vig  
Github地址：https://github.com/SimonVT  
代表作：android-menudrawer，MessageBar  
主页：http://simonvt.net/  

1. Manuel Peinado  
Github地址：https://github.com/ManuelPeinado  
代表作：FadingActionBar，GlassActionBar，RefreshActionItem，QuickReturnHeader  

1. Emil Sj?lander  
Github地址：https://github.com/emilsjolander  
代表作：StickyListHeaders，sprinkles，android-FlipView  
主页：http://emilsjolander.se/  

1. greenrobot  
Github地址：https://github.com/greenrobot  
代表作：greenDAO，EventBus  
主页：http://greenrobot.de/  

1. Jeff Gilfelt  
Github地址：https://github.com/jgilfelt  
代表作：android-mapviewballoons，android-viewbadger，android-actionbarstylegenerator，android-sqlite-asset-helper  
主页：http://jeffgilfelt.com  

1. Romain Guy  
Android team成员(2013.10已离开Android team，仍在Google)  
Github地址：https://github.com/romainguy  
代表作：ViewServer  
主页：http://www.curious-creature.org/category/android/  
個人攝影作品：http://www.flickr.com/photos/romainguy  

1. sephiroth74  
就职于Aviary.com  
Github地址：https://github.com/sephiroth74  
代表作：ImageViewZoom，HorizontalVariableListView，AndroidWheel，purePDF  
主页：http://www.sephiroth.it/  

1. Cyril Mottier  
Google开发者专家认证，发布一些Android技巧及文章  
Github地址：https://github.com/cyrilmottier  
代表作：GreenDroid，Polaris  
主页：http://cyrilmottier.com/  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 二、组织  
1. Square  
有态度有良心的企业，很多不错的分享  
Github地址：https://github.com/square  
代表作：okhttp、fest-android，android-times-square、picasso、dagger、spoon等等  
主页：http://square.github.io/  

1. Inmite s.r.o.  
Github地址：https://github.com/inmite  
代表作：android-styled-dialogs，android-grid-wichterle，android-selector-chapek  
主页：http://www.inmite.eu/  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

#### 三、博客  
[部分国外著名 Android 开发者信息](https://github.com/android-cn/android-dev-com)  
<a href="https://github.com/Trinea/android-open-project#%E7%9B%AE%E5%89%8D%E5%8C%85%E6%8B%AC" title="返回目录" style="width:100%"><img src="http://farm4.staticflickr.com/3737/12167413134_edcff68e22_o.png" align="right"/></a>  

## License

    Copyright 2014 trinea.cn

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

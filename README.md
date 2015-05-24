# android_agility
一款高度集成，精简，方便，易用Android应用快速开发框架。http请求，UI组件，常用工具应有尽有。<br>
<br>
<h3>网络请求模块：</h3>
RequestManager＋RequestAdapter：<br>
  1.基于Volley再次整合，使用泛型实现直接返回对象，调用着可忽略中间细节，大量减少代码量；<br>
  2.统一借口调用，实现Bitmap，File下载，API借口调用（只需一行代码）；<br>
  3.所有请求使用缓存机制，提高程序响应速度；<br>
  4.支持GIT，POST，DELETE，PUT；<br>
  5.使用TAG标记一条http请求，可在任意时刻中断请求；<br>
  6.采用借口回调方式，简介明了；<br>
  7.开放借口，任意扩展；<br>
<br>
<h3>图片加载：</h3> 
BitmapLoader：<br>
  1.（网络）基于NetworkImageView实现图片异步加载（一行代码），你懂的；<br>
  2.（本地）本地大图异步加载，获取制定大小缩略图；<br>
  3.以上加载方式全部使用缓存；<br>
<br>
<h3>常用工具类：</h3>
BaseUtils（方便使用的基础函数库）；<br>
File（文件相关：搜索，复制，删除文件夹，追加内容，读取）；<br>
MD5Urils；<br>
Root（Android Root权限操作）；<br>
...<br>
PS：请见包 org.pinwheel.agility.util.*;<br>
<br>
<h3>HTTP服务器组件：</h3>
  1.整合NanoHTTPPD框架，实现Android本地搭建HTTP服务器；<br>
  2.SimpleWebServer包装NanoHTTPPD，实现一行代码创建；<br>
<br>
<h3>UI组件：</h3>
SweetDialog：<br>
  1.对话框高度可定制；<br>
  2.DefaultStyle缺风格，采用资源反射方式实现简易的定制化；<br>
  3.SimpleProgressDialog只需一行代码，可实现IOS风格Loading对话款了，详情请见Demo；<br>
<br>
TouchAnimator:<br>
  1.快速实现一个View点击效果；<br>
  2.已实现基础控件 AnimatorButton，AnimatiorCheckBox，AnimatorImageButton ...<br>
<br>
FlowLayout：<br>
  1.Android流式布局；<br>
<br>
SweetLisView，SweetGridView，SweetScrollView：<br>
  1.目前最完美的越界回弹效果，谁用谁知道；<br>
  2.支持下拉定点Hold，可展示列表下层的试图；<br>
<br>
SeekBarVertical<br>
  1.垂直的SeekBar；<br>
<br>
HeaderGridView：<br>
  1.代Header的GridView；<br>
<br>
TabController：<br>
  1.快速实现主流应用的首页选项卡效果；<br>
  2.Pager＋Buttons分离，效果完全可定制；<br>
<br>  
SwipeListView，SwipeGridView，SwipeScrollView：（下拉刷新组件）<br>
  1.采用反射机制映射资源，无需代码即可实现Header，Footer各种样式；<br>
<br>
<br>
Agility的设计在于简化开发过程中的基础模块，做到功能借口标准，简介，使调用者能一行代码实现复杂的功能。<br>
<br>
    
### 3.9.4
###### 2019-4-27
- [新增]支持自定义分享模版，可以在新的设置类别`个性化`中找到。
- [优化]文章概述文字从144提高到200，避免设备太宽时不够显示的问题。
- [修复]修复自定义启动图标不能设置自定义图片的问题。

### 3.9.3
###### 2019-3-20
- [修复]修复Android 4.x版本运行就崩溃的问题。

### 3.9.2
###### 2019-3-16
- [优化]优化排序：提供重置按钮。未分类的订阅源也可以排序了。
- [修复]修复Android 9上登录和内置浏览器问题。
- [修复]修复搜索及添加订阅时崩溃问题。

### 3.9.1
###### 2019-3-14
- [优化] 去除友盟统计，朋友圈分享不再依赖友盟。
- [修复] Feedly，Inoreader现在只能使用HTTPS连接。
- [修复] 修复默认排序问题。排序重置按钮将在下个版本加入。
- [修复] 修复Tiny Tiny RSS无法保存图片的问题。
- [修复] 修复拔下耳机没有停止播放的问题。

# 3.9
###### 2018-10-6
- [新增] 订阅源支持排序。
- [优化] 支持SD卡设置为缓存路径。
- [优化] 图片另存时更新媒体记录，方便图片浏览器查看。（部分设备不支持）
- [修复] Tiny Tiny RSS 支持附件显示。
- [修复] 修复 InoReader / FreshRSS / The Old Reader / Bazqux 标签显示问题。

### 3.8.5
###### 2018-8-8
- [新增] 支持黑莓key系列手机进行快捷操作。详见：https://plus.google.com/u/1/100365587272890955375/posts/jPjZU6H2dip
- [优化] 右上角侧栏及返回按钮添加文字描述，方便视力不佳者。
- [修复] 修复FeedMe mobilizer不能正确解析纯音频页面的错误。
- [修复] 修复某些情况下在WIFI下图片不能下载的问题。

### 3.8.4
###### 2018-7-8
- [新增] 在`设置`-`关于`增加`数据收集`的选项，默认为关闭。
- [修复] 修复 Mercury mobilizer 图片重复的问题。

### 3.8.3
###### 2018-7-7
- [优化] Mobilizer 获取文章失败时显示原因，并在底部提供`report issue`按钮。
- [优化] Mercury 支持显示头图。
- [优化] 现在 FeedMe 与 Feedly 官方版一致，缩略图也会出现在正文中。
- [修复] 修复`订阅源管理对话框`的`退订`及`过滤`功能不可见的问题。
- [修复] 修复解析 HTML 错误的问题。
- [修复] Tiny Tiny RSS 获取的内容按时间排序倒序。

### 3.8.2
###### 2018-6-23
- [修复] 修复自动同步停止的问题。
- [修复] 修复保持未读状态被重置的问题。
- [修复] 修复一些其他问题。

### 3.8.1
###### 2018-6-21
- [修复] 修复闪退及其他一些问题。

# 3.8
###### 2018-6-15
- [新增] 支持显示播客章节。
- [新增] 支持自适应图标。
- [新增] 自动切换主题支持自定义时间。
- [优化] 优化同步未读文章的速度。
- [优化] 优化分享至朋友圈，支持分享播客。
- [修复] 修复其他问题。

### 3.7.1
###### 2018-5-24
- [修复] 修复崩溃问题。

# 3.7
###### 2018-5-23
- [新增] 支持分享到微信朋友圈，在`设置` - `服务`中开启。
- [优化] `设置` - `音频`下增加音频播放速度启用开关，无法播放音频的设备可以尝试禁用此功能
- [修复] 修复部分设备因新增的相机权限而不能从Play商店安装的问题。
- [修复] 修复单词间空格被删除的问题。
- [修复] 修复某些情况下分享时邮件主题没有填写的问题。

# 3.6
###### 2018-4-28
- [新增] 支持者福利：在`设置`-`关于`中创建自定义启动图标。
- [优化] 在`设置`-`界面`添加选项：屏幕足够宽时总是显示侧栏。
- [修复] 修复缓存数量重置问题。
- [修复] 修复“open url failed”问题。
- [修复] 其他优化与修复。

### 3.5.9
###### 2018-4-21
- [特别注意] 需求 相机 和 快捷方式 权限来支持新的快捷方式功能，但是这个版本还不能使用。
- [修复] 修复侧栏同步按钮和计数在小屏手机上不显示的问题。

### 3.5.8
###### 2018-4-12
- [新增] 侧栏高亮显示当前列表条目。
- [新增] 播放界面增加加星操作。
- [修复] 修复切换侧栏条目时文章列表标题不变的问题。
- [修复] 修复临时标签丢失的问题。

### 3.5.7
###### 2018-4-4
- [新增] 当屏幕宽度超过640dp时，首页同时显示文章列表与侧栏。（7.1以上带虚拟导航栏的设备在顺时针旋转横屏时会有显示问题）
- [新增] 支持蓝牙耳机（播放与停止）。
- [新增] `图片浏览器`增加`禁用`选项。
- [新增] Feedbin支持自建主机。
- [优化] 下拉刷新总是同步当前列表，而不是整体同步。如果当前列表为`所有条目`，则类似于整体同步。
- [优化] 优化FreshRSS登录体验，自动补全API地址。
- [优化] 优化文章页一键分享至Todoist。
- [优化] `临时标签`上限提高到5个。
- [修复] 修复7.1以上虚拟导航位置判定错误的问题。
- [修复] 修复首次登录时登录信息未被记录的问题（问题产生于3.5.6）。
- [修复] 修复`同步模式`设置为`全部`，但是某些源禁用的情况下，同步条数异常错误的问题。
- [修复] 修复FreshRSS仅同步100条的问题（问题产生于3.5.6）。
- [修复] 修复某些情况下使用TTS播放异常的问题。

### 3.5.6
###### 2018-3-14
- [特别注意] 由于多账户功能的改动，更新到新版后，已下载的文章的图片将不可见。如有必要，请清除缓存后重新下载。
- [优化] 不支持按源/类别同步的服务（Feedbin，FreshRSS）现在无法修改`同步模式`，启用了`中国模式`也无法修改`同步模式`，`同步模式`固定为`所有`。
- [优化] Tiny Tiny RSS增加对auth_remote的支持。
- [修复] 修复开启`自动标记已读`时过多文章被标记已读的问题。
- [修复] 修复某些情况下FeedMe mobilizer解析网页乱码的问题。
- [修复] 关键字过滤现在会忽略大小写。
- [修复] 修复一些小问题。
- [其他] 多账户功能相关改动。

### 3.5.5
###### 2018-2-24
- [优化] 音频播放过程中如果有提示音，不再暂停播放，而是降低音量。
- [优化] 下载过程显示已下载的图片数。
- [修复] 修复Feedly同步时返回`Json parse error`的问题。
- [修复] 修复Tiny Tiny RSS下拉刷新同步卡住的问题。
- [修复] 修复TTS将2个单词读成一个单词的问题。
- [修复] 修复列表摘要文字未转码的问题。
- [其他] 可以外部调用同步服务。
``` java
Intent intent = new Intent();
intent.setClassName("com.seazon.feedme", "com.seazon.feedme.service.sync.SyncService");
intent.putExtra("auto", false);
intent.putExtra("type", syncTypes);
activity.startService(intent);

// syncTypes取值如下（相加表示执行多个动作）：
public static int SYNC_TO_SERVER = 1;
public static int SYNC_UNREAD_FROM_SERVER = 2;
public static int SYNC_STARRED_FROM_SERVER = 4;
public static int SYNC_DELETE_READ = 16;
public static int SYNC_DOWNLOAD_IMAGE_AND_WEB_PAGE = 32;
public static int SYNC_DOWNLOAD_PODCAST = 256;
```

### 3.5.4
###### 2018-2-8
- [新增] 支持FreshRSS，一个类似Tiny Tiny RSS自托管的RSS服务。网站：https://freshrss.org/。
- [优化] 优化缩略图显示。现在即使同步时没有下载缩略图，也能正常显示了。
- [修复] 修复Tiny Tiny RSS同步卡住的问题。
- [修复] 修复点击添加订阅按钮时崩溃的问题。
- [修复] 修复一些小问题。

### 3.5.3
###### 2018-1-29
- [优化] 分享链接到FeedMe来添加订阅，或者复制链接到系统剪切板，点击添加订阅时自动填入链接。
- [修复] 修复通过印象笔记登录Feedly总是失败的问题。
- [修复] 修复某些情况下图片不下载的问题。
- [修复] 修复重复菜单的问题。
- [修复] 修复一些小问题。
- [其他] 增加内购商品：樱桃。

### 3.5.2
###### 2018-1-16
- [修复] 修复Tiny Tiny RSS只能同步到100条未读的问题。
- [修复] 修复文章页面下载完图片后没有刷新的问题。
- [修复] 修复下拉刷新同步不能将服务端已读文章标记为已读的问题。

### 3.5.1
###### 2018-1-12
- [新增] 除了`同步`通知和`播放`通知，现在新增了一个`最爱`通知，用于显示`临时标签`的未读文章情况。同时，现在可以在订阅源设置中启用通知，那么当这个订阅源有未读文章时，也会在`最爱`通知中显示。
- [新增] 适配8.0的通知渠道，你可以通过系统的通知设置，为不同类别的通知配置不同铃声等设置。
- [优化] 现在`临时标签`会显示未读条数。
- [优化] 文章列表中未读和加星标记移到了行首，不会再被图片遮挡。阅读时间也受`设置`-`界面`-`显示阅读时间`影响。
- [修复] 修复某些情况下通知栏自动显示`播放`通知的问题。
- [修复] 修复开启Eink优化时文章页双击crash问题。
- [修复] 修复Tiny Tiny RSS因类别和订阅源id冲突导致的一系列问题。
- [修复] 修复文章页面图片下载进度条显示错误问题。

# 3.5
###### 2017-12-06
- [新增] 支持 Tiny Tiny RSS。 重要：先确保你的TTRSS设置里已经启用了"Enable API access"，否则无法在FeedMe登录。
- [新增] 支持`临时标签`：可以在侧栏添加`临时标签`，它用起来同源／类别没有什么区别。当你点击它时，文章列表页面会显示所有标题中含有这个标签的文章。目前最多可以添加3个`临时标签`。
- [新增] 批量导出图片：如果你订阅了一些含有大量图片的源，在此之前你需要一张一张保存图片。现在你可以批量保存一个源／类别的图片。保存位置同保存单个图片。特别的，一旦执行此操作，未读文章会被标记为已读，而已读并且同步到服务器的文章将被删除。
- [优化] 你可以通过点击侧边栏顶部的RSS类型来隐藏你的账号信息。
- [优化] 现在选择内置浏览器，则新页面总是会在内置浏览器中打开，而不是Chrome。

### 3.4.3
###### 2017-11-29
- [修复] 修复某些情况下同步不下载图片和web页面的问题。

### 3.4.2
###### 2017-11-20
- [修复] 修复德语语言下同步间隔无法设置的问题。

### 3.4.1
###### 2017-11-16
- [修复] 修复某些移动流量设置不起作用的问题。
- [修复] 修复文章列表页面滑动时无法隐藏动作条的问题。

# 3.4
###### 2017-11-13
- [新增] 调整同步的设置选项。提供`移动数据`整合所有`仅Wi-Fi`的选项。提供`高级`整合订阅源设置的全局设置。
- [优化] 侧栏显示登录的RSS服务及登录账号。
- [修复] 修复svg图片问题，现在能正确显示svg的图片了。
- [修复] 修复缓慢滚动时动作栏抖动问题。
- [修复] 修复某些情况下底部动作条显示不正确的问题。
- [修复] 修复卸载的一键分享菜单无法从动作栏移除的问题。

### 3.3.2
###### 2017-10-11
- [优化] 优化一键分享到已安装应用。现在不需要重置菜单了。
- [修复] 修复DashClock中不显示的问题。

### 3.3.1
###### 2017-9-15
- [修复] 修复闪退问题。

# 3.3
###### 2017-9-14
- [新增] 支持在文章界面菜单中添加系统分享功能，实现一键分享到你最常用的应用。（在`设置`-`服务`中开启需要使用的分享。开启后，可以在文章界面的菜单中找到。目前可能需要重置一下菜单。）
- [新增] 支持自定义通知。
- [新增] 支持直接在文章界面播放视频（`实验室`中增加`Video Preview`）。
- [优化] 播放界面支持横屏显示。
- [优化] 禁用音频功能后不会自动下载音频。
- [优化] 其他一些小优化。
- [修复] 修复过滤功能不能过滤某些关键字的问题。
- [修复] 修复微信订阅文章FeedMe Mobilizer解析失败的问题。

### 3.2.1
###### 2017-6-17
- [修复]修复Feedly使用谷歌登陆失败的问题。
- [修复]适配s8等超宽手机。
- [修复]直接在浏览器中打开会标记为已读了。

# 3.2
###### 2017-6-12
- [新增]现在可以在列表页面播放当前列表（此操作会清空播放列表，并且列表最多存放前100条。）
- [新增]同步时自动下载播客音频（下载至少60分钟的音频节目）
- [新增]音频变速
- [新增]快进／快退功能，可以在设置中设置时间。
- [新增]文章页面也支持播放菜单。
- [新增]增加音频功能开关，如果你不需要音频功能，可以关闭它。
- [新增]在设置-界面中增加新选项，在列表页面单击条目可以直接在浏览器中打开。
- [优化]菜单编辑对话框增加重置按钮。
- [优化]卡片布局也支持隐藏摘要。
- [优化]优化播放功能及显示细节。
- [优化]增加connection close选项。
- [修复]加星条目顺序问题。

### 3.1.3
###### 2017-6-8
- [修复]修复已读条目同步后变为未读的问题。

### 3.1.2
###### 2017-5-20
- [优化]现在文章页只需点击1次来`保持未读`，并更新了`保持未读`的图标。
- [优化]订阅源设置页面支持单击复制订阅源链接。
- [优化]为TalkBack完善播放按钮的标签。
- [优化]实验室增加缩略图选择开关（仅用于测试）。
- [修复]修复Inoreader oauth方式无法登录的问题。
- [修复]修复电子墨水屏优化开启后文章页字体可见性差的问题。

### 3.1.1
###### 2017-5-9
- [优化]优化缩略图屏蔽，相同的图片不会重复加入列表。
- [优化]通过后退键离开应用可以隐藏列表中的已读条目。
- [优化]因网络超时而下载失败的图片，会在下次下载时继续尝试。
- [修复]修复bazqux问题，并完善认证过期提示重新登录的提示。
- [修复]修复分菜单模式下，横屏时FAB按钮不显示的问题。

# 3.1
###### 2017-4-28
- [新增]支持线控（播放与停止）。
- [新增]支持设置睡眠时间（在播放界面）。
- [新增]增加订阅源统计（在设置-关于中），能让你更好的了解每个源的阅读情况。
  - 每个订阅源会显示2个数值：
    - 兴趣指数`阅读数 + 加星数 * 2`：数值越高，说明你在这个订阅源看的文章越多，感兴趣的文章越多。
    - 阅读百分比`阅读数 / ( 阅读数 + 浏览数 )`：百分比越高，说明你对这个订阅源越感兴趣。90%以上的会优先显示。
  - 点击单个源，还可以看到5个数值：
    - fetch: 同步到的文章数。
    - filter: 使用过滤功能过滤掉的文章数。
    - glance: 在列表页使用`以上标记为已读`或者`全部标记已读`的文章数。
    - read: 进入文章页阅读的文章数。
    - star: 加星的文章数。
  - 菜单可以选择统计范围（今天，本周，本月，所有），默认为今天。
- [新增]支持Chrome custom tabs。
- [优化]优化布局。删除`摘要`布局。现在如果你使用`列表`布局时，可以设置是否显示缩略图/摘要。
- [优化]添加TTS引擎更换，但是需要重启应用。
- [优化]修改标记已读的时机：
  - 之前进入文章页面时就标记为已读，现在是离开文章页面时标记为已读。
  - 之前文章页侧滑从A文章到B文章，会标记B文章为已读，现在是标记A文章为已读。
- [优化]去掉Embedly mobilizer。
- [修复]修复隐藏广告图片不起作用的问题，并修改提示，说明并不是针对广告，而是所有用户不想看到的缩略图。最多添加32个缩略图，因为太多会影响同步速度。如果继续添加，会将最先添加的移除。
- [修复]修复默认浏览器问题，增加内置选项，现在默认代表使用系统默认值，如果没有设置，就会弹出选择框。

### 3.0.4
###### 2017-4-9
- 新增`显示阅读时间`选项，来控制是否在文章页显示阅读时间提示，默认为不显示。
- 更新`下拉刷新`选项，新增`隐藏已读条目并同步`。
- 现在长按列表页缩略图来标记为广告图片不会在`视觉`布局起作用。
- 现在缩略图会更快显示，但gif只会显示第一帧。
- 播放菜单加入了`向左（右）滑动`快捷手势，可以在`操纵`设置中修改。
- 文章通过TTS播放完以后会自动标记为已读。
- 修复Bazqux同步问题。

### 3.0.3
###### 2017-4-6
- 实验室新增Eink闪屏优化。
- 网页浏览器和图片浏览器现在可以在设置中指定具体的外部浏览器了。
- 特殊处理时间间隔为24小时的选项，现在它只会在凌晨同步。注意，如果凌晨时因为网络不可用而没有同步，那么它会在网络可用后开始同步。同步完会把下个同步时间设置为下个凌晨。
- 缩略图可以长按并标记为广告图片，那么下次再碰到这个图片链接，就不会下载，也不会再缩略图显示。最多添加16个图片为广告图片，如果继续添加，最早加入的广告图片将不再被认为是广告图片。
- 更新部分图标。

### 3.0.1
###### 2017-3-20
- Fixed crash issue.

# 3.0
###### 2017-3-19
- Support podcast (not support `Feedbin`) and TTS. Please read <a href="https://github.com/seazon/FeedMe/blob/master/podcast_tts.md">Podcast & TTS</a> for the detail.
- Provide reading time.
- Add `Podcast` layout, which show play or download progress.
- Add `Lab` in `Settings`, including `Hardware Acceleration`.
- Improve `Accent` color, now support more color and customize color.

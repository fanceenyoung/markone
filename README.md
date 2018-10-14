<h1 align="center">Mark One 马一记</h1>
<h3 align="center">The Simplest Way to Take Notes for Online Videos</h3>
<h3 align="center">针对在线视频，基于Chrome拓展应用的最简单的笔记类应用</h3>
<p align="center"><img src="https://audionetwork.oss-cn-beijing.aliyuncs.com/markone/Promotion_image.png">
</p>
Mark One通过Chrome拓展提取视频字幕文件，将字幕/语义识别自动生成的字幕转化为笔记，可在视频播放页面的一键截图、记笔记等功能，满足用户在线学习时的轻量化笔记需求，支持YouTube及Bilibili。自2018.8月登录Chrome应用商店以来，累计下载数已350+，浏览数超过5000+，获得小众软件等媒体报道。

***
你是否遇到过这样的问题，看到一些有意思的点，想稍微做点记录，可是吧，懒得打字，懒得复制粘贴，不知道记在哪里，又或是身边没有纸笔，就算视频可以收藏分组，但其实并不需要mark整个视频，而且往往收藏了也没有再看过，于是乎就这样错过了一个个有意思的地方。

对于这个问题，我们想做一点尝试。于是有了Mark One。

实现方式：虽然通过移动端看视频已经占到大约70%，但介于App本身的封闭，我们只能采用网页端Chrome拓展应用的形式，另外由于每个网站的API都要单独做，介于开发能力的限制，我们选择了在海外使用人数最多的YouTube以及我们的Bilibili。

#### 产品功能介绍：
<p align="center"><img src="https://audionetwork.oss-cn-beijing.aliyuncs.com/markone/screenshot_markone.png">
</p>

具体来说，装了这个Chrome拓展后，在插件端：
1. 点击开始、结束，自动抓取这一时间段的字幕，不用打字了哦也~
2. 一件截图~
3. 在底部文本输入框直接输入笔记，不用切换笔记软件
4. 进度条显示笔记预览图，点击跳转播放位置

<p align="center"><img src="https://audionetwork.oss-cn-beijing.aliyuncs.com/markone/extension_intro_cnhui.png">
</p>

在笔记端，可以：
1. 查看所有在扩展程序中记录的内容；
2. 对某一条目内容进行高亮标记，重点记忆；
3. 双击模块进行编辑；
4. 一键复制所有内容，方便导出。
<p align="center"><img src="https://audionetwork.oss-cn-beijing.aliyuncs.com/markone/Chrome_markone_notes.png">
</p>

***
#### 如何安装扩展应用：
1. 科学上网，点击<a href = "https://chrome.google.com/webstore/detail/mark-one-online-video-not/alnbdccffncnmmffkcmojobcaejebing?hl=en-US" target="_blank">这里</a>进入Chrome 应用商店直接安装；
2. 点击<a href="https://audionetwork.oss-cn-beijing.aliyuncs.com/MarkOne.crx" target="_blank">这里</a>下载源文件，并将文件拖拽到Chrome拓展应用页面完成安装。

#### 如何使用：
在安装拓展后，在我们支持的视频网站里，请点击网址旁边的Mark One的橙色logo激活拓展应用，即可看到底部悬浮条，首次使用需要注册登录。

#### 背后的故事：
如果你想知道Mark One马一记背后的故事，这个idea如何产生、发展，我们如何做用户调研、设计产品细节，如何做到轻巧好用，欢迎浏览知乎专栏：https://zhuanlan.zhihu.com/HKlife

#### 特别鸣谢：
* 玩转Chrome拓展程序的前端工程师：我问下他git的
* 超好沟通追求细节笔记页面前端工程师：<a href ="https://github.com/Tanbinghua">@Tanbinghua</a>
* 搞定一切后台的后端工程师：<a href ="https://github.com/zhangtianyi1234">@zhangtianyi1234</a>

#### 开发参考：
* [google官方文档](https://developer.chrome.com/extensions/getstarted)
* [360关于chrome插件开发](http://open.chrome.360.cn/extension_dev/overview.html)
* [chrome插件开发全攻略](https://www.cnblogs.com/liuxianan/p/chrome-plugin-develop.html)

#### 协作开发：
- 源代码：
  * git clone https://github.com/fanceenyoung/markone.git

- Pull requests 方式：
  * rebase origin/master）
  * 请从 `develop` 分支开始；（ 注意：rebase origin/master）
  * Pull requests
  *

#### 联系信息：
任何痛点、idea、反馈、意见, 请发邮件到：markone_support@163.com。

#### 许可：
[![license-badge]][license-link]

<!-- Link -->
[www-badge]:        https://img.shields.io/badge/website-_simpread.ksria.com-1DBA90.svg
[version-badge]:    https://img.shields.io/badge/lastest_version-1.1.1-blue.svg
[version-link]:     https://github.com/fanceenyoung/markone/releases
[chrome-badge]:     https://img.shields.io/badge/download-_chrome_webstore-brightgreen.svg
[chrome-link]:      https://github.com/fanceenyoung/markone/releases
[offline-badge]:    https://img.shields.io/badge/download-_crx-brightgreen.svg
[license-badge]:    https://img.shields.io/github/license/mashape/apistatus.svg
[license-link]:     https://opensource.org/licenses/MIT

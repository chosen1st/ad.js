ad.js
=================

####功能####
免越狱去除视频广告、部分网页广告

####适用于####
系统：iOS （iOS 9.3可能会失效，请更新至iOS 9.3.1）   
广告屏蔽：优酷、土豆、乐视、湖南电视台、搜狐视频、腾讯视频、谷歌广告、百度广告

####如何设置####
>第一步：打开 设置 - 无线局域网   
>第二步：点击 iPhone 已经连接成功的无线网络名称右侧的 ⓘ 按钮   
>第三步：进入界面后下拉至底部，在“HTTP 代理”一栏中点击“自动”标签。   
>第四步：在 URL 框中输入：`http://cdce.cf/ad.js`   
>第五步：点击屏幕左上角【 ＜无线局域网 】返回即可保存设置。   

####如何关闭####
在“HTTP 代理”一栏中点击“关闭”标签。返回保存即可。

####原理####
通过无效的代理服务器访问ad.js里包含的域名，返回404状态码。对于未被ad.js包含的域名将采用直连的方式连接，不会经过代理服务器。本站不会记录您的任何信息。

####项目主页####
[http://cdce.cf/](http://cdce.cf/)

####报告问题####
[https://github.com/MikeWang000000/ad.js/issues](https://github.com/MikeWang000000/ad.js/issues)

####License####
[GNU General Public License v3.0](http://www.gnu.org/licenses/gpl-3.0.html)

=== SteamProfile 2.1.0 (Ajax Version) ===

** Installation and Usage **

Extract archive to the desired location on your webserver.
The directory "steamprofile/cache" is used for caching, therefore it must be read- and writable for the web server process.

You can change configurations for the XML proxy in "steamprofile/common.cfg" and "steamprofile/xmlproxy.cfg".
For client configuration and template editing, open "steamprofile/ajax/steamprofile.xml".

See example.html for examples and instructions for proper embedding into your website.

** Server Requirements **

 - Any PHP-compliant webserver (tested with Apache/2.2.11)
 - PHP 5.0.0 or higher, 5.2.x recommended (tested with PHP/5.2.6-3ubuntu4.2)
 - cURL (libcurl3 7.x)
 - GD library (libgd2 2.x)

** Client Requirements **

 - Any modern browser with enabled JavaScript

** Known Problems **

Internet Explorer 7 / Internet Explorer 8 in compatibility mode:
 - "Loading..." is not displayed
 - icons are not showing up

Internet Explorer 6 (of course):
 - unable to display transparent 32-bit PNG images
 - slider menu unusable
 - flawed layout
 
 === SteamProfile 2.1.0（阿贾克斯版）===

**安装和使用**

解压压缩文件到您的Web服务器需要的位置。
目录“steamprofile /缓存”用于高速缓存，因此它必须是只读和可写的Web服务器进程。

您可以更改为“steamprofile / common.cfg”和“steamprofile / xmlproxy.cfg”的XML代理配置。
对于客户端的配置和模板编辑，打开“steamprofile / AJAX / steamprofile.xml”。

见example.html为适当的嵌入到你的网站的例子和说明。

**服务器要求**

  - 任何PHP兼容的Web服务器（使用Apache / 2.2.11测试）
  - PHP 5.0.0或更高版本，5.2.x推荐（使用PHP / 5.2.6-3ubuntu4.2测试）
  - 卷曲（libcurl3 7.x中）
  - GD库（libgd2 2.X）

**客户端要求**

  - 任何现代浏览器中启用JavaScript

**已知问题**

的Internet Explorer 7 / Internet Explorer 8的兼容模式：
  - “载入中...”不显示
  - 图标不显示出来

的Internet Explorer 6（当然）：
  - 无法显示透明的32位PNG图像
  - 滑动菜单无法使用
  - 有缺陷布局
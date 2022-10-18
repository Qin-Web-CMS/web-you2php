# You2PHP
----
You2PHP是一个用PHP开发的Youtube流量代理脚本、通过对接谷歌api获取数据，可用来搭建Youtube视频镜像站、可实现长城之内观看Youtube。
请访问项目主页[https://you2php.github.io//](https://you2php.github.io/)查看更详细介绍。

![https://you2php.github.io/img/pic/jt1.png](https://you2php.github.io/img/pic/jt1.png)

# 特点
使用You2PHP的成本非常低，只需要一个支持PHP环境的虚拟海外主机，上传代码简单设置即可立即使用。无论您使用的是虚拟主机，还是VPS，上传即可使用，无需数据库！

You2PHP对接谷歌官方APi，实现了视频/频道搜索、视频在线播放 、频道/类别内容预览、视频下载等功能、浏览这些内容不需要您的设备上安装任何软件。

You2PHP采用GPL开源协议发布，你可以自由的使用和修改代码，随时随地，访问一个URL即可观看全球视频。
请访问项目主页[https://you2php.github.io//](https://you2php.github.io/)查看更详细介绍。
# 如何安装与使用
请查看You2PHP文档[https://you2php.github.io/doc/](https://you2php.github.io/doc/)

请在遵守当地相关法律法规的前提下使用本项目

本人拒绝为任何商业或非法目的提供任何技术支持

本项目仅为科研人员更方便地学习知识而创建, 请勿大范围传播
# 程序截图

![https://you2php.github.io/img/11.png](https://you2php.github.io/img/11.png)
![https://you2php.github.io/img/22.png](https://you2php.github.io/img/22.png)
![https://you2php.github.io/img/33.png](https://you2php.github.io/img/33.png)
![https://you2php.github.io/img/55.png](https://you2php.github.io/img/55.png)
请在遵守当地相关法律法规的前提下使用本项目

本人拒绝为任何商业或非法目的提供任何技术支持

本项目仅为科研人员更方便地学习知识而创建, 请勿大范围传播



# ---简介---

使用You2PHP的成本非常低，只需要一个支持PHP环境的虚拟海外主机，上传代码简单设置即可立即使用。无论您使用的是虚拟主机，还是VPS，上传即可使用，无需数据库！

You2PHP对接谷歌官方APi，实现了视频/频道搜索、视频在线播放 、频道/类别内容预览、视频下载等功能、浏览这些内容不需要您的设备上安装任何软件。

You2PHP采用GPL开源协议发布，你可以自由的使用和修改代码，随时随地，访问一个URL即可观看全球视频。

You2PHP支持一些基础功能：

视频搜索
频道搜索
频道&分类内容浏览
支持多种格式视频下载
支持视频分辨率切换，支持720P高清视频
支持字幕切换
视频代理工作原理：
You2PHP脚本读取谷歌服务器上的视频并一块一块的写入到你的虚拟主机/服务器内存中，然后转发给您的浏览器，你的虚拟主机/服务器起到了一个中转跳板的作，巧妙的避开了G夫W的拦截，因此可以支持大于虚拟主机空间的视频。

获取 Youtube API
You2PHP利用API获取数据，在安装You2PHP脚本之前，需要您申请一个YouTube Data API的密钥，You2PHP获取的所有内容都是通过这个API进行请求。YouTube Data API是谷歌提供的免费API，申请不需要您支付任何费用。

YouTube Data API申请教程：
0.请确保你的浏览器能打开Google，先注册一个Google账户，(注册地址：https://accounts.google.com/SignUp)如果您已经有了google账户，直接登陆即可。

1.打开https://console.developers.google.com/

2.打开此链接之后 ，若弹出服务条款更新窗口，全部选 是 ，接着点击 接受 。如果没有弹出此窗口可以忽略并进行下一步。



3.点击顶部 选择项目。

4.点击 + 图标创建一个新项目

5.项目名称使用默认的即可。当然也可以填写自定义的名称。

6.等待30秒左右，待创建完成之后，点击顶部 选择项目。找到您刚创建的项目，点 打开。

7.点击 启用 API 和服务。

8.在页面左侧下拉列表中找到 YouTube 。

9.选择YouTube Data API。并且启用。

10.点击创建凭据

11.您使用的是哪个 API？凭据种类选 YouTube Data API v3，您从哪里调用 API？ 选 网页服务器，您要访问哪些数据？选公开数据
接着点 我需要哪些凭据？

12.复制您的API密钥， 点击完成。

到这里Youtube API已经申请完成了，接着就可以使用这个密钥安装You2PHP了。



	
安装 You2PHP
本程序比较注重自己动手解决问题，伸手党请勿使用。你需要具备网站搭建知识，如代码修改、域名/空间购买与获取、域名绑定、FTP/程序上传等。对于不懂网站搭建的新手请您先通过搜索引擎自学。

本程序对虚拟主机要求并不高，空间支持Curl扩展即可，现在市场上售卖的虚拟主机基本都支持Curl扩展。

如果您没有虚拟主机建议您使用heroku部署You2PHP，或者申请免费空间使用。一般免费空间也支持CURL扩展，请谷歌一下"Free hosting"

You2PHP安装步骤：
1.下载You2PHP源码，将Zip源码包解压并上传到您的空间根目录或某个子目录下。

2.打开浏览器，然后在浏览器的地址栏输入您站点的域名加上/install.php，程序将进入安装页面。
例如：假设您的域名是example.com，安装目录为根目录，那么只要在浏览器地址栏输入http://example.com/install.php就可以开始安装系统了。若记住要把example.com换成您的域名哦，安装在根目录需要在域名后面加上路径（http://example.com/test）！
输入访问地址后出来的第一个页面如下：
这是一个使用协议页，您必须仔细阅读后并同意协议就可以进入下一步安装界面。

3.接着会出现如下页面：

这是一个运行环境检测页面，如果您发现有某项不支持，那么请重新设置您的WEB环境以符合系统需求，并重新执行安装。

如果您的主机环境符合所有条件，那么您可以点击下一步继续。

4.接着设置一些基本信息：

Youtube API V3 KEY：填您申请的Youtube API密钥
国家代码：这个填一个ISO3166标准的国际代码，默认建议填HK,一般为两位英文字母（如 台湾=TW，日本=JP）长度为2位。所填国家需要Youtube支持（可以从Youtube页面位置列表中看到），切记不能填CN，填CN或其他不支持代码将导致程序报错。
网站名字：为你的站点起一个名字，主要显示在浏览器头部title标签之间。
站点名字：页面将显示这个名字
加/解密密钥：这个填一个随机无序的字符串(夹杂各种符号数字)，作为加密KEY，加密一些外链URL。
你的邮箱：建议填写国外邮箱：gmail yahoo等！用于接收版权内容投诉。
请完整并且正确填写每一项内容后点继续，然后系统自动创建配置文件。

当你看到这样的提示，说明您的站点已经全部安装完毕！您可以开始尽情的观看全球视频！

5.好了，安装已经全部完成，您是不是已经很激动了，让我们打开站点首页看看吧：



疑难解答
问：You2PHP支持多用户同时在线观看吗？

答：支持几个人，但不支持很多人！这个脚本不支持很多人同时观看。无法搭建类似（优酷/腾讯视频）一样的大型视频网站，最多支持几个人同时观看(视服务器配置而定)。

如需提问请移步至Github项目页面发Issues https://github.com/You2php/you2php/issues

站点加锁
如果不想让您的You2PHP站点让其他人访问，可以对站点使用密码保护方法——使用htpasswd文件来实现。访问页面之后会弹出一个输入框，需要输入正确的用户名和密码才能浏览网页上的内容，否则会出错。同时搜索引擎无法收录!

1.首先，需要创建一个名为.htpasswd的文件， 将这个.htpasswd文件存放You2PHP的安装目录下。这个文件用于存储用户名和加密后的密码。比如用户名为admin，密码为123456，那么在.htpasswd文件中的内容可能就是这样的：

admin:9dKtKHPyz51Vs

用户名后紧跟的是密码，用:隔开。而且密码是加密后的密文。上传这个.htpasswd文件You2PHP的安装目录下。有一个在线生成.htpasswd文件的网站：http://www.htaccesstools.com/htpasswd-generator
通过这个地址可以生成加密后的密码。

2.创建一个新的.htaccess文件，将这个.htaccess文件存放You2PHP的安装目录下。并编辑这个文件，写入如下内容：

AuthName "Restricted Area"
AuthType Basic
AuthUserFile /home/hosting/public_html/.htpasswd
AuthGroupFile /dev/null
require valid-user

注意，需要把AuthUserFile后面/home/hosting/public_html/改成您的You2PHP站点绝对安装路径（如果装在子目录，那么应该加上子目录路径，如 /home/hosting/public_html/youtube）

3.现在打开您的You2PHP站点，会弹出一个这样的框框，需要填写正确的用户名和密码才能浏览！可以通过修改.htpasswd文件修改密码。



在 Heroku 部署 You2PHP
如果您没有虚拟主机或服务器，也可以使用Heroku部署You2PHP

请访问https://github.com/You2php/you2php-heroku 看README.md说明



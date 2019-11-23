# C-
学习过程中的C语言小代码

下面列出 120 多个项目构思，根据主题分成了 10 个分类。

文本操作
逆转字符串--输入一个字符串，将其逆转并输出。
拉丁猪文字游戏--这是一个英语语言游戏。基本规则是将一个英语单词的第一个辅音音素的字母移动到词尾并且加上后缀-ay（譬如"banana"会变成"anana-bay"）。可以在维基百科上了解更多内容。
统计元音字母--输入一个字符串，统计处其中元音字母的数量。更复杂点的话统计出每个元音字母的数量。
判断是否为回文--判断用户输入的字符串是否为回文。回文是指正反拼写形式都是一样的词，譬如"racecar"。
统计字符串中的单词数目--统计字符串中单词的数目，更复杂的话从一个文本中读出字符串并生成单词数目统计结果。
文本编辑器--记事本类型的应用，可以打开、编辑、保存文本文档。可以增加单词高亮和其它的一些特性。
RSS源创建器--可以从其它来源读取文本并将其以RSS或者Atom的格式发布出去。
实时股价--可以查询股票当前价格。用户可以设定数据刷新频率，程序会用绿色和红色的箭头表示股价走势。
访客留言簿/日志--允许人们添加评论或者日记，可以设置开启/关闭评论，并且可以记录下每一条目的时间。也可以做成喊话器。
新闻和比分播报器--一个桌面应用，可以从网上收集新闻和比赛分数，将结果在屏幕上滚动播出。
占星罗盘--用占星术来预测每天的运程。
密码短信--可以将数据加密解密，并能将其发送给朋友。
帮你挑礼物--输入一堆你可能会送的礼物，当有人过生日时，该程序会随机选择一样礼物。也可以加上一个额外功能，可以告知哪里可以弄到这个礼物。
HTML生成器--将 TEXT 文档转换成HTML文件，对制作网页HTML文档很有用。
CD-Key生成器--利用某种算法生成一个唯一的key。软件开发者可以用它来作为软件的激活器。
正则表达式查询工具--用户可以输入一段文本，在另外的控件里输入一个正则表达式。运行以后会返回匹配的内容或者正则表达式中的错误。
网络FTP工具--与远程网络服务器交互文件。
原子钟校时--从网上同步原子钟时间。全世界有很多原子钟，可以把它们都列出来。
聊天应用（IRC或者MSN风格的）--像IRC那样的聊天室软件或者MSN那样的实时聊天软件。更复杂一点的话，可以为聊天制定一套你自己的传输协议。
获取当前天气--获取某个地区当前的天气情况。
P2P文件共享应用--像LimeWire、FrostWire、Bearshare或者torrent风格的应用。
端口扫描器--输入某个ip地址和端口区间，程序会逐个尝试区间内的端口，如果能成功连接的话就将该端口标记为open。
邮件检查工具（POP3/IMAP）--用户输入一些账号信息，包括服务器、ip、协议类型（POP3或者IMAP），应用每隔一段时间就会检查下该账号下的邮箱。
数据包嗅探器--侦测电脑上进出的数据包，获取诸如目的地和大小之类的信息。
IP注册地查询--输入ip地址，查询该ip是在哪注册的。
Whois查询工具--输入一个ip或者主机地址，通过whois查询并将结果返回。
邮编查询--输入邮编，返回使用该邮编的地区名称。
远程登入--远程登入桌面类型的应用，可以查看和控制远程电脑（假如你已经获得权限）。可能需要你自己的网络和两台电脑来进行测试。
网站定时检查器--每隔一段时间或者在预定的时间尝试连接某个网站或者服务器，来检查它是否可以连上，如果连不上了会通过邮件或者桌面通知来告知你。
小型网页服务器--简易版的网页服务器，可以存放包含Javascript和其它形式代码的HTML文件。复杂一点的话可以尝试流媒体视频、创建一种服务器端语言或者其它类型的流媒体。
网络蜘蛛--一个可以自动执行网页上各种任务的程序，任务包括网站检查、页面抓取、数据摘要以及网络邮务。
类产品库存管理--创建一个管理产品库存的应用。建立一个产品类，包含价格、id、库存数量。然后建立一个库存类，记录各种产品并能计算库存的总价值。
电影商店--管理录像带租借，记录借出时间、到期时间、逾期费用。复杂一点可以生成逾期用户的账号报告。
航空/酒店预订系统--创建一套预订航班或酒店的预订系统。不同的航班座位和酒店房间收费不一样。譬如头等舱要比经济舱贵。带阁楼的套间要更贵些。记录下何时有空房可供预订。
学生成绩管理器--记录一个班级的学生（创建一个Student类，记录他们的名字、平均分和考试分数）和他们的成绩等级。根据学生的测验和作业的分数计算出平均分和成绩等级。复杂一点可以将数据画在贝尔曲线上。
银行账户管家--创建一个名为"Account"的抽象类，有三个为"CheckingAccount"、"SavingsAccount"和"BusinessAccount"的子类。通过类似ATM的程序来管理这些账户的借贷。
馆藏目录--创建一个图书类，记录书名、页数、国际标准书号、是否借出。用它来管理各种书籍，允许用户进行借出和归还操作。复杂一点的话，可以生成逾期图书和逾期费用的报告。也可以让用户进行预约操作。
线程处理下载进度条--创建一个表示下载进度的进度条。进度条由独立的线程操作，通过委托来和主线程进行通讯。
下载管理器--允许程序同时下载数个文件，每个都用单独的线程进行背景下载。主线程会关注下载进度并且在下载完成时通知用户。
聊天软件（远程聊天）--做一个聊天软件，允许你通过ip直接连接到另一台电脑，也允许你的"服务器"程序处理多个请求连接。
批量缩略图生成器--在进行图片转换的处理时会需要很多时间，尤其是图片很大时。做一个图片处理程序，能让你在做其它事的时候在后台线程里将数百张图片转换成某个大小的图片。复杂一点的话可以用一个线程来缩放，用另一个线程来为缩略图重命名。

Web应用
所见即所得编辑器--创建一个在线编辑器，允许用户移动元素、创建表格、书写文本、设置颜色，而用户不必懂HTML。就像Dreamweaver或者FrontPage。如果需要例子的话，可以参看DIC。
分页浏览器--创建一个可以分页的小型网页浏览器，可以同时浏览几个网页。简化一点的话不要考虑Javascript或者其它客户端代码。
文件下载器--该程序可以从网页上下载各种资源，包括视频和其它文件。用于有很多下载链接的网页。
远程登录--创建一个远程登录的应用，可以通过网络登录服务器并能执行一些基本命令。
在线白板--做一个在线白板程序，你和朋友们可以一起在白板上进行一些操作，画图、写字等等。
带宽监视器--这个小工具可以记录你已经在网上上传和下载多少数据流量了。可以试着做份报告或者图表来展示各时段的使用情况。
书签搜集管理器--该程序可以让用户上传书签并将它们排序，去掉重复的，并能生成书签文件以供Firefox/IE/Safari等使用。复杂一点的话可以试着将书签整理进不同的文件夹。
密码保险箱--用来记录各种密码，并且将它们加密，这样别人就看不到了。
iGoogle媒体播放器小部件--做一个iGoogle小部件，可以用来播放本地音乐列表，也可以每天分享一首歌。也许还可以让别人看到你最近听了些什么歌。
基于文本的游戏--做一个像Utopia那样的文本RPG，游戏中，你可以创建一个文明、收集资源、共铸联盟、施放法术、回合制系统。看看是否能够统一王国。
定时自动登录--做一个程序可以在预定的时间登录进某个指定的网页并且执行特定的动作，然后在登出。可以用来检查邮箱、发布常规内容、为其它程序获取信息。
电子卡片生成器--可以让用户制作自己的电子卡片并发送给其他人。可以使用flash也可以不用。可以使用图片库，也可以加上深刻的格言警句。
内容管理系统--像Joomala、Drupal、PHP Nuke这样的内容管理系统。从简单的做起，慢慢增加其它功能。
模板制作器--该网站应用允许用户输入各种颜色代码、元素、尺寸，来为PHPBB、Invision Board、MySpace之类的应用创建模板文件。
验证码生成器--应该在登录时见过有数字有字母的验证码图片吧？这可以防止自动登录和垃圾广告。试着自己做一个，如果使用PHP的话，看下GD的图片函数。

文件
试卷生成器--该程序可以从文件中随机挑选出不同的题目生成一份试卷。每份试卷可以不一样，通过读取答案来给打分。
快速启动--该工具可以添加各个程序的小图标，点击小图标就可以运行程序。和Windows的快速启动类似。
文件管理器--做一个文件管理器，要加些新特性，更佳的搜索功能、新图标、新外观。
文件记录排序工具--从文件中读取记录，将其排序并写回文件中。允许用户选择排序风格以及排序关键字。
生成财务交易文件并且算出平均值--将财务交易读进文件，按照账户分类、算出各项目的总量或平均值、理清各账户的借贷数据。
Zip文件生成器--用户输入不同文件夹的文件，也许还包括其他电脑中的文件，然后程序将这些文件打包成zip文件。复杂一点的话，打包时对这些文件进行压缩。
PDF生成器--从txt、html或其它文件中读取数据生成PDF文件。可以做成一个网页服务，用户上传文件，返回一个pdf版本。
批量文件命名器--程序批量处理一些文件，将根据用户提供的过滤器为它们重命名。譬如用户输入的过滤器为myimage###.jpg，那么会生成至少包含3位数的文件名，譬如myimage001.jpg、myimage145.jpg，甚至是myimage1987.jpg，因为1987也满足了至少包含3位数的条件。
MP3标签生成器--修改MP3文件的id3v1标签。还可以试着在MP3文件的头部加入id3v2的标签，譬如album art标签。
日志文件生成器--该程序可以记录指定事件的日志。譬如程序做了什么、系统在干什么、文件什么时候被修改了。
Excel分页输出器--做一个在线程序，可以读取文件内容生成一个excel分页。可以通过CVS或者其它文件格式来做。复杂一点的话看看是否能创建公式字段。
RPG角色属性生成器--做一个程序来给RPG角色随机分配属性点数，可以由用户制定一些分配规则。可以生成职业、性别、力量/魔法/敏捷点数、额外能力或者贸易技能。把结果保存成文件，这样跑团的时候地下城主可以把它打印出来。
文件复制工具--该工具可以批量处理文件复制和备份操作。

数据库
SQL查询分析器--该工具可以让用户输入一条查询命令，让其运行于本地数据库中。尽量让它运行得更高效。
远程SQL工具--该工具能让你通过网络在远程服务器上执行查询操作。它能接收远程主机地址、验证用户名和密码、执行查询并返回结果。
卡片整理器--创建一个在线应用，用来记录搜集到的卡片。可以让用户输入整套卡片，查看哪些已经有了，哪些还需要搜集。要增加复杂度的话，还可以让用户知道还差多少可以完成，或者已经收集卡片的价值。
报告生成器--该工具可以根据数据库中的表格生成一份报告。譬如根据订单表格生成销售报告。
数据库备份脚本制作器--该程序可以读取数据库的对象、关系、记录和步骤，生成一个sql文件，该文件可以导入另一个数据库或者作为备份文件。
备忘录--该程序可以让用户设置一个日期和某个事件的时间、事件备注并将它们放到日历上。用户可以查看日历、搜索特定的事件。复杂一点的话，可以让用户设置重复发生的事件，譬如每天、每周、每月、每年等等。
预算记录器--该程序可以记录家庭预算。用户可以添加支出、收入，计算一段时间内的收入和支出。复杂一点的话，让用户指定一个时间段，显示该时间段内的家庭收支情况。
电话簿--记录各种联系人和他们的号码、邮箱、备注。复杂一点的话可以让用户连上网将电话簿发布到设置好的网站上。
电视节目记录器--你是否有不想错过的电视节目？但没有录像机或者想之后能找到该电视节目然后录下来，那么可以做个程序寻找各种在线电视导航网站，记录下电视节目名称、播放时间、播放频道，存在数据库中。数据库或者网站到时就会发邮件提醒你，节目就快在某个频道开始了。
旅行计划系统--该系统可以让用户管理旅行路线，记录下航班和酒店安排、感兴趣的地方、预算和时间表。
实体关系图生成器--该程序可以让用户整合实体关系图，并将其保存起来，也可以用它来生成一些基础SQL语句。
数据库翻译器（MySQL<->SQL Server）--该工具可以从数据库A读取数据，生成数据库B使用的SQL语句，将数据存入数据库B。比较常用的是SQL Server和Oracle使用的MySQL服务器。
BBS论坛--为你和小伙伴们做一个论坛，可以发帖、管理、分享想法和构思。

图像和多媒体
幻灯片--做一个以幻灯片形式显示各种图片的程序。为了增加难度可以做些额外的效果，譬如渐进检出、星型擦除、窗口渐隐。
思维导图--允许用户记录下各种构思并且快速地进行头脑风暴将这些构思整合到一张思维导图中。越快越好，因此要让用户能迅速地写下构思，然后将其拖到可视的导图中去，将构思之间的关系展现出来。
导入图片并存成灰度图--该工具将图片上的彩色除尽并保存。可以增加对比度调整、色化等额外功能以增加复杂度。
在线流媒体视频--试着自己做一个在线流媒体视频播放器。
MP3播放器（以及其他格式的音乐播放器）--该小程序用来播放你最爱的音乐文件。复杂一点的话看看能否加个播放列表功能和均衡器。
批量图片处理--该程序可以将一个文件夹内的图片进行统一的处理，譬如降低图片色调、转换格式或者修改文件属性。还可以尝试给图片增加标签。
CD烧录器--可以轻松烧录CD的工具。
YouTube下载器--可以从Youtube.com上下载视频到硬盘中，要支持包括FLV和AVI在内的文件格式。
墙纸管理工具--做一个管理墙纸的程序，可以定时更换刷新墙纸，也可以针对分辨率进行缩放。
截屏程序--做一个可以截屏的工具，复杂一点可以增加一个转发邮件的功能。
图片浏览器--该程序可以查看电脑上各种格式的图片，譬如PNG、GIF、JPG、BMP、TIFF等等。
交通信号灯--试着做一个交通信号灯并且把它放到可以互动的场景中。不要让汽车闯红灯或者撞到其它车。
MP3-WAV转换器--MP3格式本质上就是压缩版的WAV。试着将MP3转换成WAV格式以供可以处理WAV格式的程序使用。请记住1MB的MP3大约等于10MB的WAV。
签名生成器--是否在网上见过有人的留言后面有条生成的签名？试着做个程序让用户可以指定背景、文字、颜色和对齐方式来定制一个签名档。
屏保--电脑空闲时会运行的屏保程序。简单版的可以使用一些标准图片，复杂版的可以做出能在屏幕上转来转去的3D物体。
水印--你是否想保护你图片的版权？在图片上加上标志或者文字，这样别人就不能轻易地从你网站上盗图了。做一个程序来给你的图片加上水印吧。
海龟图--创建一个20*20的格子，用命令让一只海龟在格子上画线。可以前进、左转、右转，拿起或放下笔等等。复杂一点的话，允许程序从文件中读取命令列表。可以在网上了解到更多关于"海龟图"的信息。

游戏
战船--创建两块游戏面板，玩家各占一边，在上面放置一些战船，玩家看不到对方的面板。每艘船都占几个格子，玩家轮流攻击某个格子，如果格子上有船，那就命中目标，否则就是未命中。当一艘船所占的所有格子都被攻击命中了，那么船就被击沉。谁先将对方战船全部击沉就获胜。
象棋跳棋--象棋或者跳棋游戏。可以试着做成可以联网玩，用图形用户界面来实现悔棋、保存走棋过程并且可以回放。
刽子手--从文件中随机选择一个单词，让玩家猜单词中的字母。旁边是一幅隐藏的行绞刑的画，猜错一个单词，画就显示出一部分。画全部显示出来时还没能猜全的话玩家就输了。
填字游戏--创建一个填字游戏，并为每个词提供一个提示信息，让玩家填上所有正确的单词。
青蛙跳--让青蛙跳过河或者马路，过河的话要跳在顺流而下速度各异的木头或者睡莲叶子上，过马路的话要避开速度各异的车子。

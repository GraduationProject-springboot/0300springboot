# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0300springboot网上团购系统设计与实现

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 第1章 绪论
## 1.1 研究背景
互联网时代不仅仅是通过各种各样的电脑进行网络连接的时代，也包含了移动终端连接互联网进行复杂处理的一些事情。传统的互联网时代一般泛指就是PC端，也就是电脑互联网时代，但是最近几十年，是移动互联网时代，是向下一步互联网时代过度的一个重要时代，下一个互联网时代叫物联网，而移动互联网就是一个风口，是当前社会的主流风向。目前移动互联网大行其道，人人都手中拿着智能机，手机手机，手不离机，如果开发一个用在手机上的程序软件，那是多么的符合潮流，符合管理者和客户的理想。本次就是开发网上团购系统有管理员和用户两个角色。管理员功能有个人中心，用户管理，商品类别管理，团购商品管理，订单管理，系统管理。用户可以注册登录，查看公告信息，对可以团购的商品进行团购操作，把团购商品加入到购物车里，支付后变成订单信息。
## 1.2 研究现状
当微软操作系统占领了多半江山，目前不分年龄和种族，使用频率最高，覆盖面积最广。使用人群使用的大多数都是微软系统。而微软又不遗余力的更新Windows版本，从微软对Windows的市场定位来讲，Windows的未来不仅仅是一个操作系统，而是让所有人都拥抱Windows，建立一个属于Windows的互联网生态圈。目前各大行业，各种类型的软件阵地转移到了Windows平台上，包含一些带商城的免费管理系统，或者一些带广告的免费应用，还有好多游戏之类的应用。尤其是经过疫情涌现的互联网办公，学校的互联网教学等，都不断的刷新人们对于互联网的认知。
## 1.3 目的和意义
从经济成本考虑，手机的价格比较亲民，对于不是必须在电脑上办公的人员来讲，手机上如果能解决事情就更方便了。

从使用便利角度上讲，用手机上的应用处理业务，不用考虑网线是否存在，不用考虑位置是否变化，依托无处不在的手机信号就可以在任何有信号的地方处理事务，这是多么的方便和使用，不限制时间，不限制地点，高山平原山谷都可以作为使用的地点而不影响使用的效果。

从操作角度上讲，手机的操作先天性的高于电脑的操作，因为电脑适合处理复杂的操作，而手机就是为了简化操作而生的，方便高效操作简单。

此次开发这个网上团购系统，不仅仅满足用户的需要，也能跟上时代的发展风向，从技术的角度还是用户的角度上进行开发都是很有意义的。
## 1.4 论文研究内容
论文设计的结构也是依照程序开发的流程进展的，也涉及到功能需求分析，功能设计与实现，程序测试等流程。

绪论：讲解课题的背景与意义，展示论文结构。

程序开发技术：讲解程序运用到的工具与技术知识。

系统分析：讲解程序的功能需求与开发可行性问题。

系统设计：讲解程序的功能与数据库的设计。

系统实现：讲解程序功能与界面实现。

系统测试：讲解程序的功能测试。
# 第2章 程序开发技术
## 2.1 Mysql数据库
为了更容易理解Mysql数据库，接下来就对其具备的主要特征进行描述。

（1）首选Mysql数据库也是为了节省开发资金，因为网络上对Mysql的源码都已进行了公开展示，开发者根据程序开发需要可以进行下载，并做一些改动就可以使用在程序中，可以推动开发者开发此程序的开发进度。

（2）SQL数据语言在Mysql里面也同样适用

（3）Mysql不仅可以支持多种编程语言，比如在校期间学到的C语言，Java语言，以及课后接触的PHP语言，C++语言等编程语言，它都能很好的支持，而且Mysql的安装与使用还不挑剔使用平台。

（4）Mysql可以支持具有千万条数据记录的数据库，电脑操作系统在进行首次安装或者是重装时，可以根据需要选择安装32位或64位操作系统，这两种操作系统对表文件的支持力度不一样，32位的操作系统最多可以存放4GB的表文件，64位操作系统最多可以存放8TB的表文件。

（5）Mysql数据库可以通过GPL协议进行个性化定制，需要开发者自己对数据库的源代码进行修改，以此开发出属于自己的Mysql。
## 2.2 Java语言
程序开发语言有很多，但是截至目前，Java语言在IT领域内，仍然是最被认可，以及被广泛运用的编写语言之一，因此在选择此程序的编写语言上，果断选择这门编程语言进行程序开发。可以说经过了这么多年的发展，Java语言不仅在Web开发领域有了突出性贡献，而且在大数据开发领域以及Windows开发领域都得到了广泛运用。由于Java语言拥有较强的扩展性能，并且表现出的稳定性能，让其成为大型后端系统开发语言首选，现如今，Java语言也成为了一种常用的互联网平台的解决方案。

作为一种源码在网络上开源的面向对象的程序开发Java语言，由它开发完成的程序是不可能直接运行在各大平台的，Java程序的运行，需要在操作平台上配置其运行的环境，包括数据库软件与Java程序开发软件等工具的安装与配置。在Win7，Win10或其它操作平台上配置Java程序运行环境，只要环境配置成功，Java程序都可以运行起来。
## 2.3 Spring Boot框架简介
Spring Boot是由Pivotal团队提供的全新[框架](https://baike.baidu.com/item/%E6%A1%86%E6%9E%B6/1212667)，其设计目的是用来[简化](https://baike.baidu.com/item/%E7%AE%80%E5%8C%96/3374416)新[Spring](https://baike.baidu.com/item/Spring/85061)应用的初始搭建以及开发过程。该框架使用了特定的方式来进行配置，从而使开发人员不再需要定义样板化的配置。通过这种方式，Spring Boot致力于在蓬勃发展的快速应用开发领域(rapid application development)成为领导者。

SpringBoot可以与经典的Java开发工具一起使用或者作为命令行工具安装。无论如何，需要JavaSDK1.6或者更高版本，本项目用到的是JDK1.8版本。
## 2.4 VUE框架  
Vue.js（读音 /vjuː/, 类似于 view） 是一套构建用户界面的渐进式框架。

Vue 只关注视图层， 采用自底向上增量开发的设计。

Vue 的目标是通过尽可能简单的 API 实现响应的数据绑定和组合的视图组件。
## 2.5 HTML5技术  
HTML5 是下一代 HTML 标准。

HTML , HTML 4.01的上一个版本诞生于 1999 年。自从那以后，Web 世界已经经历了巨变。

HTML5 仍处于完善之中。然而，大部分现代浏览器已经具备了某些 HTML5 支持。

HTML5 是 W3C 与 WHATWG 合作的结果,WHATWG 指 Web Hypertext Application Technology Working Group。

WHATWG 致力于 web 表单和应用程序，而 W3C 专注于 XHTML 2.0。在 2006 年，双方决定进行合作，来创建一个新版本的 HTML。

HTML5 中的一些有趣的新特性：

用于绘画的 canvas 元素

用于媒介回放的 video 和 audio 元素

对本地离线存储的更好的支持

新的特殊内容元素，比如 article、footer、header、nav、section

新的表单控件，比如 calendar、date、time、email、url、search

# 第3章 系统分析
在进行系统分析之前，需要从网络上或者是图书馆的开发类书籍中收集大量的资料，因为这个环节也是帮助即将开发的程序软件制定一套最优的方案，一旦确定了程序软件需要具备的功能，就意味着接下来的工作和任务都是围绕着这个方案执行的，所以系统分析需要对程序功能反复进行思考和研究。
## 3.1可行性分析
开发一款系统软件之前，用户都会思考这个软件程序值不值得去开发，把开发软件过程中可能涉及到的问题罗列出来，并一个个分析解决，以此来确定开发这款程序软件是否有必要，这样的分析方法也能帮助用户降低损失，不至于开发者开发进度进行到一半之后，突然遇到问题就放弃对软件的开发，到那时，资金损失，人力投入等方面就损耗太大了。
### 3.1.1技术可行性分析
此次开发程序使用到的开发工具有：Mysql等工具，使用的开发语言是Java，选择的开发工具和开发语言都是在大学课堂接触并学习过，后期因为自己也比较感兴趣，所以也通过网络渠道，或借助图书馆的开发类书籍进行过软件开发知识的系统学习，让自己有了一定的知识积累，加上自己在校期间也独立开发过一些软件作品，也积累了一定的开发经验，所以这次毕设作品的制作在技术上无须担忧过多。
### 3.1.2经济可行性分析
目前的信息时代，对信息的管理趋于高效化，便捷化，这也是计算机大力普及所带来的便利，此程序软件在设备选用上，依靠的是比较大众的电脑设备，对电脑的配置没有过多要求，一般学校的计算机机房的电脑都可以满足程序开发需求，另外，开发出此款程序，让信息处理变得高效率，其所带来的高效益是远超程序开发的低成本的，因此程序开发的资金投入是可以忽略不计的。
### 3.1.3操作可行性分析
程序软件的操作界面是符合大众审美的需求，功能模块的布局也是类似于社会上同种类型的软件，因此使用者操作该软件可以无需培训就上手。加上现在计算机入驻各家各户，大部分人的计算机操作水平都比较高，这样的局面也表明开发出来的程序在操作性问题上也是不用担心的。

综合上面的可行性论证，基本可以确定程序开发完全可行。
## 3.2系统运行环境
程序经过编码可以实现对程序设计的功能。但是编码实现时需要一定的配置环境，包括了电脑上的硬件环境，也包括在电脑操作系统上安装的软件环境。

硬件环境：一台可以正常使用并能够上网的笔记本或者是电脑，电脑内存最低要求4个G，电脑的中央处理器可以配置i5CPU。

软件环境：运用的微软操作系统是比较稳定的win7旗舰版系统，采用比较熟练的360安全浏览器，并在此系统上通过浏览器下载安装好MYSQL软件等。
## 3.3系统流程分析
分析程序的流程，涉及到程序的整体操作流程，通过分析与设计，绘制的程序操作流程图见下图。此程序为了确保安全，会让使用者通过登录模块验证信息，符合要求的使用者才有权限操作程序。

![](/md/blog.001.png)

图3-1 程序操作流程图

程序处理数据会涉及到数据的录入环节，绘制的添加流程见下图。程序录入数据过程中，始终与数据库保持同步。

![](/md/blog.002.png)

图3-2 信息添加流程图

程序里面的数据也会出现错误，因此就有相应的修改数据的功能，绘制的程序修改流程见下图。此过程也是跟后台数据库进行数据同步显示。

![](/md/blog.003.png)

图3-3信息修改流程图

程序数据存放于数据仓库，有时也会涉及到数据删除，此过程对应的流程图见下图。数据信息被删除之后，数据库里面也就没有了该数据信息了。

![](/md/blog.004.png)

图3-4 信息删除流程图

第4章 系统设计
## 4.1 系统设计的原则
在系统设计过程中，也需要遵循相应的设计原则，这些设计原则可以帮助设计者在短时间内设计出符合设计规范的设计方案。设计原则主要有可靠性，安全性，可定制化，可扩展性，可维护性，可升级性以及客户体验等原则。下面就对这些原则进行简要阐述。

可靠性：一个软件是否可靠决定了其是否被用户使用，设计不可靠的软件，用户很容易就遗弃；

安全性：程序软件承担了信息的保存与管理等事务，安全性不足的软件会导致使用者承担巨大的损失；所以系统安全也是需要考虑进入的；

可定制化：市场环境从来都不是一直固定不变，面对客户群体的改变，以及使用环境的改变，市场需求的改变等因素，程序软件也要易于调整以适应各种变化；

可扩展性：程序软件在运行使用期间，也需要及时引进当下的新技术来进行系统优化，主要就是在系统功能层面，系统性能层面上进行相应的扩展，只有这样才能让系统在实际生活中继续占有市场；

可维护性：程序软件的维护需要一定量的资金，不管是排除现有程序错误，还是变更软件的现有需求，都需要在软件技术上投入一定资金，所以易于维护的软件程序就可以降低技术层面的资金消耗；

可升级性：程序软件的投入使用，会面临用户数量增多的情况，用户对软件的使用率也会提升，所以系统面临这种情况，仍然需要通过升级保持性能的合理，这样才能够适应市场；

客户体验：设计出来的程序软件在界面上不能够太复杂，要遵循界面设计的原理设计出简单，方便操作的功能操作界面，让用户易于接受软件，并乐于使用软件提供的功能。
## 4.2 功能结构设计
在管理员功能模块确定下来的基础上，对管理员各个功能进行设计，确定管理员功能的详细模块。绘制的管理员功能结构见下图。管理员功能有个人中心，用户管理，商品类别管理，团购商品信息管理，订单管理，系统管理。

![](/md/blog.005.png)

图4-2 管理员功能结构图
## 4.3 数据库设计
与功能结构设计一样，数据库设计也是程序开发不可避免的设计环节，数据库设计最主要的目的就是帮助运行程序存储相应的数据信息。数据库设计包含的内容有数据表结构的设计，也包含了数据库E-R图的设计。
### 4.3.1 数据库E-R图
在绘制E-R图之前，先要找出数据库的实体，明确各个实体具有的属性，比如用户信息这个实体，它具备的属性包括了用户的姓名属性，用户的密码属性，用户的创建时间属性等，所以明确了用户这个实体，以及用户实体具备的属性之后，就需要根据这些信息绘制用户实体对应的实体属性图了。绘制软件选用当下认可度高，使用范围广，操作便利的微软旗下的Visio工具。

（1）管理员实体属性图通过Visio工具绘制，绘制结果展示如下：

![](/md/blog.006.png)

图4-4 管理员实体属性图

（2）用户实体属性图通过Visio工具绘制，绘制结果展示如下：

![](/md/blog.007.png)

图4-5 用户实体属性图

（3）商品类别实体属性图通过Visio工具绘制，绘制结果展示如下：

![](/md/blog.008.png)

图4-6 商品类别实体属性图
### 4.3.2 数据库表结构
在进行这部分设计之前，需要明白和掌握数据类型以及各个数据类型的长度范围等知识，因为在一张具体的数据表中，为了方便理解，这里就举个简单的例子。比如用户信息表，这个表格的字段就是用户这个实体具备的属性，这时就需要对字段进行数据类型，以及字段长度的设置，也要设置一个主键来作为用户信息表的唯一标识。这些都是数据库表结构设计需要完成的内容。根据网上团购系统的功能设计以及数据库设计要求，展示该系统的数据表结构。 

1公告资讯表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|addtime|Date|创建时间|是|
|3|title|String|标题|是|
|4|introduction|String|简介|是|
|5|picture|String|图片|是|
|6|content|String|内容|是|
2地址表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|addtime|Date|创建时间|是|
|3|userid|Integer|用户id|是|
|4|address|String|地址|是|
|5|name|String|收货人|是|
|6|phone|String|电话|是|
|7|isdefault|String|是否默认地址[是/否]|是|
3团购商品评论表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|addtime|Date|创建时间|是|
|3|refid|Integer|关联表id|是|
|4|userid|Integer|用户id|是|
|5|nickname|String|用户名|是|
|6|content|String|评论内容|是|
|7|reply|String|回复内容|是|
4团购商品表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|addtime|Date|创建时间|是|
|3|shangpinbianhao|String|商品编号|是|
|4|shangpinmingcheng|String|商品名称|是|
|5|shangpinleibie|String|商品类别|是|
|6|pinpai|String|品牌|是|
|7|guige|String|规格|是|
|8|tupian|String|图片|是|
|9|fabushijian|date|发布时间|是|
|10|shangpinxiangqing|String|商品详情|是|
|11|clicktime|datetime|最近点击时间|是|
|12|reversetime|datetime|倒计结束时间|是|
|13|clicknum|Integer|点击次数|是|
|14|price|float|价格|是|
|15|onelimittimes|Integer|单限|是|
|16|alllimittimes|Integer|库存|是|
5用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|addtime|Date|创建时间|是|
|3|yonghuzhanghao|String|用户账号|是|
|4|mima|String|密码|是|
|5|yonghuxingming|String|用户姓名|是|
|6|xingbie|String|性别|是|
|7|yonghudianhua|String|用户电话|是|
|8|touxiang|String|头像|是|
|9|money|float|余额|是|
6订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|addtime|Date|创建时间|是|
|3|orderid|String|订单编号|是|
|4|tablename|String|商品表名|是|
|5|userid|Integer|用户id|是|
|6|goodid|Integer|商品id|是|
|7|goodname|String|商品名称|是|
|8|picture|String|商品图片|是|
|9|buynumber|Integer|购买数量|是|
|10|price|float|价格/积分|是|
|11|discountprice|float|折扣价格|是|
|12|total|float|总价格/总积分|是|
|13|discounttotal|float|折扣总价格|是|
|14|type|Integer|支付类型|是|
|15|status|String|状态|是|
|16|address|String|地址|是|
|17|tel|String|电话|是|
|18|consignee|String|收货人|是|
|19|logistics|String|物流|是|
7商品类别表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|addtime|Date|创建时间|是|
|3|shangpinleibie|String|商品类别|是|
8收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|addtime|Date|创建时间|是|
|3|userid|Integer|用户id|是|
|4|refid|Integer|收藏id|是|
|5|tablename|String|表名|是|
|6|name|String|收藏名称|是|
|7|picture|String|收藏图片|是|
|8|type|String|类型(1:收藏,21:赞,22:踩)|是|
|9|inteltype|String|推荐类型|是|
9管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|用户名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|
10购物车表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|addtime|Date|创建时间|是|
|3|tablename|String|商品表名|是|
|4|userid|Integer|用户id|是|
|5|goodid|Integer|商品id|是|
|6|goodname|String|商品名称|是|
|7|picture|String|图片|是|
|8|buynumber|Integer|购买数量|是|
|9|price|float|单价|是|
|10|discountprice|float|会员价|是|

# 第5章 系统实现
系统实现这个章节的内容主要还是展示系统的功能界面设计效果，在实现系统基本功能，比如修改，比如添加，比如删除等管理功能的同时，也显示出系统各个功能的界面实现效果，该部分内容一方面与前面提到的系统分析，系统设计的内容相呼应，另一方面也是一个实际成果的展示。
## 5.1管理员功能实现
### 5.1.1 用户管理
管理员可以对用户信息进行添加，修改，删除，查询操作。

![](/md/blog.009.png)

图5-1 用户管理页面
### 5.1.2 商品类别管理
管理员可以对商品类别信息进行添加，修改，删除，查询操作。

![](/md/blog.010.png)

图5-2 商品类别管理页面
### 5.1.3 团购商品信息管理
管理员可以对团购商品信息进行添加，修改，删除，查询操作。

![](/md/blog.011.png)

图5-3 团购商品信息管理页面
### 5.1.4 订单管理
管理员可以查看已支付订单，可以对订单进行发货。

![](/md/blog.012.png)

图5-4 订单管理页面
## 5.2 用户功能实现
### 5.2.1 团购商品信息
用户可以查看团购商品信息，可以购买和加入购物车，也可以评论和收藏。

![](/md/blog.013.png)

图5-5 团购商品信息页面
### 5.2.2 购物车
用户把图书加入到购物车里后可以在购物车里对商品数量更改和删除。

![](/md/blog.014.png)

图5-6 购物车页面
### 5.2.3 确认下单
用户在购物车里点击确认下单后到以下界面，这个界面可以对收货地址修改，可以进行支付操作。

![](/md/blog.015.png)

图5-7 确认下单页面
### 5.2.4 我的收藏
用户收藏过的团购商品信息可以在我的收藏里查看查询和删除。

![](/md/blog.016.png)

图5-8 我的收藏页面















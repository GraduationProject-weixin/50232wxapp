# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50232wxapp微信小程序BS模式的学生实习与就业管理系统设计与实现springboot

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 第1章 绪论
## 1.1 课题背景
互联网发展至今，无论是其理论还是技术都已经成熟，而且它广泛参与在社会中的方方面面。它让信息都可以通过网络传播，搭配信息管理工具可以很好地为人们提供服务。所以各行业，尤其是规模较大的企业和学校等都开始借助互联网和软件工具管理信息，传播信息，共享信息等等，以此可以增强自身实力，提高在同行业当中的竞争能力，并从各种激烈的竞争中获取发展的机会。针对高校教师成果信息管理混乱，出错率高，信息安全性差，劳动强度大，费时费力等问题，经过分析和考虑，在目前的情况下，可以引进一款学生实习与就业管理系统这样的现代化管理工具，这个工具就是解决上述问题的最好的解决方案。它不仅可以实时完成信息处理，还缩短高校教师成果信息管理流程，使其系统化和规范化。同时还可以减少工作量，节约高校教师成果信息管理需要的人力和资金。所以学生实习与就业管理系统是信息管理环节中不可缺少的工具，它对管理者来说非常重要。
## 1.2 课题意义 
现如今，信息种类变得越来越多，信息的容量也变得越来越大，这就是信息时代的标志。近些年，计算机科学发展得也越来越快，而且软件开发技术也越来越成熟，因此，在生活中的各个领域，只要存在信息管理，几乎都有计算机的影子，可以说很多行业都采用计算机的方式管理信息。信息计算机化处理相比手工操作，有着保密性强，效率高，存储空间大，成本低等诸多优点。针对高校教师成果信息管理，采用学生实习与就业管理系统可以有效管理，使信息管理能够更加科学和规范。

总之，在实际中使用学生实习与就业管理系统，其意义如下：

第一点：学生实习与就业管理系统的实际运用，可以帮助管理人员在短时间内完成信息处理工作；

第二点：通过系统页面的合理排版布局，可以更加直观的展示系统的内容，并且使用者可以随时阅读页面信息，随时操作系统提供的功能；

第三点：可以实现信息管理计算机化；

第四点：可以降低信息管理成本；
## 1.3 研究内容
对学生实习与就业管理系统设计制作，不仅需要技术支撑，也需要大量的理论研究。本文在对学生实习与就业管理系统进行介绍时，将按照如下内容进行。

第一部分：介绍学生实习与就业管理系统研究的背景意义，便于用户了解系统；

第二部分：介绍开发学生实习与就业管理系统需要搭建的环境，包括技术和工具；

第三部分：介绍用户对学生实习与就业管理系统的功能要求，以及对学生实习与就业管理系统的性能要求等；

第四部分：介绍数据库的设计方案，以及根据功能要求设计的功能结构；

第五部分：介绍通过编码最终实现的系统功能运行效果；

第六部分：介绍系统的功能测试，对系统进行综合检测，并及时解决系统出现的问题，直至系统运行正常。
# 第2章 开发环境与技术
学生实习与就业管理系统的编码实现需要搭建一定的环境和使用相应的技术，接下来的内容就是对学生实习与就业管理系统用到的技术和工具进行介绍。
## 2.1 MYSQL数据库
本课题所开发的应用程序在数据操作方面是不可预知的，是经常变动的，没有办法直接把数据写在文档里，这样不仅仅不安全，也不能实现应用程序的功能。如果要能实现应用程序所需要的数据存储功能，就避免不了要进行专业数据库存储软件的选择。基本上应用程序实现的功能不算太复杂，市面上任何一个关系型数据库软件都可以实现。参考自己的学习进度和操作习惯来讲，Oracle数据库是适合的，但是所需要的的安装软件很大，并且有好多不需要的功能都是开启的状态，十分消耗电脑资源，所以没有选择Oracle数据库，而SQL Server数据库虽然学过，但是安装的时候因为电脑上可能有其他的软件存在，经常性的出问题，而安装问题不好解决就需要重新安装操作系统，这样对已经存在的软件来讲又是一种时间上的浪费。只有MySQL数据库，安装包小，安装速度快，操作简单，哪怕安装出问题也好解决，不用重装操作系统，也不影响电脑上运行的其他软件，消耗资源也少，最重要的是在功能方面完全的符合设计需要，所以最后选择了MySQL数据库作为应用软件开发需要的数据库。
## 2.2 Java语言
Java语言发展有25年多了，在互联网行业经过这么多年的发展，还依然在市场的占有率上有半壁江山，依然受到很多程序员的喜爱，好多从业人员进行学习，随着互联网从业人员的增加，并没有降低Java语言的江湖地位，算是一个常青藤。Java语言学习很简单，当然这是针对于前辈C++来讲的，C++语言相当的强悍。Java取消了很多C++特征，比如go to这些语句，还有取消了主文件，让所有的文件都是类，类里都是数组和各种对象，还让Java自己处理各种对象的引用和回收，让开发人员只需要创建对象，使用对象，编辑代码逻辑，不需要关注性能方面，让数据的各种存储交给Java自己处理，可以花更多的时间研究应用程序之间的关系，让开发变得更专注，就像赛车的驾驶员一样，只需要了解各种车辆的性能，并且进行操作，不需要研究轱辘如何制造，这样让程序开发更加的细化。
## 2.3 微信小程序技术  
小程序并非凭空冒出来的一个概念。当微信中的 WebView 逐渐成为移动 Web 的一个重要入口时，微信就有相关的 JS API 了。

实际上，微信官方是没有对外暴露过如此调用的，此类 API 最初是提供给腾讯内部一些业务使用，很多外部开发者发现了之后，依葫芦画瓢地使用了，逐渐成为微信中网页的事实标准。2015年初，微信发布了一整套网页开发工具包，称之为 JS-SDK，开放了拍摄、录音、语音识别、二维码、地图、支付、分享、卡券等几十个API。给所有的 Web 开发者打开了一扇全新的窗户，让所有开发者都可以使用到微信的原生能力，去完成一些之前做不到或者难以做到的事情。

JS-SDK是对之前的 WeixinJSBrige 的一个包装，以及新能力的释放，并且由对内开放转为了对所有开发者开放，在很短的时间内获得了极大的关注。从数据监控来看，绝大部分在微信内传播的移动网页都使用到了相关的接口。

​JS-SDK 解决了移动网页能力不足的问题，通过暴露微信的接口使得 Web 开发者能够拥有更多的能力，然而在更多的能力之外，JS-SDK 的模式并没有解决使用移动网页遇到的体验不良的问题。用户在访问网页的时候，在浏览器开始显示之前都会有一个的白屏过程，在移动端，受限于设备性能和网络速度，白屏会更加明显。我们团队把很多技术精力放置在如何帮助平台上的Web开发者解决这个问题。因此我们设计了一个 JS-SDK 的增强版本，其中有一个重要的功能，称之为“微信 Web 资源离线存储”

​这个设计有点类似 HTML5 的 Application Cache，但在设计上规避了一些 Application Cache的不足。

​在内部测试中，我们发现 离线存储 能够解决一些问题，但对于一些复杂的页面依然会有白屏问题，例如页面加载了大量的 CSS 或者是 JavaScript 文件。​除了白屏，影响 Web 体验的问题还有缺少操作的反馈，主要表现在两个方面：页面切换的生硬和点击的迟滞感。

​微信面临的问题是如何设计一个比较好的系统，使得所有开发者在微信中都能获得比较好的体验。这个问题是之前的 JS-SDK 所处理不了的，需要一个全新的系统来完成，它需要使得所有的开发者都能做到：

快速的加载

更强大的能力

原生的体验

易用且安全的微信数据开放

高效和简单的开发

## 2.4 SpringBoot框架
在过去两三年的Spring生态圈，最让人兴奋的莫过于Spring Boot框架。或许从命名上就能看出这个框架的设计初衷：快速的启动Spring应用。因而Spring Boot应用本质上就是一个基于Spring框架的应用，它是Spring对“约定优先于配置”理念的最佳实践产物，它能够帮助开发者更快速高效地构建基于Spring生态圈的应用。

那Spring Boot有何魔法？自动配置、起步依赖、Actuator、命令行界面(CLI) 是Spring Boot最重要的4大核心特性，其中CLI是Spring Boot的可选特性，虽然它功能强大，但也引入了一套不太常规的开发模型，因而这个系列的文章仅关注其它3种特性。如文章标题，本文是这个系列的第一部分，将为你打开Spring Boot的大门，重点为你剖析其启动流程以及自动配置实现原理。要掌握这部分核心内容，理解一些Spring框架的基础知识，将会让你事半功倍。

可以把Spring IoC容器比作一间餐馆，当你来到餐馆，通常会直接招呼服务员：点菜！至于菜的原料是什么？如何用原料把菜做出来？可能你根本就不关心。IoC容器也是一样，你只需要告诉它需要某个bean，它就把对应的实例（instance）扔给你，至于这个bean是否依赖其他组件，怎样完成它的初始化，根本就不需要你关心。

作为餐馆，想要做出菜肴，得知道菜的原料和菜谱，同样地，IoC容器想要管理各个业务对象以及它们之间的依赖关系，需要通过某种途径来记录和管理这些信息。 BeanDefinition对象就承担了这个责任：容器中的每一个bean都会有一个对应的BeanDefinition实例，该实例负责保存bean对象的所有必要信息，包括bean对象的class类型、是否是抽象类、构造方法和参数、其它属性等等。当客户端向容器请求相应对象时，容器就会通过这些信息为客户端返回一个完整可用的bean实例。


## 2.5 B/S架构
B/S架构是软件行业针对C/S架构来进行区分的，用来描述浏览器与服务器之间的一种架构模式。一般选择B/S架构最主要的原因就是方便维护，当程序开发的时候，可以在本地进行测试，一般的集成开发环境都自带的有开发和一键部署，本地浏览器可以及时的看到效果，测试人员有专门的服务器，只需要部署上去即可，如果中间有问题都可以进行整改的。应用程序升级，只需要后台维护代码即可，客户方面还是用之前的浏览器进行访问，所以客户端方面是很方便的。现在市面上基本上所有的操作系统平台只要是有视窗模式的，除了命令行操作界面的窗口之外，在视窗模式都是可以安装浏览器的，所以任何带视窗模式的电脑操作系统自带的浏览器或者是其他厂家的浏览器，或者是移动端的浏览器，都可以进行访问服务器的。访问服务器占用客户端资源是很少，而且不容易出错，哪怕客户端这边出现大的问题，只需要重装系统然后再安装上浏览器即可。在程序功能和客户体验上面，选择B/S架构进行应用程序开发，是很适合当今社会的主流发展趋势的。
## 2.6 Tomcat 介绍
刚开始学习Java语言的时候，是不知道还有Tomcat这些东西的，各种语法各种输出在控制台进行输出结果，当Java网站开发的时候就不可避免的学习到了Tomcat服务器。Tomcat准确的来讲不算是服务器，可以说是微信小程序引擎或者一个容器，这些都是学术上或者原理上都比较贴切的，但是实际工作中Tomcat就是作为一个web服务器来用的，因为可以实现网站的发布和运行。因为工作原理的原因，Tomcat一般作为中小型企业和并发量并不突出的一种轻量级的服务器存在的，比如某些行业的应用系统，本身客户端就不多，需要的连接也不多，一般都用Tomcat的。Tomcat里面可以配置多个网站，配置文件后缀是config的文档，类似于XML的结构，比较清晰明了。每当Java发布新的版本的时候，Tomcat也会为了匹配Java的版本进行升级，目前Tomcat版本已经到版本10了。Tomcat标识是一只有点发黄的小猫咪，当Tomcat配置成功一般测试的时候能看到这个小猫咪就算是成功的，才能进行下一步的配置。Tomcat服务器在Java网站开发中还是挺合适的。
## 2.7 HTML简介
HTML是超文本标记语言，都是用各种声明以及对称性的的特殊符号作为标记，用以浏览器解析。HTML还有一些基本标签，比如根元素标签就是<html>，而文档元数据一般都写在了<head>标签里面，标题就是浏览器左上角的显示的网页内容，用的是<title>标签描述，<body>里是很重要的，描述的是浏览器显示的可见内容，如果想要在浏览器上面显示一些数据，那么肯定是要写在<body>标签里面的。关于定义标题或者换行以及段落，都有对应的标签。基本上各个浏览器都支持调试模式，一般都是用到了键盘上面用F12就可以看到标签形式的代码。

HTML作为一种超文本标记语言，是目前学习网站必须学习的第一门语言，要熟悉里面很多种标记，这种标记就是网页专属标记，只有这样浏览器才能解析相关信息。HTML里面包含了整整一套的标签，各种标签都有自己的功能，并且可以循环嵌套这些标签，比如一个表格里套着两个小小的表格。HTML一般文件名称的后缀都是html作为后缀，文档一般叫做web页面，里面的描述性标记语法被称为代码。
## 2.8 MyEclipse开发工具
MyEclipse是功能最全面的Java IDE。Java语言发展至今，已经与好多语言相互配合，并且各种语法都不一样，实现的效果不一样，造成现在的程序开发人员需要学习很多种语言，出现问题就解决问题，这是各种新的工具产生的一些动力。刚开始的Java需要自己安装开发环境和运行环境，然后手动新建文本，一句话一句话的进行编写，这样的功底需要极其的扎实，效率也是相当的低下，所以各种文本编辑工具就开始像雨后春笋一样的冒了出来，经过互联网的传播，大家使用后经过口碑，自然优胜略汰，大浪淘沙，到现在为止MyEclipse开发工具已经牢牢地占据了Java开发的半壁江山。MyEclipse的立足就是为了企业人员用的，企业开发讲究效率，不可能让所有的开发人员来了从电脑安装软件先开始，配置环境又需要花费太久的时间，MyEclipse就解决了这样的烦恼，只要安装了软件，各种Java程序都可以进行开发，可以对各种语法自动的进行检测，有效的提示细节处错误，并且可以在写作上面让对一些整段代码的移动复制都很便利，应用部署也是一键到位。


# 第3章 系统分析
面对即将开发的系统，进行提前的分析是必要的。这也是开发流程中必须有的环节。通常分析系统期间，主要涉及的内容包括系统开发可行性问题，对系统功能和性能的分析等问题。
## 3.1 可行性分析
在正式对需要建设的项目进行投资前，有一个比较关键的步骤是不能缺少的，那就是可行性分析。它主要从当前技术，经济等角度去评估系统的可行性，在投资决策中常常采用这种科学的方法来论证项目。
### 3.1.1 技术可行性
当前，系统开发的技术已经发展成熟，而且通过计算机网络可以获取开发工具的使用方法，以及规范化编写的模块化代码，这些知识可以帮助开发者顺利完成本系统的编码工作。
### 3.1.2 经济可行性
本系统开发期间需要配置的软件环境，可以免费通过开发类官网下载安装，需要配置的硬件设备也不需要具备很高的性能，通常网吧电脑，或学校计算机机房的电脑都符合要求。因此，从经济方面考虑，学生实习与就业管理系统开发可行。
### 3.1.3 操作可行性
学生实习与就业管理系统根据用户使用习惯进行开发，设计的界面具有统一性，并具备优秀的导航功能。所以，只要会简单操作电脑的人员，可以无压力操作学生实习与就业管理系统。

总之，从上述的论证来看，本系统可以开发。
## 3.2 系统流程
流程图这样的工具可以直观反映出系统内部的操作逻辑，可以帮助用户更好的理解系统。
### 3.2.1 操作流程
进入本系统需要访问者提供验证信息。验证合格的访问者才能获取访问资格。其具体的操作流程见下图。访问者根据登录界面设置的信息项如实填写，待信息通过验证后，访问者可以进入指定的页面享受本系统提供的服务和阅读本系统的相关信息。

![](/md/blog.001.png)

图3.1 操作流程图
### 3.2.2 登录流程
本系统的登录模块，其内部的流程见下图。主要对访问本系统的人员提供的验证信息进行逐个判断，系统面对录入错误的信息会给出提示，比如，提示账号不对，或提示密码不匹配等提示信息。总之，在登录页面填写的所有信息都符合要求，访问者就登录成功了。

![](/md/blog.002.png)

图3.2 登录流程图
### 3.2.3 删除信息流程
本系统在经常性的使用后，会产生很多失去价值的信息，因此就需要及时清理数据，腾出系统的空间。对这些数据进行清理时，其对应的流程见下图。先选中要清理的数据，通过反复确认需要清理的数据，避免操作人员误删。已经删除的数据就不会出现在系统里面。

![](/md/blog.003.png)

图3.3 删除信息流程图
### 3.2.4 添加信息流程
本系统主要用于显示信息，提供服务，其中，数据添加功能就是其中的服务之一，具体流程见下图。让操作者在信息添加的页面录入数据，待这些数据被提交检验合格后，就会在系统指定页面显示出来。

![](/md/blog.004.png)

图3.4 添加信息流程图
## 3.3 性能需求
进行需求分析，包括了根据用户实际需求制定功能，也涵盖了对即将设计的系统进行性能上的需求分析。所以一般分析系统时，一方面要分析系统功能，另一方面也要分析系统的性能。毕竟设计开发出一个好性能的系统可以确保系统的质量可靠。

接下来分析系统的性能，还要从界面友好性，系统的时间特性，系统的可靠性等方面来分析说明。

（1）系统的容量要求：对本系统完成数据处理的容量最大化进行确定。也就是确定系统处理数据的容量临界值，超过这个临界值，可能系统就运行不正常了。

（2）系统精度的要求：确定数据传输需要达到的精度值，也包括了数值计算的精度值，数据的精度值的设置等。

（3）时间特性要求：系统处理数据都有时间要求，这也是系统的时间特性。通常都会把数据处理的时间进行分析，也会设置用户请求的响应时间，还有系统在满负荷运行时可以偏离的范围数值等都需要提前分析确定。

（4）适应性要求：系统在面对系统环境的改变时，其自身适应这种变化的能力，也需要通过参数信息体现。比如说，在面对变化的需求，系统就要去适应这种变化，通过指出需要设计的过程或者是需要设计的软件来体现系统的适应性。

（5）界面友好性：除了功能上需要考虑用户需求外，在人机交互界面的设计上，也需要考虑用户的使用习惯，包括界面的布局，界面基调选择以及颜色搭配等。尽量做到用户在接受简单的培训之后，可以对系统进行独立操作。

（6）系统可靠性：对于初学者而言，很容易出现一个问题，就是设计开发的系统，因为人为的误操作出现崩溃，有些也会导致电脑死机。这样的现象也说明这种容错能力低下的系统是不可靠的。完全不能作为生活中处理信息的系统。当下，系统开发要保证可靠性，设计时，把模块化和结构化的设计理念也考虑进来。如果遇到对时效性要求比较严格的系统，也需要采取其它的措施，比如双机系统，还有磁盘阵列等方式。还有就是一个可靠性的系统，对设备的供电能力也有要求。

运行在计算机上的系统大都担负着信息处理的任务，对于它们而言，其性能要求有：完成信息查询，需要的响应时间；对终端设备的连接数量的确定；对存储数据的容量的安排；以及存储数据的可扩充的容量的设置，比如说系统存放近几个月，或者存放近几年的数据；完成报表打印数量的设置，也包括报表打印种类的设置等。

# 第4章 系统设计
一个成功设计的系统在内容上必定是丰富的，在系统外观或系统功能上必定是对用户友好的。所以为了提升系统的价值，吸引更多的访问者访问系统，以及让来访用户可以花费更多时间停留在系统上，则表明该系统设计得比较专业。
## 4.1 设计原则
本系统在设计过程中需要依照一定的设计原则进行，目的就是为了让开发的系统具备高质量，齐全完备的功能，方便简单的操作，如此才可以最大限度的满足使用者的要求。系统设计原则除了基本的易操作原则，安全性原则外，还有准确性原则，实用性原则，可维护性原则。

第一个设计原则：易操作原则，针对本系统设计的功能要完备齐全，编码时，设计的各个接口要具备友好性，使用者一旦使用本系统时，要能够轻松上手，操作本系统处理数据时，要具备便利性。此外，也需要设计一些必要提示，引导使用者操作系统。

第二个设计原则：安全性原则，本系统在登录模块要对各个访问者进行身份验证，系统会通过访问者输入的信息进行判断，使用提前编写的安全验证代码进行数据比对，引导匹配成功的访问者进入指定的操作界面。这样可以避免无关性访问者窃取系统的数据。

第三个设计原则：准确性原则，为了保证使用者登记的数据是正确的，需要提前设计数据纠错机制，让使用者可以通过系统的报错提示，仔细检查登记的错误信息，并及时纠正错误，填写规范正确的信息。比如设置密码时，要求密码的长度不能低于6个字符，且数据类型要求不能全部是数字等都能进行规范。

第四个设计原则：实用性原则，本系统主要用于处理信息，在实际工作中，要帮助使用者完成信息处理任务，同时本系统在面对特殊情况时，也要能够满足信息处理的需要。另外，为了后期便于在本系统中进行功能的扩充，也需要提前预留好空间。

第五个设计原则：可维护性原则，本系统在实际使用期间，难免会遇到一些故障，因此，本系统在应对故障时，要能够进行诊断并弱化故障，可以在短时间内进行自维护。
## 4.2 功能结构设计
在前面分析的管理员功能的基础上，进行接下来的设计工作，最终展示设计的结构图（见下图）。

学生实习与就业管理系统


用户信息管理

公告信息管理

职位招聘管理

商辅导教师管理

商企业信息管理

用用户信息修改

用用户信息新增

商企业信息添加 

商企业信息删除

商企业信息修改

商辅导教师添加

商辅导教师修改

商辅导教师删除

商公告信息添加

商公告信息删改

商公告信息删除

商职位招聘添加 

商职位招聘修改 

商职位招聘删除 

新

公告类型管理

新公告类型修改

新公告类型删除

新公告类型添加


![](/md/blog.005.png)

4.3 数据库设计

开发一个系统也需要提前设计数据库。这里的数据库是相关数据的集合，存储在一起的这些数据也是按照一定的组织方式进行的。目前，数据库能够服务于多种应用程序，则是源于它存储方式最佳，具备数据冗余率低的优势。虽然数据库为程序提供信息存储服务，但它与程序之间也可以保持较高的独立性。总而言之，数据库经历了很长一段时间的发展，从最初的不为人知，到现在的人尽皆知，其相关技术也越发成熟，同时也拥有着坚实的理论基础。

4.3.1 数据库概念设计

这部分内容需要借助数据库关系图来完成，也需要使用专门绘制数据库关系图的工具，比如Visio工具就可以设计E-R图（数据库关系图）。设计数据库，也需要按照设计的流程进行，首先还是要根据需求完成实体的确定，分析实体具有的特征，还有对实体间的关联关系进行确定。最后才是使用E-R模型的表示方法，绘制本系统的E-R图。不管是使用亿图软件，还是Visio工具，对于E-R模型的表示符号都一样，通常矩形代表实体，实体间存在的关系用菱形符号表示，实体的属性也就是实体的特征用符号椭圆表示。最后使用直线将矩形，菱形和椭圆等符号连接起来。接下来就开始对本系统的E-R图进行绘制。

（1）下图是用户实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\用户.jpg](/md/blog.006.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\用户.jpg")
图4.1 用户实体属性图

（2）下图是职位留言实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\职位留言.jpg](/md/blog.007.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\职位留言.jpg")
图4.2 职位留言实体属性图

（3）下图是辅导教师实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\辅导教师.jpg](/md/blog.008.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\辅导教师.jpg")
图4.3 辅导教师实体属性图

（4）下图是公告信息实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\公告信息.jpg](/md/blog.009.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\公告信息.jpg")
图4.4 公告信息实体属性图

（5）下图是字典表实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\字典表.jpg](/md/blog.010.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\字典表.jpg")
图4.5 字典表实体属性图

（6）下图是工作管理人实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\工作管理人.jpg](/md/blog.011.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\工作管理人.jpg")
图4.6 工作管理人实体属性图

（7）下图是企业实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\企业.jpg](/md/blog.012.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\企业.jpg")
图4.7 企业实体属性图

（8）下图是职位收藏实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\职位收藏.jpg](/md/blog.013.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\职位收藏.jpg")
图4.8 职位收藏实体属性图

（9）下图是职位招聘实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\职位招聘.jpg](/md/blog.014.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\职位招聘.jpg")
图4.9 职位招聘实体属性图

（10）下图是申请实习实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\申请实习.jpg](/md/blog.015.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\申请实习.jpg")
图4.10 申请实习实体属性图

（11）下图是辅导教师留言实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\辅导教师留言.jpg](/md/blog.016.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\辅导教师留言.jpg")
图4.11 辅导教师留言实体属性图

（12）下图是用户表实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\用户表.jpg](/md/blog.017.jpeg "C:\Users\Administrator\Desktop\img\xueshengshixiyujiuye\用户表.jpg")
图4.12 用户表实体属性图
### 4.3.1 数据库物理设计
本数据库是关系型数据库，因此对二维表的结构设计也比较关键。毕竟二维表格模型就是关系型数据库中的关系模型。而一些常用的关系模型中的概念也需要了解，才可以对关系模型进行设计。下面就简单介绍关系，元组，属性，域，关键字等常用概念的含义。

关系：关系就是数据库中的一张数据表，每张数据表都有命名，也就是每个关系也有名字，那就是数据表名；

元组：元组就是数据表中的一行记录；

属性：属性就是数据表中的字段，也就是数据表中的一列；

域：域就是对数据表中属性的取值进行限定；

关键字：关键字就是数据表中的主键；

在了解了表结构设计的常用概念后，接下来就需要使用前面绘制的E-R模型完成表结构的设计工作，并在数据库中创建数据表，并为各个数据表进行命名。以下就对设计的结果通过表格形式进行展示。

表4.1字典表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|
表4.2辅导教师表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|fudaojiaoshi\_name|String|教师姓名|是|
|3|fudaojiaoshi\_photo|String|头像|是|
|4|fudaojiaoshi\_phone|String|教师手机号|是|
|5|fudaojiaoshi\_email|String|邮箱|是|
|6|create\_time|Date|创建时间|是|
表4.3辅导教师留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|fudaojiaoshi\_id|Integer|辅导教师|是|
|3|yonghu\_id|Integer|用户|是|
|4|fudaojiaoshi\_liuyan\_text|String|留言内容|是|
|5|reply\_text|String|回复内容|是|
|6|insert\_time|Date|留言时间|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.4企业表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gongsi\_name|String|企业名称|是|
|3|hanye\_types|Integer|所在行业|是|
|4|gongsi\_phone|String|联系方式|是|
|5|gongsi\_email|String|邮箱|是|
|6|gongsi\_photo|String|营业执照展示|是|
|7|gongsi\_content|String|企业简介|是|
|8|gongsi\_delete|Integer|逻辑删除|是|
|9|create\_time|Date|创建时间|是|
表4.5工作管理人表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gongzuoguanliren\_name|String|工作管理人姓名|是|
|3|gongzuoguanliren\_photo|String|头像|是|
|4|gongzuoguanliren\_phone|String|工作管理人手机号|是|
|5|gongzuoguanliren\_email|String|邮箱|是|
|6|create\_time|Date|创建时间|是|
表4.6公告信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|news\_name|String|公告信息标题|是|
|3|news\_types|Integer|公告信息类型|是|
|4|news\_photo|String|公告信息图片|是|
|5|insert\_time|Date|公告信息时间|是|
|6|news\_content|String|公告信息详情|是|
|7|news\_delete|Integer|假删|是|
|8|create\_time|Date|创建时间|是|
表4.7申请实习表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|学生|是|
|3|zhaopin\_id|Integer|招聘|是|
|4|zhaopin\_file|String|简历|是|
|5|toudi\_yesno\_types|Integer|审核结果|是|
|6|toudi\_yesno\_text|String|审核原因|是|
|7|insert\_time|Date|投递时间|是|
|8|create\_time|Date|创建时间|是|
表4.8用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|用户姓名|是|
|3|yonghu\_photo|String|头像|是|
|4|yonghu\_phone|String|用户手机号|是|
|5|yonghu\_id\_number|String|用户身份证号|是|
|6|yonghu\_email|String|邮箱|是|
|7|yonghu\_delete|Integer|假删|是|
|8|create\_time|Date|创建时间|是|
表4.9职位招聘表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gongsi\_id|Integer|企业|是|
|3|zhaopin\_name|String|招聘信息名称|是|
|4|zhaopin\_photo|String|招聘信息照片|是|
|5|zhaopin\_address|String|上班地点|是|
|6|lianxiren\_name|String|联系人|是|
|7|zhaopin\_phone|String|招聘电话|是|
|8|zhaopin\_types|Integer|招聘岗位|是|
|9|zhaopin\_renshu\_number|Integer|招聘人数|是|
|10|zhaopin\_content|String|招聘信息详情|是|
|11|create\_time|Date|创建时间|是|
表4.10职位收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|zhaopin\_id|Integer|职位|是|
|3|yonghu\_id|Integer|用户|是|
|4|zhaopin\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.11职位留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|zhaopin\_id|Integer|职位|是|
|3|yonghu\_id|Integer|用户|是|
|4|zhaopin\_liuyan\_text|String|留言内容|是|
|5|reply\_text|String|回复内容|是|
|6|insert\_time|Date|留言时间|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.12用户表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|用户名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|


# 第5章 系统实现
进入到这个环节，也就可以及时检查出前面设计的需求是否可靠了。一个设计良好的方案在运用于系统实现中，是会帮助系统编制人员节省时间，并提升开发效率的。所以在系统的编程阶段，也就是系统实现阶段，对于一些不合理的设计需求，也是可以及时发现。因为设计的方案是完全指导系统的编码过程的。
### 5.1用户信息管理
如图5.1显示的就是用户信息管理页面，此页面提供给管理员的功能有：用户信息的查询管理，可以删除用户信息、修改用户信息、新增用户信息，

还进行了对用户名称的模糊查询的条件

![](/md/blog.018.png)

图5.1 用户信息管理页面
### 5.2 企业信息管理
如图5.2显示的就是企业信息管理页面，此页面提供给管理员的功能有：查看已发布的企业信息数据，修改企业信息，企业信息作废，即可删除，还进行了对企业信息名称的模糊查询 企业信息信息的类型查询等等一些条件。

![](/md/blog.019.png)



图5.2 企业信息管理页面
### 5.3职位招聘管理
如图5.3显示的就是职位招聘管理页面，此页面提供给管理员的功能有：根据职位招聘进行条件查询，还可以对职位招聘进行新增、修改、查询操作等等。

![](/md/blog.020.png)


图5.3 职位招聘管理页面
### 5.1公告类型管理
如图5.4显示的就是公告类型管理页面，此页面提供给管理员的功能有：根据公告类型进行新增、修改、查询操作等等。

![](/md/blog.021.png)


图5.4 公告类型管理页面


# 











# UTADA Group Study Tech List

##WEB 后端


### &emsp; 1. web 基础知识 (TCP, restful…)

prerequisite: None

resources: 

-   [web入门](https://jestar719.gitbooks.io/net_skill_tree/content/)



###&emsp;2.1.  django framework

 prerequisite: CSC148

简介：A start for web programmer. Django makes it easier to build better Web apps              more quickly and with less code.

resources：

-   [basic tutorial](https://tutorial.djangogirls.org/en/index.html)    
-   [e-commerence project](https://codingforentrepreneurs.com/projects/ecommerce-2/)

### &emsp;2.2. flask framework

prerequisite: CSC148

简介：比django更简单易用的轻量级web框架, industry(e.x CPPIB, RBC)中internal system主流

resources: 

-   [The Flask Mega-tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)

### &emsp;3.   separate backend and frontend

 prerequisite: 2.1 or 2.2 , CSC148

简介：简而言之就是把前端（html，css, js部分从web application中分离）

resources：

-   [The reason why we separate back and front end](https://quickleft.com/blog/six-reasons-we-split-front-end-and-back-end-code-into-two-git-repositories-working-with-github-repositories/)

-   Flask restful: [flask with restful](https://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask)

-   Django restful: [how to create a django restful api in 20 minutes](https://www.youtube.com/watch?v=gz5TPI2sSTo)

### &emsp;4. Deployment

 prerequisite: An idea about how components of a website works together

 resources: (a) AWS: EC2 + RDS + R53, (b) Heroku, (c) DigitalOcean …

 resources:
 
 -   [Post your python app](https://www.youtube.com/watch?v=3HuYr6G2Z28)
 <br>
 <br>

##WEB 前端 [web前端主要靠实战，知识点太杂，简单了解]



###&emsp; 1. READING web前段简介

prerequisite: None

resources : 
 
- [web前段如何入门](https://www.zhihu.com/question/32314049)

###&emsp;2.   HTML&amp;CSS&amp;JS

resources:

-    [李炎恢 HTML CSS JavaScript Bootstrap 教程](https://wizardforcel.gitbooks.io/liyanhui-tutorials/content/66.html)        快速扫一遍

###&emsp;3.   Anjular JS

prerequisite:  HTML&amp;CSS&amp;JS

 resources: 
 
 -   [code school](https://www.codeschool.com/courses/shaping-up-with-angular-js)

###&emsp;4.   React JS

prerequisite:  HTML&amp;CSS&amp;JS

resources: 

-   [code school](https://www.codeschool.com/courses/powering-up-with-react)
<br>
<br>

##Multiplatform APP开发(开发一遍，web,ios,android都能用)

###1. REACT NATIVE

prerequisite: React, IOS or Androidd basics.

简介： Write once, run multiplatform. Now react native is compatible with IOS\Android\Windows and so on.

resources:

-   [facebook hand-on tutorials codelab](https://facebook.github.io/react-native/docs/tutorial.html)
- [your first react native example app - Hello World App](https://www.raywenderlich.com/126063/react-native-tutorial)
- [luffy的项目代码示例](https://github.com/chocoluffy/ReactNativeEverydayDemo)
- [why react native rather than native ios?](https://medium.com/ios-os-x-development/an-ios-developer-on-react-native-1f24786c29f0#.b6njysneo)
- 即将推出的whalesper app的技术栈， 技术细节留意未来workshop

<br>

##Native Android

Recommended preparation: CSC207

resources:

-   编辑器：Android Studio

-   [Udacity Android Beginner](https://www.udacity.com/course/android-development-for-beginners--ud837)

-   (survive) UI Widget, Intent, Activity Lifecycle, AsyncTask + Internetworking (volley), Fragment, ListView,

-   (ViewPager), Storing information,

-   (thrive) Multimedia, Notification broadcast &amp; receive, View override, JNI, Gradle, Unit test


<br>

##Native iOS

Recommended Prerequisite: CSC108，CSC148, CSC207

resources:

-   所用语言: Swift (推荐) / Objective-C

-   所用编译器: Xcode

-   所用API: Cocoa

-   [Swift官方介绍](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/index.html#//apple_ref/doc/uid/TP40014097-CH3-ID0)

-   [Swift官方教程](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/GuidedTour.html#//apple_ref/doc/uid/TP40014097-CH2-ID1)

-   [如何下载Xcode](https://developer.apple.com/download/)

-   [掘金的iOS专页](https://gold.xitu.io/welcome/ios)

-   [TutorialPoint的Objective-C教程](http://www.tutorialspoint.com/ios/)







<br>

##Machine Learning

Prerequisite: CSC108, STA247/STA257

Recommended Preparation: CSC148, STA248/STA261

###&emsp;1. Machine Learning简介

 resources: 
 
-   [机器之心 machine learn 入门](http://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&amp;mid=2650721853&amp;idx=3&amp;sn=f9f0048cccefbf9c00dc94f2a71c7d00&amp;chksm=871b0a43b06c8355376d1bc897b4f3585b4a129d77a9e5b025f4c344f2ef264c05133cff7682&amp;scene=21#wechat_redirect)

-   [ Generating Stories about Images](https://medium.com/@samim/generating-stories-about-images-d163ba41e4ed#.xxofzzyn2)

###&emsp;2.  神经网络入门

resources:

  -   NN+CNN: [standford cs231n](http://cs231n.stanford.edu/)  (BEST tutorial for entry level mechine learning)

  -   RNN: [standford cd224d](http://cs224d.stanford.edu/)

-   LTST: [ 理解LSTM](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)

###&emsp;3.  Machine Learning and NLP

 resources: 
 
 -   [represent word using vector](https://arxiv.org/pdf/1301.3781.pdf)

-   相关项目 UT助手chatbot

###&emsp;4. 2016 paper list

 -   [ICML 2016 accepted papers](http://icml.cc/2016/?page_id=1649)

 -   [NIPS 2016 accepted papers](https://nips.cc/Conferences/2016/AcceptedPapers)


<br>

##Traditional AI

Prerequisite:  CSC148

###1.  Game AI

resources:   

 -   [CMU lecture](https://www.cs.cmu.edu/~adamchik/15-121/lectures/Game%20Trees/Game%20Trees.html)

 -   五子棋 AI [教程](http://blog.csdn.net/lihongxun945/article/details/50625267)
<br>
<br>

##IOT+Application of AI (软硬件结合)

Prerequisite:  CSC258 (or equivalent courses. Should be comfortable with running    programs on a board)  ,Be comfortable with playing around with circuits

Recommended preparation:   CSC358 or be comfortable with talking about TCP/IP, DNS, etc, CSC401 or be comfortable with NLP

resources:

 -   Mark Zuckerberg&#39;s Jarvis: video demo 1[[https://www.youtube.com/watch?v=KdQ54681no0](https://www.youtube.com/watch?v=KdQ54681no0) ] demo 2 [[https://www.youtube.com/watch?v=PqvkhxNatyY](https://www.youtube.com/watch?v=PqvkhxNatyY) ]
 -   How was Jarvis built? [[https://www.facebook.com/notes/mark-zuckerberg/building-jarvis/10154361492931634/](https://www.facebook.com/notes/mark-zuckerberg/building-jarvis/10154361492931634/) ]
 -   Internetworking with Arduino [Arduino manual]

 
<br>
##BIG DATA

Prerequisite:  STA257， CSC343


###&emsp;1.  Hadoop

resources:   

 -   [零基础如何入门hadoop](https://www.zhihu.com/question/19795366l)

 
###&emsp;2.  Spark

resources:   

 -   [用Apache Spark进行大数据处理](http://www.infoq.com/cn/articles/apache-spark-introduction)

  
###&emsp;3.  Cassandra

resources:   

 -   [Data Stax self-paced courses](https://academy.datastax.com/courses)
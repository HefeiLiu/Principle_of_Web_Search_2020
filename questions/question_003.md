| 第3讲答疑&nbsp;问题列表  |
|--------------|
|老师用了header来反制网站的反爬措施，那么一般的网站搜索引擎会不会被网站的反爬措施屏蔽？还是说只是爬取的频率问题？|
|课前让安装requests可以讲一下吗|
|能否将链接与标题文本作一个直观上的合并？实现了用频率作为排序标准后，能否以其他因素，比如被检索次数（历史）、单个用户的搜索兴趣标签等作为排序标准进行排序？|
|有些地方讲的比较快，当场不太好理解。不过课下可以看回放|
|对大小写高亮显示的问题很感兴趣|
|老师您好上课的时间和每周的组会有冲突，可以在看完视频后再填课堂调查吗？|
|想了解一下网页防爬虫和爬虫如何绕过网络防御，看老师爬网易新闻时候加到agent，对这个比较感兴趣|
|爬取不同网站的内容时需要因地制宜地分析不同网站的架构并开发对应的爬虫吗？有没有一种通用的办法呢？|
|之前了解过爬虫的内容，用的也是requests包，想问一下爬虫和搜索引擎的关系是什么？|
|如果对所获取的文本按照关键词出现次数进行打分，感觉执行起来比较耗时间，有什么别的方法吗？|
|搜索的实现只能用Python语言吗，语言的选择会对搜索最终的呈现产生影响吗|
|这几节课都是在讲一个简单搜索引擎的实现，不知道之前安装的elasticsearch开源框架该如何使用。还是会在后续课程中陆续用到？|
|想问一下，jupyter的代码高亮，以及敲“.”之后自动弹出相关方法这些在哪里设置？|
|新闻网站某条新闻的点击量如何获得？我觉得热度也可以作为影响score函数的一部分|
|在编程过程中，发现继续用上节课编的Jupter Notebook 的文件，在后面加cell 出现了sorted_result列表为空这个问题，新建一个python文件就没有这个问题。|
|在实际的网络搜索中，对于向用户推荐的网页的打分是否可以根据超链接来分析?因为如果某个网页被其他网页指向的次数越多，应该说明这个网页越热门。|
|很佩服老师的思考方式，问题导向提高解决问题的能力，但我觉得自己缺乏的就是发现问题的能力|
|1.对于一个长短语想要搜索出结果应该怎么做，比如输入“华为5G手机”这样的短语怎么搜索出包含华为、包含5G或者包含手机这样关键词的结果？会用到什么方法库？<br/>2.如何将爬取到的连接和标题结合起来，和浏览器搜索出的结果一样，点击对应的标题，就可以进入到相应的正文界面，如果要实现这样的功能，需要进行Web开发吗？<br/>3.最后获取正文那段代码运行的速度比较慢？有什么优化的方法吗？比如建立索引表之类的方法对优化这种情况可行性如何？|
|课上呈现搜索结果时是一次性打印全体的，而网上的搜索引擎对搜索结果是分页显示的，真实的搜索引擎是如何保存之后页的搜索结果的，是重新做一次搜索排序还是结果暂存在某个地方等待用户点击下一页？|
|“采”这个过程，百度谷歌这种搜索到底是爬了多少网站呢？是不是看到百度的header，那些网站就放开让他抓数据了|
|怎样更好的对Python问题（语法，方法）描述？|
|在网页上爬数据一定要用requests和lxml吗，还是说不同的应用场景，有不同的合适的库或包呢|
|1 sort()里用的lambda是干啥用的<br/>2 我们今天这个带有正文的打分排序可以在elasticsearch里操作吗，另外，有关es的视频老师大概什么时候出哈哈<br/>3 我们课程大概的结构是怎么样的，后续老师会讲现在用的比较多的搜索打分排序推荐算法吗|
|搜索结果要缓存，经过打分之后再输出排序结果，那用户的历史行为也是打分的一项吗？还是用户的历史行为直接排到前面？|
|1.xpath的用法不是很清晰<br/>2.requests中的get方法，什么时候需要加headers什么时候不需要加？headers中'user_agent''accept'这些信息要都写上吗|
|现在还没有使用到ES，通过编程进行信息检索排序等，现在是通过编程模拟ES的功能吗？|
|网络中的信息是瞬息万变的，为了保证搜索结果的时效性需要对爬取的数据进行更新，如何选取合适的更新策略与更新频率？|
|真正的搜索引擎也是从其他公司的服务器上来这样爬取过滤吗？是不是有一些协议啥的，如果是本地查询的话这个存储量也太大了吧？|
|对于lxml和requests下使用到的一些函数，是否需要去了解其实现的原理？|
|没学过Python的同学是不是要去系统学一下Python，感觉靠百度搜各个函数功能来写代码有点吃力|
|想问老师一个有关python编程的问题，python不同已封装好的函数如何衡量其复杂度呢，如果想提高算法效率需要了解函数内部实现过程吗？|
|本次课我们对爬取的网页进行处理时是通过人工指定xpath来的方式来获得网页的标题和正文的。但是在自动化采集处理网页的过程中，对于每一个不同的网页不可能都来人为指定xpath，那么他们是如何确定网页中哪些内容是标题，哪些是正文，哪些是垃圾信息的呢？|
|感觉三节课学了还是有点懵，老师能不能给个这门课的整体学习框架|
|老师，课后作业能多扩展一两个思路或者方法吗？也不用特别详细，一个简单的idea或者别的应用场景，这样以后遇到类似的问题也能很有帮助！谢谢老师！|
|"当前的通用搜索引擎最大的缺点是什么？有哪些急需解决的问题或改进的方向？哪些用户需求还不能被很好地满足？<br/>近几年发展起来的阅读理解式问答系统有哪些有实际意义且有望落地的应用？"|
|是否可用正则表达式和find()函数实现不区分大小写的搜索，从而解决第一个问题|
|老师我很好奇为什么python里面字符串要规定不可改变，虽然某些时候会起到保护数据的作用，但是也可能会导致内存泄漏呀。比如：str="Hello"，执行一下str=str+"world"。那么新得到的str就不是原来的string对象了，指向的内存地址也不同了，而原来的"Hello"这个string对象还在内存里呀，那这段被占用的内存不就在程序运行结束前一直被占着吗？|
|我观察到我们这几次实践的网页都比较像那种传统的静态页面，布局比较整齐，可能比较好获取xpath,如果遇见动态生成的那种页面，链接是变量的怎么办？|
|对于多级页面信息的爬取是采用bfs或者dfs的方法吗？如何根据具体情况分析爬取多少级页面信息？在匹配关键词时，使用正则匹配的和转换大小写后再匹配，哪个效率更高？|
|像新闻这样的每天都会更新内容和信息爬虫爬取的频率是多高，整个搜索引擎的数据更新频率是怎么设定的呢？<br/>我自己设计的爬虫经常会被其他网站ban掉（已设计好headers内容） 搜索引擎的爬虫是如何避免被其他网站ban掉的呢？|
|在爬取信息的时候，因为课上的网页是网易新闻的，结构会比较相似，那如果爬取一些结构不那么相似的网页的信息，会需要对每个网页所要获得的信息的xpath进行分析吗|
|在二级标题较多的时候应该怎么取文本呢？|
|老师，请问爬虫程序在对一个网站进行爬取时，需要些什么技术来应对网站的各种反爬机制呢？|
|今天前面没跟上，课下跟着视频再学一遍吧。请问老师有PPT吗，感觉这样更有效果。|
|"爬取多级链接页面信息时，如何根据具体情况确定爬取多少级？<br/>关键词在进行匹配时，使用正则表达式和在进行大小写转换后再匹配相比，哪个效率更高？"|
|为什么我在增加了headers以后，循环会报错：list index out of range|
|更新下刚刚提的问题，深层原因我也不清楚，表面上来看是当我用chrome刷新一次网页后，网易新闻会自动跳转到这篇文章的手机版，所以headers也不是windows，而是Android linux，当我用edge刷新网页后就不存在该问题了。|
|反爬是怎么实现的？Robots协议和爬虫是什么关系？它会影响我们自己写的爬虫吗？|
|为什么我的keyword（华为和tiktok）匹配到的标题还不到10个，而老师匹配到了那么多，在用xpath取到了700多个标题的情况下。|
|课上对一句代码进行反复修改以后那句话会变得好长不利于阅读，是不是设一个中间变量看起来更清楚呢|
|课上在rank那里没有搞的很明白，课后又看了遍视频，虽然感觉能跟着做下来，但自己写不出来|
|每次爬取网页数据，需要知道对应的xpath，如果要爬取大量网页的数据，不可能像课上那样一个个去找对应块的xpath，那应该怎么操作呢？|
|还是不太懂为什么highlight函数刚开始用return text时无法达到想要的效果…|
|可以将xpath理解为网页上标签的目录吗|
|请老师详细讲讲正则表达式|
|安全机制更好的网络是怎样从已经设置agent和头部的抓取方法察觉到是机器抓取的|
|网页有哪些反爬虫机制|
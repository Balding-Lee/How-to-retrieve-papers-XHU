# How-to-retrieve-papers-XHU
西华大学论文检索方式与如何阅读论文

# 1 如何检索论文
## 1.1 Web of Science
进入`西华大学官网首页`，点击右上角`图书馆`。

![西华首页](https://user-images.githubusercontent.com/49380927/134502686-84a957b8-ce3c-48e7-bca5-52a0bab07b5d.png)

选择`[综合] Web of Science(SCI系列)`。

![图书馆首页-Web of Science](https://user-images.githubusercontent.com/49380927/134502900-a650c3cc-8933-40e0-ac1a-78c294c7a0af.png)

`Web of Science`首页做检索：

![Web of Science-首页](https://user-images.githubusercontent.com/49380927/134503357-b16464f3-b9d5-4fa1-90f4-1563783d00d5.png)

之后进入检索页面后，选择自己需要的论文。看了摘要后，如果觉得是自己需要的论文，则复制DOI号（**`DOI:`后的内容全部复制**），在SCI-HUB中进行检索下载。右上角`导出`按钮可导出`EndNote Desktop`或者`RIS`，下载下来后导入`EndNote`做文献管理。

![Web of Science-论文页](https://user-images.githubusercontent.com/49380927/134503719-cdb24e9c-a72e-480f-85bf-4d2eb9e1b9a5.png)

在SCI-HUB中，将刚刚复制的DOI粘贴进去，点击检索按钮，右上角点击下载按钮即可下载。SCI-HUB网址：https://www.douban.com/group/topic/144179135/

![SCI-HUB](https://user-images.githubusercontent.com/49380927/134504158-1a05d8fb-e1e7-4321-b478-55fc18b02f1e.png)

## 1.2 中国知网CNKI
在`西华大学图书馆`中选择`[综合] 中国知网CNKI`：

![图书馆首页-中国知网CNKI](https://user-images.githubusercontent.com/49380927/134504883-3fa62ece-ef33-4129-9e9c-80f4570fbb1f.png)

如果`未登录`，则在登陆入口选择`IP登陆`。在检索内容中输入检索东西。**个人建议阅读一区二区或者顶会论文，如果要看中文论文，则建议只看985的博士学位论文。**

![知网检索](https://user-images.githubusercontent.com/49380927/134505654-29edb617-f05a-4219-b118-51f82330aec3.png)

## 1.3 dblp

百度搜索`dblp`，第一个就是了。或者`dblp`网址：https://dblp.org/

在检索栏就可以进行检索，包括`关键字`，`文章名`，`作者名`，`期刊名`，`会议名`等等，都可以检索。

![dblp-首页](https://user-images.githubusercontent.com/49380927/134506696-0d37a0de-3781-4747-a151-d3089a0cd4d0.png)

在检索页中，其排序方式是按照年份进行排序的。可以看得到`作者名`，`论文名`，`发表刊物`。同时，在左侧会有颜色的标记，其中：
1. `红色：`期刊论文；
2. `蓝色：`会议论文；
3. `灰色：`未发表论文，比如arxiv，CoRR等；
4. `黄色：`书籍；
5. `其余颜色查看：`https://blog.csdn.net/DXY587542/article/details/114306545

![dblp-检索页](https://user-images.githubusercontent.com/49380927/134507438-1b78646b-fb56-441c-bcc2-19e3b6f7ea56.png)

至于在dblp上下载论文，把鼠标放置论文前这一坨上，选择`electronic edition via DOI (open access)`：

![dblp-下载论文](https://user-images.githubusercontent.com/49380927/134508005-86ab26ff-e90b-43e8-9590-2dab21bc95f1.png)

通过这个链接进入后，一般来说都可以下载论文，如果下载要钱，那么你可以在页面里面找到`DOI`，然后`SCI-HUB`，你懂我意思。（当然这个截图是个错误示范，`IEEE Access`尽管是个二区，但是是中科院预警期刊，就是属于那种审稿人看着你参考文献里面有个`Access`的论文估计都会看低你两眼的那种……食之无味，弃之可惜）。或者说你可以在`dblp`里面有没有相同的论文，只是说发表在`arxiv`或者`CoRR`里面的论文，那个就是免费下载的，就比如下图：

![dblp-下载论文-2](https://user-images.githubusercontent.com/49380927/134508576-831b628c-b3fd-4ec7-ab7f-7289f1241a93.png)

dblp中还可以选择下载`RIS`，导入`EndNote`中做文献管理；也可以下载`BibTex`，从此不用再纠结于一个字一个字敲参考文献：

![dblp-RIS与BibTex](https://user-images.githubusercontent.com/49380927/134508872-919f0067-5f22-4761-aaaa-1cb755b45f0b.png)

## 1.4 arxiv
百度搜索`arxiv`，第一个就是。或者`arxiv`网址：https://arxiv.org/ 或者：https://arxiv.org/corr （后者就是计算机的了）

![arxiv-检索](https://user-images.githubusercontent.com/49380927/134510196-7b382877-7757-41b5-bf8a-8253c0fd1d35.png)

写了论文怕被审稿人嫖走了，就可以投稿在`arxiv`上宣告主权。

## 1.5 HuggingFace

百度搜索`HuggingFace`，第一个就是，或者`HuggingFace`网址：https://huggingface.co/

超方便的端到端模型，超详细的官方文档：https://huggingface.co/transformers/ ，可以直接在该网站上搜索想要的模型，然后用别人给的API即可快速搭建一个自己的端到端模型。快速搭建自己模型的网址：https://mp.weixin.qq.com/s/TraKZhicH1cRCLCBo7K_SQ （或者看官方文档）

## 1.6 Papers with code

百度搜索`Paperswithcode`，第一个就是，或者`Paperswithcode`网址：https://paperswithcode.com/

这里面可以搜索到想要的论文，以及其在`github`上公开的代码：

![paperswithcode](https://user-images.githubusercontent.com/49380927/134511839-2809ae1a-8b34-49c8-9eac-a9e1926ff4b9.png)

# 2 论文哪些可读，哪些不可读？

最直白的查看论文可不可读的方法，就是搜索论文的分区。这里推荐的期刊查询的是`letpub`，网址在这里：https://www.letpub.com.cn/ （虽然该网站广告就像小网站一样，但是确实不错）

进入页面后，选择`智库资源`中的`最新SCI期刊信息查询系统`：

![letpub-首页](https://user-images.githubusercontent.com/49380927/134514901-b838e657-4db4-420f-80b7-799c5ff560eb.png)

输入要检索的期刊，就可以查看到简略信息，也可以点击进入查看详细信息：

![letpub-检索页](https://user-images.githubusercontent.com/49380927/134515212-e930428f-3a28-4789-8f5f-fd8849e37398.png)

其中有两个分区信息，第一个是美国那边的评级（没啥参考价值）：

![letpub-分区一](https://user-images.githubusercontent.com/49380927/134515367-d2f9c32b-7398-48bc-9aca-039343eced24.png)

第二个就是中科院的JCR分区：

![letpub-分区二](https://user-images.githubusercontent.com/49380927/134515479-3179e082-3c63-4f68-ad36-3fa95f8515ea.png)

当然，上面还可以看到论文审稿速度啊巴拉巴拉的，可以自行探索。

这里推荐的呢，对于期刊论文，就是中科院分区一区二区的论文。当然，对于有些学校申请博士可能看的是CCF上的内容，这个的搜索方式就是上CCF官网进行检索：https://www.ccf.org.cn/ ，网站上最新版的CCF推荐的国际期刊和会议的网址如下：https://www.ccf.org.cn/Focus/2019-04-25/663625.shtml

同样，还有中科院预警期刊。这个就百度`中科院预警期刊`即可查看到预警期刊，比如20年底发布的：https://www.zhihu.com/question/437284270

最后呢，就是经验之谈啦，因为我的了解的面不够，所以我这里就谈谈我自己觉得可以的和不可以的：

1. **可以的**：AAAI，ACL，EMNLP，SIGIR，NLPCC，KBS，information science，neurocomputing，ICLR，IEEE trans...
2. **不行的**：再次鞭尸`IEEE Access`，食之无味，弃之可惜。


# 3 如何阅读论文？

> 这也算是我从进校到现在各个老师师兄师姐，以及我的各位站在科研一线的朋友们，还有我自己在阅读论文的时候的心得体会吧，写在这个地方，留给我现在的师弟师妹，以及我毕业后可能只能在微信群里看到的陌生名字的师弟师妹们，或者无意中进了这个库的各个志同道合的伙伴们吧。

我相信对于我们学校的大部分研究生同学而言，可能都和我一样进校前是个科研小白。一进校，导师就丢过来一啪啦论文，师兄师姐也给你说多看论文。我还记得我刚进校的时候，看李老师给我发的一篇论文，读了整整两个星期，然后发现讲的是啥，我是谁，我在哪，我要干什么？尤其又是纯英文的，看的都头皮发麻。那么应该怎样看论文呢？

![麻了](https://user-images.githubusercontent.com/49380927/134519010-5b7a353d-3567-43cd-a826-adf3b6f11adb.jpg)


## 3.1 读论文前的准备工作
> 以下内容感谢罗家兴师兄！

大家阅读了论文后，会发现有许多的数学知识，这个很考验大家的数学水平，所以在阅读论文前，我比较推荐大家先把数学知识补充一下。线性代数我推荐3Blue1Brown：https://www.bilibili.com/video/BV1ys411472E?p=1 ，看过都说好！概率论呢，我推荐浙江大学的《概率论与数理统计》，或者《程序员的数学》。这些都是论文当中经常出现的。如果是其它的内容，比如随机过程、群论等，那么就看到了自行查资料。

## 3.2 如何读论文？
> 以下内容感谢杜亚军老师，李显勇老师，牛宪华老师，罗冰老师，陈白杨师兄，王亚坤师兄，本科室友徐冯杰，高中同学李林原！

当大家开始阅读论文的时候，会发现论文是十分晦涩难懂的，并不像教材一样会写的十分精细，那么我们应该怎样阅读论文呢？

### 3.2.1 确定论文是否是自己需要的论文
首先`标题`就代表了一篇论文的核心内容，包括解决的问题，采用的方法。`关键字`则包含了本文最核心的东西。通过这两者，就可以大致判断出是否是自己需要的内容。当确定是自己需要的东西后，首先阅读`摘要`，摘要里面就包含了论文解决的问题，论文采用的思想，使用的方法，以及实验的结果。接着阅读`总结`，虽然总结其实就是换个话的摘要，但是侧重点不同，摘要是概括，总结是总结。最后阅读`实验的表格与图`，`模型框架图`，这些可以大致的了解作者的实验思路，以及模型思路。通过上述三个部分，就可以大致确认这篇论文是不是优质论文，或者是不是自己需要的方法。如果不是，那么就跳过看下一篇，如果是，那么就需要**从头开始仔细阅读这篇论文，搞清楚每个细节**。

### 3.2.2 如何看懂一篇论文

经典的论文网上会有许多大佬的解答。当然，大部分的论文，尤其是最新的论文，并不会有这样的东西，那么要搞懂这篇晦涩的论文的思想，最简单的方法就是**看代码**。结合代码来梳理这篇论文的内容，你会发现很多东西都一目了然了。（比如我最近看的一篇论文，里面就轻描淡写的说两个向量做`concatenate`，我并不知道怎么实现的，一看代码，用的`np.vstack()`，瞬间理解了）。如果又是优质的论文，又没有代码呢，那么没办法，自己去实现。当然，也可以选择给作者发邮件咨询问题，但是我至今没有收到过回复的邮件，所以这方面其实我也没有办法说……

## 3.3 看完论文后如何结合到自己的研究方法中

首先要明确你是打算做哪类论文。现有的论文的研究方法无非以下4种：
1. 提出新方法，解决新问题；
2. 提出新方法，用老问题解决；
3. 提出新问题，用老方法解决；
4. 用老方法解决老问题。

这4种里面，对于硕士阶段的我们，第一个其实不是特别容易实现，因为这需要大量的知识与经验的积累，但是我还是希望各位能够朝着这个方向努力。第四种方法也不用考虑，这就是炒冷饭，毫无科研价值在内。那么对于硕士，我觉得要出科研成果，就是针对方法2,3. 

那么对于方法2，我们就看论文中提到的问题，自己能否用其他的方式解决。比如别人用的`GCN`，又没人用过`GAT`做过，我是不是可以考虑使用`GAT`？对于方法3呢，就是我从别人论文里面发现问题，比如你这里只考虑了部分情况，那么我考虑全局情况呢？当然，再详细的经验就没办法细说，因为这个本身就是不可言传的东西，只能靠个人去感受。

## 3.4 紧跟科研步伐
> 这里必须特别感谢陈白杨师兄！！！

紧跟科研的步伐，最大的一个好处就是能够抓住现在的一线学者们研究的问题，而这些有潜力的问题，那么做的再差，也会是一篇排名较高的论文。比如13年的`xxx2Vec`，18年的`BERT`，19年的`GNN`等。当别人提出了一个新的东西之后，新的研究方向就会如雨后春笋一般野蛮生长，而这个时候就是你找到新的创新点的最佳时机。那么如何抓住这个科研前线的任务呢，我推荐一个公众号《智源社区》，每个工作日都会推荐计算机科研最新的资讯，可以根据自己的需要来进行选择。同时，这个还会偶尔发起一些免费的会议，赠送一些免费的书籍，这些都是一个很好的学习机会。

同时，我也恨推荐大家参加学术研讨会，包括但不限于实验室的学术报告（可以了解师兄师姐同学的研究方向，以及了解他们分享的东西是否对自己有所帮助），国际或国内顶会的会议（了解最新科研进展）。

以上就是我个人关于`论文检索`，`期刊和会议评级查询`，以及`如何阅读论文以及找科研方向`的拙见。带有极强的主观感受，如有纰漏，欢迎补充。

<center><b>Copyright @ 2021 西华大学智能技术与系统实验室（http://cs.xhu.edu.cn/b2/82/c1739a111234/page.htm） 版权所有</b></center>

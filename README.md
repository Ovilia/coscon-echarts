# coscon-echarts

欢迎和羡辙一起动手做酷炫的可视化作品！

## 简介

这个文档是为 2018.10.21 [COSCon 会议](http://coscon.kaiyuanshe.cn/)的 ECharts Workshop 准备的。鉴于现场网络状况堪忧，强烈建议与会者事先按“**准备工作**”章节下载好相关资料。“**动手做吧**”章节是会议当天的步骤大纲。

不过，即使你不参加这个会议，也可以跟着文档一起加入动手做的行列哦~

通过这次 Workshop，我们将零基础教学 ECharts，利用开放数据，做出创造性的酷炫的可视化作品。



## 准备工作

### 下载代码

1. 在 GitHub 上 fork 本项目（[Ovilia/coscon-echarts](https://github.com/Ovilia/coscon-echarts)）
2. 下载 fork 后的项目到本地
3. 在项目目录下运行 `npm i`
4. 下载 [echarts-examples](https://github.com/ecomfe/echarts-examples/archive/gh-pages.zip) 以及 [echarts-doc](https://github.com/ecomfe/echarts-doc/archive/gh-pages.zip) 并解压到本项目目录，命名分别为 `echarts-examples-gh-pages` 以及 `echarts-doc-gh-pages`
5. 安装 http-server 以起服务器：`npm i -g http-server`
6. 测试安装成功：运行 `http-server`，打开 `http://127.0.0.1:8080/`，应该会看到一个折线图，点击左下角的“文档”和“链接”，应该都有可以查看到相应内容

### 下载数据

可视化的数据哪里来呢？`data` 文件夹下提供了几个例子，你也可以自行从别处获取。

下面列了几个开放数据网站：

- [国家统计局](http://www.stats.gov.cn)
- [上海市政府数据服务网](http://www.datashanghai.gov.cn)
- [国内40个免费数据源](https://mp.weixin.qq.com/s?__biz=MjM5MTY5OTI0MQ==&mid=205619145&idx=1&sn=987f6a90f30bd134598f9c80c1c57f3e&scene=5#rd)



## 动手做吧

（以下为会议当天 Workshop 内容）

####

### 数据可视化的步骤

1. 获取数据再构思主题 / 构思主题再寻找数据
2. 分析数据，找出感兴趣的维度，过滤掉有明显错误的数据
3. 选择图表类型
4. 用数据实现简单的该类型的图表（先不管样式）
5. 检查是否能反映出主题，能讲出什么样的故事
6. 试验并改进图表设计
7. 改进细节，使得数据更容易被理解，改善视觉效果
8. 添加交互相关的功能，完善图表
9. 检查图表是否表达构思的主题，改进图表

### 一些容易忽略的事

#### 讲故事

一般来说，一个图表最重要的的是：它讲了一个什么故事，你想通过它表达什么。

就算是简单的二维数据，也不是随便放进一个折线图就算完成任务的。一旦明确了你想讲的故事，后面图表的设计都是围绕这点展开的。

#### 图表类型的选择

图表类型怎么选？（会场现场告诉你！）

在你选择图表类型的时候，多问一下自己，为什么用了这种类型而不用另一种？对于图表的亚类型（如堆积柱状图、正负柱状图等）同样需要思考其裨益。

# coscon-echarts

欢迎和羡辙一起动手做酷炫的可视化作品！

## 简介

这个文档是为 2018.10.21 [COSCon 会议](http://coscon.kaiyuanshe.cn/)的 ECharts Workshop 准备的。鉴于现场网络状况堪忧，强烈建议与会者事先按“**准备工作**”章节下载好相关资料。“**动手做吧**”章节是会议当天的步骤大纲。

不过，即使你不参加这个会议，也可以跟着文档一起加入动手做的行列哦~

通过这次 Workshop，我们将零基础教学 ECharts，利用开放数据，做出创造性的酷炫的可视化作品。



## 准备工作

### 下载代码

1. 在 GitHub 上 fork 本项目（[Ovilia/coscon-echarts](https://github.com/Ovilia/coscon-echarts)）。
2. 下载 fork 后的项目到本地
3. 在项目目录下运行 `npm i`
4. 下载 [echarts-examples](https://github.com/ecomfe/echarts-examples/archive/gh-pages.zip) 以及 [echarts-doc](https://github.com/ecomfe/echarts-doc/archive/gh-pages.zip) 并解压到本项目目录，命名分别为 `echarts-examples-gh-pages` 以及 `echarts-doc-gh-pages`
5. 安装 `http-server` 以起服务器：`npm i -g http-server`
6. 测试安装成功：运行 `http-server`，打开 `http://127.0.0.1:8080/`，应该会看到一个折线图，点击左下角的“文档”和“链接”，应该都有可以查看到相应内容

### 下载数据

可视化的数据哪里来呢？`data` 文件夹下提供了几个例子，你也可以自行从别处获取。

下面列了几个开放数据网站：

- [国家统计局](http://www.stats.gov.cn)
- [上海市政府数据服务网](http://www.datashanghai.gov.cn)
- [国内40个免费数据源](https://mp.weixin.qq.com/s?__biz=MjM5MTY5OTI0MQ==&mid=205619145&idx=1&sn=987f6a90f30bd134598f9c80c1c57f3e&scene=5#rd)

## 动手做吧

（以下内容为会议当天 Workshop 步骤）

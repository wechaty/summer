# 期中报告提交指南

期中报告提交后会有一个 OSPP 的 Mid-term Demo Day， 导师和学生会在线上进行期中汇报。提交的期中报告包括 Mid-term Demo Day 的视频和期中报告内容总结。[点击这里查看暑期2020中期路演日（Mid-Term Demo Day）会议实况](https://wechaty.js.org/2020/08/22/summer-2020-wechaty-soc-midterm-demo-day/)

期中报告要**以博客的方式提交到 [wechaty.js.org](https://github.com/wechaty/wechaty.js.org) Repo** 中，在提交报告之前，可以先阅读 [Wechaty 社区规范](https://wechaty.js.org/2021/06/23/the-wechaty-way/), 至少了解下面内容：

1. Wechaty 的介绍
1. 社区沟通渠道
1. 会议规范
1. 博客发布规范
1. Issue 发布规范
1. PR 发布规范

尤其要注意的是在博客发布规范中详细的介绍了如何提交博客、如何在博客中嵌入视频等，在期中博客中会用到，具体要求如下：

## 1. 期中 Demo Day 视频

每位开发者需要进行中期的展示，视频将添加至博客、提交到组委会中，并剪辑成完成的路演日视频，向全社区展示，吸引更多的开发者参与到对应的项目中：

- 提交3-5分钟的、有真人出镜（视频会议软件录制）的、基于PPT的展示。
- 提交不限时长的、有真人出镜（视频会议软件录制）的 Live Code。

学生要在8月26日之前将视频链接回复在对应项目的 Github Issue 下面进行提交，视频由同学们直接上传到Youtube / B站中，并直接将视频的链接和将视频以iframe方式附在各个博客中：

- 视频需要上传到 youtube 中，并联系 [Huan](https://wechaty.js.org/contributors/huan/) 添加到 wechaty 的 playlist 中。
- 考虑到国内用户，可以上传到 bilibili 或者腾讯视频中

可以参考去年优秀学生突出贡献奖获得者[江姗姗](https://wechaty.js.org/contributors/univerone/)的视频：

- [期中汇报视频](https://www.bilibili.com/video/BV1vT4y157x5/)
- [Live Coding 视频](https://www.bilibili.com/video/BV1ih411d75h)

## 2. 期中报告

在8月30日前，以Pull Requests形式在[wechaty.js.org Repo](https://github.com/wechaty/wechaty.js.org)中提交博客。

- 标题： `OSPP 2021-期中报告-你的标题`
- 文件名： `2021-XX-XX-ospp-mid-term-XX`
- 报告 category 为：`project`, `ospp`
- 报告 tag 至少包括：`summer-of-wechaty`,`summer-2021`,`ospp`,`ospp-2021`,`mid-term`，`ospp`
- 报告内容至少包括：
  - 项目信息
    - 项目名称
    - 方案描述
    - 时间规划
  - 项目进度
    - 已完成工作
    - 遇到的问题及解决方案
    - 后续工作安排
  - 项目成果
    - 期中汇报的视频，可以参考 [使用jekyll include在wechaty博客中快速插入视频](https://wechaty.js.org/2020/08/24/add-video-to-wechaty-blog/)
    - Live Coding/Demo 视频

**提交PR时请注意：为这个 PR 打上 `ospp` 的标签，并在 PR 中填写自己项目的 GitHub Issue 链接，方便组委会进行审核。**

报告模板参考：[mid-term-template](template/mid-term-template.md)

## 3. OSPP 2020 学生期中报告参考：

- [基于开放 API 封装 Wechaty 接口下的飞书聊天机器人：期中](https://wechaty.js.org/2020/08/19/wechaty-puppet-lark-mid-term-blog/)
- [暑期2020 编写一个“每日一句”插件 POC 成果展示](https://wechaty.js.org/2020/08/15/wechaty-words-per-day-plugin-mid-term/)
- [暑期2020 基于python-wechaty的群聊助手机器人 POC 成果展示](https://wechaty.js.org/2020/08/14/python-wechaty-groupchat-assistant-bot-poc/)
- [暑期2020 基于 RPA 封装 Wechaty 接口下的快手聊天机器人 中期报告](https://wechaty.js.org/2020/08/20/wechaty-puppet-kuaishou-mid-term/)
- [Wechaty Java 移植组件开发](https://wechaty.js.org/2020/08/17/java-wechaty-transplant-midpoc/)

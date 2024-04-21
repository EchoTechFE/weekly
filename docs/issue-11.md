# #11 - 2024.4.22

## 最前沿

### [ESLint v9 发布](https://eslint.org/blog/2024/04/eslint-v9.0.0-released/)

4.5 日，ESLint 发布了 v9.0.0，该版本存在重大变动，ESLint 为此提供了[迁移指南](https://eslint.org/docs/latest/use/migrate-to-9.0.0)。

以下是部分重要的更新内容：

- Flat config 现在是 ESLint 的默认配置格式，并且 eslintrc 已正式弃用。
- 删除了除 stylish 、 html 、 json 和 json-with-meta 之外的所有格式化程序
- 删除了 valid-jsdoc 和 require-jsdoc 规则
- 删除了 context 和 SourceCode 上已弃用的方法
- 更新了 eslint:recommended
- 对一些现有规则的更新

另外找到一篇 ESLint 在 2022.08 发布的关于 flat config 的介绍，[ESLint's new config system, Part 2: Introduction to flat config](https://eslint.org/blog/2022/08/new-config-system-part-2/)。

### [Nuxt 更新了与 ESLint 集成](https://nuxt.com/blog/eslint-module)

Nuxt 改进了与 ESLint 集成，以通过新的平面配置支持 ESLint v9，使其更加个性化、更强大，并具有更好的开发人员体验。

### [TC 39 Signal 提案](https://eisenbergeffect.medium.com/a-tc39-proposal-for-signals-f0bedd37a335)

Signal 的 v0 草案以及符合规范的 polyfill 已公开发布。Signal 是一种数据类型，通过模拟状态单元和从其他状态或计算中派生的计算来实现单向数据流。状态和计算形成一个无环图，其中每个节点都有从其值中派生状态的其他节点（汇点）和/或为其值贡献状态的节点（源点）。节点也可以被跟踪为“干净”或“脏的”，信号的算法是“推然后拉”模型。脏标志会被急切地更新（Push），而计算会被延迟评估（Pull）。

感觉改方案如果落地，也许会推动各种前端框架中数据流和状态管理统一。

### [Nuxt 2023 回顾和展望](https://nuxt.com/blog/looking-forward-2024)

在 2023 年，Nuxt 团队实现了大部分设定的目标，发布了从 v3.1 到 v3.9 的 9 个小版本更新，直至 23 年 10 月底，Nuxt 3 的下载量超越了 Nuxt 2。
预计在 2024 年 6 月 14 日或之前发布 Nuxt v4，在这之前 Nuxt 将在次要版本中尽可能发布 v4 的部分功能。

### [Node.js 性能 API 简介](https://betterstack.com/community/guides/scaling-nodejs/performance-apis/)

探索 Node.js [pref_hooks](https://nodejs.org/api/perf_hooks.html) 模块中性能测量的 API，并通过一些代码片段了解如何使用它们来记录各种性能指标。

## 涨知识

### [使用 CloseWatcher API 修复烦人的弹出窗口](https://logaretm.com/blog/fix-your-annoying-popups-with-the-closewatcher-api)

Chrome 120 中引入的新 API [CloseWatcher](https://developer.chrome.com/blog/new-in-chrome-120#close-watcher)，该 API 可以帮助开发者更好的处理和优化关闭事件，特别是在移动端还可以处理 Android 的返回键和 iOS 的旁白 Z 手势发出的关闭请求。

### [JavaScript 引擎和 JavaScript 运行时的区别](https://humanwhocodes.com/blog/2024/03/javascript-engines-runtimes)

- JavaScript 引擎实现了由 ECMA-262 标准定义的 ECMAScript。
- JavaScript 运行时则是一个 ECMAScript 宿主，它嵌入了一个 JavaScript 引擎，并为其增加了额外的输入输出功能，以及运行时所需的其他功能。

### [这个“临时方案” Windows 用了 30 年，网友：段子源于现实](https://mp.weixin.qq.com/s/roePnEvG6eJ3VzLYMmwvZA)

微软的“格式化”对话框是 Dave Plummer 设计的一个临时方案，没想到这个方案一用就是 30 年。当初还凭直觉决定了 cluster slack 大小的限制，这直接导致了 FAT 卷的格式化最大容量为 32GB，变成了至今仍在使用的永久限制。

## 小贴士

### [介绍 ESLint 配置检查器](https://eslint.org/blog/2024/04/eslint-config-inspector)

ESLint Config Inspector，这是一个可视化的交互式工具，可以更好地帮助理解和检查 ESLint 配置文件。

### [如何写好 Dark Mode](https://uoyguvbzfk.feishu.cn/wiki/A71LwJ7DLiDsaAk8QO6chWM6nUe)

想知道 Vue、React、Svelet 官网中是如何处理主题的切换的么？如何避免水合不一致的问题呢？

### [开发者线路图](https://roadmap.sh)

roadmap.sh 是 GitHub 上星级排名第六的项目，旨在创建路线图、指南和其他教育内容，帮助开发者选择学习路径。

### [CDN 高额账单风险警示](https://www.alibabacloud.com/help/zh/cdn/product-overview/configure-high-bill-alerts)

三周前我们的 CDN 被盗刷流量了，大致是黑产通过我们业务中直连 OSS 上传图片的 API 上传视频分片文件，并通过我们的 CDN 给用户播放视频，产生了高额的 CDN 账单。我们测试了一些其他网站，发现多多少少也可能存在类似的风险。这里有一篇阿里云官方的教程，可以看看如何尽量减少 CDN 被盗流的风险。

## 念念不忘

本期周刊由以下同学提供资讯:（排名不分先后）

- [lbb00](https://github.com/lbb00)
- [zhuscat](https://github.com/zhuscat)

> 部分摘要由 AI 辅助生成

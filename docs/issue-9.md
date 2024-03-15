# #9 - 2024.3.15

## 最前沿

### [The faster Lambda runtime - NodeJS or LLRT? We benchmarked.](https://learnaws.io/blog/node-vs-llrt)

亚马逊最近开源了 [LLRT](https://github.com/awslabs/llrt)，一种新的低延迟服务器端 JavaScript 运行时，内部使用 [QuickJS](https://bellard.org/quickjs/)。虽然 QuickJS 性能不如 Node.js，但 LLRT 的启动时间和请求的响应速度优于 Node.js，更适合轻量级的应用。

### [Rolldown](https://rolldown.rs) 使用 Rust 编写兼容 Rollup 的打包工具

Rolldown 在 [Oxc](https://oxc-project.github.io) 的基础上开发，目标在未来替换掉 vite 中的 esbuild 和 rollup ，从而解决使用两个不同的工具导致开发版本和生产版本之间的产物可能存在行为差异，以及拥有更好的性能。

### [vue0](https://www.vue0.dev) Vue 版本的 [v0](https://v0.dev) 开源替代品

基于 OpenAI GPT4 ，需要填入 OpenAI Key 才能使用。

### [GitHub Actions; All Actions will run on Node20 instead of Node16 by default](https://github.blog/changelog/2024-03-07-github-actions-all-actions-will-run-on-node20-instead-of-node16-by-default)

随着 Node 16 在去年 9 月终止维护， GitHub Action 将在 5 月 13 日开始强制使用 Node 20。

## 涨知识

### [在 webpack、Vite、Rollup、esbuild、Next.js 等中使用 Parcel 的宏实现](https://github.com/devongovett/unplugin-parcel-macros)

亮点是使用 [Unplugin](https://unplugin.unjs.io/) 开发，Unplugin 是一个统一插件系统。

### [ECMAScript 2024（ES15）将带来这些新特性，超实用！](https://mp.weixin.qq.com/s/rzJyVU7qCRVnEIBcECSD5Q)

速览

- Promise.withResolvers
- Object.groupBy / Map.groupBy
- ArrayBuffer.prototype.resize
- ArrayBuffer.prototype.transfer
- String.prototype.isWellFormed
- String.prototype.toWellFormed
- Atomics.waitAsync
- 正则表达式 v 标志

### [在没有 JavaScript 的情况下无序流式传输 HTML](https://lamplightdev.com/blog/2024/01/10/streaming-html-out-of-order-without-javascript/)

需要浏览器支持 [DSD](https://developer.chrome.com/docs/css-ui/declarative-shadow-dom)。目前 Chrome 和 Safari 已经支持。

### [Speedometer 3.0: The Best Way Yet to Measure Browser Performance](https://webkit.org/blog/15131/speedometer-3-0-the-best-way-yet-to-measure-browser-performance/)

Speedometer 自 2014 年以来一直存在，单新的 3.0 版本得到主要浏览器引擎（Blink, Gecko, WebKit）的支持。新版本增加了更多新的测试、性能提升和改进。WebKit 团队称其为“迄今为止衡量浏览器性能的最佳方式”。

### [The quiet, pervasive devaluation of frontend](https://joshcollinsworth.com/blog/devaluing-frontend)

前端的重要性和挑战被低估，尽管 CSS 和 HTML 在创建用户界面时至关重要，但它们常常被视为不够严肃或不是真正的编程语言。前端工具的营销强调速度而非质量，也影响了对前端工作的认知。

## 小贴士

### [Modern Git Commands and Features You Should Be Using](https://martinheinz.dev/blog/109)

作者推荐了几个好用的 Git 命令。本刊建议学习 worktree 和 bisect 这两个命令，能提升不少效率。

- switch
- restore
- sparse-checkout
- worktree
- bisect

## 念念不忘

> 部分摘要由 AI 辅助生成

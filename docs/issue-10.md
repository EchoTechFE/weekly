# #10 - 2024.3.22

## 最前沿

### [require(esm) in Node.js](https://joyeecheung.github.io/blog/2024/03/18/require-esm-in-node-js)

Node.js 即将实验性的支持 require 加载不包含顶层 await 的 ESM 代码，文章的作者向 Node.js 提交了实现该功能的 PR。模块的格式在 JS 生态仍然是个令人烦恼的问题，比如之前允许 ESM 引入 CJS，但不支持 CJS 引入 ESM。生态内也比较割裂，比如一些包只有 ESM 产物，一些包则保证最大兼容性（编译各种产物）。

### [Nuxt 3.11](https://nuxt.com/blog/v3-11)

> 这可能是 Nuxt v4 之前的最后一个小版本。

可能是比较实用的

- 与请求关联的服务器日志将被传递到客户端，并显示在浏览器控制台，方便调试应用程序。
- 使用 .client.vue 或 .server.vue 指定仅服务端或仅客户端渲染的页面
- public/ 目录或图层目录中的公共资产现在完全由 Nuxt 解
- useAsyncData 和 useFetch 提供 clear 函数

其它

- Preview mode
- Cache-busting payloads
- Middleware routeRules
- New clear data fetching utility
- New #teleports target
- Loading indicator and transition controls
- Server component bonanza
- Performance improvements
- Chunk naming
- Type fixes
- Upgrading
- Full release notes

###

### [Nodejs 新的官网上线啦](https://nodejs.org/en)

新官网有全新的外观、全局搜索框、[教程](https://nodejs.org/en/learn)。

## 涨知识

### [Navigating the future of frontend](https://frontendmastery.com/posts/navigating-the-future-of-frontend/#advances-in-infrastructure)

一篇深入探讨前端生态系统的当前状态和未来发展趋势的文章，包括众多的框架、概念、倡导者、偏好和最佳实践。

### [Qwik 与 React Hydration 有何不同](https://mp.weixin.qq.com/s/NLkeTDFCUqw_2bV2a_V0wA)

Qwik 框架旨在只在需要时加载必要的 JavaScript，比 React 基于路由加载 JavaScript 的颗粒度更小，从而优化性能和用户体验。

### [Next.js v14 实现乐观更新，面向未来的 UI 更新方式](https://juejin.cn/post/7347957960884355113)

通过一个 Todo List 应用介绍在 React 和 Next.js 中如何使用 useOptimistic 实现乐观更新。

## 小贴士

### lodash 的一个替代品 [radash](https://radash-docs.vercel.app/docs/getting-started)

radash 有良好的类型提示，没有依赖，函数式。找到了一篇作者 2022 年的旧文 [Lodash is dead. Long live Radash.](https://medium.com/exobase/lodash-is-dead-long-live-radash-d9d52abf428b)。

## 念念不忘

本期周刊由以下同学提供资讯:（排名不分先后）

- [lbb00](https://github.com/lbb00)
- [zhuscat](https://github.com/zhuscat)

> 部分摘要由 AI 辅助生成

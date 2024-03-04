# #7 - 2024.3.4

## 最前沿

### Volar Language Features (Volar) 更名为 Vue - Official，并废弃了 TypeScript Vue Plugin 扩展

[Vue Language Tools](https://github.com/vuejs/language-tools) 在 3.2 日发布 [v2.0](https://github.com/vuejs/language-tools/releases/tag/v2.0.0)。VS Code 中的 Volar 插件已经更名为 Vue - Official。此次更新 [Takeover Mode](https://vuejs.org/guide/typescript/overview.html#volar-takeover-mode) 被弃用，之前在工作区禁用 VS Code 内置 TS 插件 TypeScript and JavaScript Language Features 的用户将收到 "Takeover mode is no longer needed in version 2.0. Please enable the "TypeScript and JavaScript Language Features" extension." 的警告。

### [React 将被编译](https://reacttraining.com/blog/react-19-will-be-compiled)

将 React 编译成更高效的代码，减少手动优化。

### [Deno 团队开发的一个新 JavaScript 包注册表 JSR](https://jsr.io)

JSR 支持 TypeScript 优先的开发，无需转译，可以直接部署。并且提供了集成的工作空间和无缝的 NPM 集成。

[JSR：目前我们对 Deno 新 JavaScript 包注册表的了解](https://socket.dev/blog/jsr-new-javascript-package-registry)

## 涨知识

### [Pinia 灾难课](https://www.youtube.com/watch?v=D61hGeliypY)

Eduardo 讨论了他在 Pinia 看到的一些不良做法以及应该如何改进。

### [所以你认为你了解 Git](https://www.youtube.com/watch?v=aolI_Rz0ZqY)

GitHub 联合创始人 Scott Chacon 在 FOSDEM 2024 上发表了热情洋溢的演讲，深入探讨了 Git 的许多有趣的部分。

### [Node.js 2023 Year in An Article](https://blog.rafaelgss.dev/nodejs-2023-year-in-review)

一篇文章总结 2023 年以来 Node.js 领域取得的成就。

### [React 实验室：我们一直在做什么 – 2024 年 2 月](https://react.dev/blog/2024/02/15/react-labs-what-we-have-been-working-on-february-2024)

- React Compiler 已经在 instagram.com 上投入生产
- React Actions 管理从客户端到服务器的数据传输的功能，可以在 DOM 元素（如 <form/>）中使用 action 属性来执行数据操作
- React Canary 已经为发布 React 19 做好了准备
- Activity 在研究将应用程序的某些部分标记为“活动”或“非活动”的行为

### [WebAIM 第十次屏幕阅读器用户调查结果现已公布](https://webaim.org/projects/screenreadersurvey10/)

该调查于 2023 年 12 月和 2024 年 1 月进行，共有 1539 名受访者。JAWS 仍然是最常报告的主要桌面/笔记本电脑屏幕阅读器，占被调查者的 40.5%，尽管使用率相对于 NVDA 有所下降，NVDA 现在是 37.7%的被调查者的主要屏幕阅读器。VoiceOver 的使用率相对稳定，为 9.7%。

### [NodeJS 的吉祥物 - Rocket Turtle](https://www.reddit.com/r/node/comments/1awicty/what_do_you_think_of_nodes_new_mascot_its_called)

一只火箭龟，NodeJS 的[官方文档](https://nodejs.org/en/about)也已经更新了啦!

让我们来看看事情的起源[nodejs/admin --- Have a mascot · Issue #828](https://github.com/nodejs/admin/issues/828)。

## 小贴士

### [Mac 上自带处理图片的命令行工具](https://til.simonwillison.net/macos/sips)

```bash
sips -s format png image.webp --out image.png
sips -j smile.js -o smile.png
```

除了支持图片处理，还支持通过编写 JavaScript 脚本生成图片。

### [专为性能而设计的代码编辑器 Zed](https://zed.dev)

Zed 是一款高性能、多人写作的代码编辑器，由 Atom 和 Tree-sitter 的创建者开发。它也是开源的。

官网首页展示的基准测试上，Zed 在渲染延迟、启动速度、内存占用上都快于 VS Code 和 Sublime Text 4，并且支持 GitHub Copilot。

### [下一代浏览器插件框架](https://wxt.dev)

WXT 可以为 Chrome、Firefox、Edge、Safari 以及任何基于 Chromium 的浏览器构建插件，简化开发过程，并且支持任何支持 Vite Plugin 的前端框架。

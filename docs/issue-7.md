#

## 最前沿

### `Volar Language Features (Volar)` 更名为 `Vue - Official`，并废弃了 `TypeScript Vue Plugin` 扩展

[Vue Language Tools](https://github.com/vuejs/language-tools) 在 3.2 日发布 [v2.0](https://github.com/vuejs/language-tools/releases/tag/v2.0.0)。VS Code 中的 `Volar` 插件已经更名为 `Vue - Official`。此次更新 [Takeover Mode](https://vuejs.org/guide/typescript/overview.html#volar-takeover-mode) 被弃用，之前在工作区禁用 VS Code 内置 TS 插件 `TypeScript and JavaScript Language Features` 的用户将收到 "Takeover mode is no longer needed in version 2.0. Please enable the "TypeScript and JavaScript Language Features" extension." 的警告。

## 好文

[](https://webaim.org/projects/screenreadersurvey10/)

WebAIM 第十次屏幕阅读器用户调查结果现已公布。该调查于 2023 年 12 月和 2024 年 1 月进行，共有 1539 名受访者。JAWS 仍然是最常报告的主要桌面/笔记本电脑屏幕阅读器，占被调查者的 40.5%，尽管使用率相对于 NVDA 有所下降，NVDA 现在是 37.7%的被调查者的主要屏幕阅读器。VoiceOver 的使用率相对稳定，为 9.7%。

## 小提示

### [Mac 上自带处理图片的命令行工具](https://til.simonwillison.net/macos/sips)

```bash
sips -s format png image.webp --out image.png
sips -j smile.js -o smile.png
```

除了支持图片处理，还支持通过编写 JavaScript 脚本生成图片。

### [专为性能而设计的代码编辑器 Zed](https://zed.dev)

Zed 是一款高性能、多人写作的代码编辑器，由 Atom 和 Tree-sitter 的创建者开发。它也是开源的。

官网首页展示的基准测试上，Zed 在渲染延迟、启动速度、内存占用上都快于 VS Code 和 Sublime Text 4，并且支持 GitHub Copilot。

<br>
<p align="center">
<a href="https://sli.dev" target="_blank">
<img src="https://sli.dev/logo-title.png" alt="Slidev" height="250" width="250"/>
</a>
</p>

<p align="center">
为开发者打造的演示文稿工具 🧑‍💻👩‍💻👨‍💻
</p>

<p align="center">
<a href="https://www.npmjs.com/package/@slidev/cli" target="__blank"><img src="https://img.shields.io/npm/v/@slidev/cli?color=2B90B6&label=" alt="NPM version"></a>
<a href="https://www.npmjs.com/package/@slidev/cli" target="__blank"><img alt="NPM Downloads" src="https://img.shields.io/npm/dm/@slidev/cli?color=349dbe&label="></a>
<a href="https://cn.sli.dev/" target="__blank"><img src="https://img.shields.io/static/v1?label=&message=%E4%B8%AD%E6%96%87%E6%96%87%E6%A1%A3&color=45b8cd" alt="Docs & Demos"></a>
<a href="https://cn.sli.dev/themes/gallery.html" target="__blank"><img src="https://img.shields.io/static/v1?label=&message=%E4%B8%BB%E9%A2%98&color=4ec5d4" alt="Themes"></a>
<br>
<a href="https://github.com/slidevjs/slidev" target="__blank"><img alt="GitHub stars" src="https://img.shields.io/github/stars/slidevjs/slidev?style=social"></a>
</p>

<br>
<p align="center">
  <b>简体中文</b> ｜ <a href="https://github.com/slidevjs/slidev#readme">English</a>
</p>
<br>

<p align="center">
<table>
<tbody>
<td align="center">
<img width="2000" height="0"><br>
目前 Slidev 中文文档正在翻译校对过程中 (WIP)<br>
欢迎参与贡献，<a href="https://github.com/slidevjs/docs-cn/issues/8">翻译任务认领说明</a><br>
<img width="2000" height="0">
</td>
</tbody>
</table>
</p>

<br>

## Slidev 中文文档

- 📝 [**Markdown 支持**](https://cn.sli.dev/guide/syntax.html) —— 使用你最喜欢的编辑器和工作流编写 Markdown 文件
- 🧑‍💻 [**对开发者友好**](https://cn.sli.dev/guide/syntax.html#code-blocks) —— 内置代码高亮、实时编码等功能
- 🎨 [**可定制主题**](https://cn.sli.dev/themes/gallery.html) —— 以 npm 包的形式共享、使用主题
- 🌈 [**灵活样式**](https://cn.sli.dev/guide/syntax.html#embedded-styles) —— 使用 [Windi CSS](https://windicss.org/) 按需使用的实用类和易用的内嵌样式表
- 🤹 [**交互**](https://cn.sli.dev/custom/directory-structure.html#components) —— 无缝嵌入 Vue 组件
- 🎙 [**演示者模式**](https://cn.sli.dev/guide/presenter-mode.html) —— 可以使用另一个窗口，甚至是你的手机来控制幻灯片
- 🧮 [**LaTeX 支持**](https://cn.sli.dev/guide/syntax.html#latex) —— 内置了对 LaTeX 数学公示的支持
- 📰 [**图表支持**](https://cn.sli.dev/guide/syntax.html#diagrams) —— 使用文本描述语言创建图表
- 🌟 [**图标**](https://cn.sli.dev/guide/syntax.html#icons) —— 能够直接从任意图标库中获取图标
- 💻 [**编辑器**](https://cn.sli.dev/guide/editors.html) —— 集成的编辑器，或者使用 [VS Code 扩展](https://github.com/slidevjs/slidev-vscode)
- 🎥 [**录制**](https://cn.sli.dev/guide/recording.html) —— 内置录制功能和摄像头视图
- 📤 [**跨平台**](https://cn.sli.dev/guide/exporting.html) —— 能够导出 PDF、PNG 文件，甚至是一个可以托管的单页应用
- ⚡️ [**快速**](https://vitejs.dev) —— 基于 [Vite](https://vitejs.dev) 的即时重载
- 🛠 [**可配置**](https://cn.sli.dev/custom/config-vite.html) —— 支持使用 Vite 插件、Vue 组件以及任何的 npm 包

### 📨 与官网文档同步

目前 Slidev 中文文档正在翻译校对过程中(WIP)。

**同步原理**：[印记中文](https://github.com/docschina) 的机器人每天会拉取 [Slidev 的官网文档](https://github.com/slidevjs/slidev) 的内容，并自动合并到 `sync-docs` 分支，然后会从 `sync-docs` 分支发起自动合并或 PR 到 main 分支。

**仓库维护者**需要**每天**检查该类型的 PR：
- 如无冲突，会自动 merge 到 `main` 分支中；
- 若有冲突，需要先解决 PR 中的冲突，再 merge 到 `main` 分支中。

### 📝 参与贡献

贡献者首先 fork 本仓库，基于 `main` 创建新的翻译分支，进行翻译。翻译完成后，发起到 `main` 的 PR，等待 review，review 通过，仓库维护者将 PR merge。

若需要本地查看网站效果，可以切换到 `site` 分支，并执行如下命令：

```
# 安装依赖，使用 pnpm
$ pnpm install

# 构建文档，site 分支使用了 Git 的 submodules，执行此命令会同时将 docs-cn 同步到 site 分支
$ npm run docs:build

# 启动文档
$ npm run docs
```

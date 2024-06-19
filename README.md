# Tiny Tapeout Verilog 项目模板

- [阅读项目文档](docs/info.md)

## 什么是 Tiny Tapeout？

Tiny Tapeout 是一个教育项目，旨在让您的数字和模拟设计在真实芯片上制造变得比以往任何时候都更容易和更便宜。

了解更多并开始，请访问 https://tinytapeout.com。

## 设置您的 Verilog 项目

1. 将您的 Verilog 文件添加到 `src` 文件夹。
2. 编辑 [info.yaml](info.yaml) 并更新有关您的项目的信息，特别注意 `source_files` 和 `top_module` 属性。如果您正在升级现有的 Tiny Tapeout 项目，请查看我们的 [在线 info.yaml 迁移工具](https://tinytapeout.github.io/tt-yaml-upgrade-tool/)。
3. 编辑 [docs/info.md](docs/info.md) 并添加项目描述。
4. 适应您的设计测试平台。请参阅 [test/README.md](test/README.md) 了解更多信息。

GitHub action 将使用 [OpenLane](https://www.zerotoasiccourse.com/terminology/openlane/) 自动构建 ASIC 文件。

## 启用 GitHub actions 以生成结果页面

- [启用 GitHub Pages](https://tinytapeout.com/faq/#my-github-action-is-failing-on-the-pages-part)

## 资源

- [常见问题](https://tinytapeout.com/faq/)
- [数字设计课程](https://tinytapeout.com/digital_design/)
- [了解半导体如何工作](https://tinytapeout.com/siliwiz/)
- [加入社区](https://tinytapeout.com/discord)
- [在本地构建您的设计](https://www.tinytapeout.com/guides/local-hardening/)

## 接下来做什么？

- [提交您的设计到下一个航班](https://app.tinytapeout.com/)。
- 编辑 [这个 README](README.md) 并解释您的设计、它是如何工作的以及如何测试它。
- 在您选择的社交网络上分享您的项目：
  - LinkedIn [#tinytapeout](https://www.linkedin.com/search/results/content/?keywords=%23tinytapeout) [@TinyTapeout](https://www.linkedin.com/company/100708654/)
  - Mastodon [#tinytapeout](https://chaos.social/tags/tinytapeout) [@matthewvenn](https://chaos.social/@matthewvenn)
  - X (前 Twitter) [#tinytapeout](https://twitter.com/hashtag/tinytapeout) [@tinytapeout](https://twitter.com/tinytapeout)
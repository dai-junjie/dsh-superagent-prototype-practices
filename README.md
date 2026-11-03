# dsh-superagent-prototype 实践与技术报告

记录 [dsh-superagent-prototype](https://github.com/dai-junjie/dsh-superagent-prototype) 的技术解读和可复现的实践案例。

## 参考资料

- [原文（微信公众号）](https://mp.weixin.qq.com/s/zoS7GlReWPhfCjENGxXCdg)
- [官方仓库：dsh-superagent-prototype](https://github.com/dai-junjie/dsh-superagent-prototype)
- [非官方中文翻译：项目理念](https://github.com/saltapp/dsh-superagent-prototype-cn/blob/main/docs/000-philosophy-zh.md)：社区译文，理解项目与核对实现时请同时参考官方仓库。

## 内容导航

- [技术解读](docs/README.md)：架构、工作机制和技术报告。
- [实践案例](practices/README.md)：以目标、步骤、结果和踩坑为主线的可复现案例。
- [配图与附件](assets/README.md)：文章引用的图片和其他静态资源。

## 从哪里开始

已有一篇 [Superagent 特性验证记录](practices/superagent-feature-verification.md)，包含 Inline / Spill 的一次长消息实测、复现方法与未验证边界。新增实践可以继续使用目录说明和写作模板。

1. 选择一个能独立验证结果的小目标，明确输入和预期输出。
2. 复制[最小实践模板](practices/_template.md)，在 `practices/` 下创建文章，例如 `first-practice.md`。
3. 按模板写清环境、操作步骤、实际结果和踩坑；从头复现一次，并将文章加入[实践案例索引](practices/README.md)。
4. 配图放入 `assets/<文章名>/`，在文章中用相对路径引用。

目前使用 Markdown 和目录索引组织内容，暂不搭建文档站。

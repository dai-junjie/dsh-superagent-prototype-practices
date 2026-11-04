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

想了解 Superagent 能怎样帮助团队，先读[生产实践与 Codex 分工](practices/README.md#生产实践)：跨飞书和 GitHub 跟进任务、多人独立任务并行、按授权规则主动跟进反馈。Codex 仍是主力编码工具，Superagent 补足团队入口和持续协作，不是替代关系。

想动手理解技术链路，读[基础练习](practices/basics/README.md)。基础练习保留操作步骤和记录表；生产实践以工作场景和分工为主。当前内容分别是待执行的练习与场景化示例，尚无实测收益结论。

1. 选择一个能独立验证结果的小目标，明确输入和预期输出。
2. 复制[最小实践模板](practices/_template.md)，在 `practices/` 下创建文章，例如 `first-practice.md`。
3. 按模板写清环境、操作步骤、实际结果和踩坑；从头复现一次，并将文章加入[实践案例索引](practices/README.md)。
4. 配图放入 `assets/<文章名>/`，在文章中用相对路径引用。

目前使用 Markdown 和目录索引组织内容，暂不搭建文档站。

## 验证记录

飞书测试群 `superagent-test` 已跑通。

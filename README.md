# TheoremOS

数学 Agent 的研究运行时。连接你的模型，构造 Lean 与 Mathlib 证明，由独立 Lean 流程验收完整原题。

- 官网：https://likc1606.github.io/theorem-os-site/
- 证明档案：https://likc1606.github.io/theorem-os-site/archive.html
- 反馈与建议：https://likc1606.github.io/theorem-os-site/feedback.html，或直接[提交 Issue](https://github.com/LikC1606/theorem-os-site/issues/new)

**在线工作台即将开放。** 开放后，可以在浏览器中提交原题、使用自己的 API Key（OpenAI 及兼容 Responses API 的服务）开始研究，并下载 Lean 源码与验收报告。

## 仓库内容

本仓库是 TheoremOS 官网与公开研究成果，不包含 TheoremOS 运行时源码。

| 路径 | 内容 |
| --- | --- |
| `index.html`、`archive.html`、`feedback.html` 及同级资源 | 官网、证明档案与反馈页面（构建产物） |
| `accepted/` | 具备 Lean-Eval 官方通过记录的证明包，`accepted.json` 记录原题版本、来源、模型归属、官方回复与 SHA-256 |
| `submitted/` | 在 [Lean-Eval #2144](https://github.com/leanprover/lean-eval-submissions/issues/2144) 获得 4/4 通过的提交包 |
| `in-progress/` | 证明档案引用的研究快照源码，未经官方验收 |
| `data/catalog.json` | 证明档案的完整数据 |

证明包内的文件按归档时的提交包逐字节保存。官方验收以链接的 Lean-Eval 回复为准；本地 `verification.json` 只记录特定源码与环境下的检查。

成果来自前身 DeepScientist / DeepScientist Math 及后续工作，原始归属见各题档案。

## 反馈

欢迎在 [Issues](https://github.com/LikC1606/theorem-os-site/issues) 提出问题、需求和建议。官网的[反馈页面](https://likc1606.github.io/theorem-os-site/feedback.html)会帮你整理成 Issue。

## 许可

TheoremOS 为闭源软件，保留所有权利。本仓库中的字体、图标等第三方组件按各自许可分发，许可文件随附于 `assets/fonts`、`assets/licenses` 与 `lucide-LICENSE.txt`。

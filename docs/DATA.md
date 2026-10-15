# 数据与候选审核资料

本仓库收录的是个人实验记录和既有审核资料，没有重新开展2000题审核，也没有重新导出整套训练数据。

## 审核PDF的范围

[全部2000题_已加审核批注.pdf](全部2000题_已加审核批注.pdf) 是2026-10-13形成的候选批注册，共2001页（含册首），文件大小24,544,162字节。按用户指定原文件逐字节复制，SHA256：

```text
a0be4385e52ac896e388bfad7d993106c59971712b2348ccf58586f232f86bda
```

PDF是2000道**训练候选**的历史审核记录，不包含另外200道开发候选的完整审核册，不代表2000道均通过，也不是最终953条训练样本导出。后续还有修订、关联隔离和去重；最终训练953、可评分开发161、开发侧另保留39道不评分题。批注“认可”不等于独立专家完成了全部数学证明认证。

## 数据来源

- Geometry3K / InterGPS：[原始项目](https://github.com/lupantech/InterGPS)。
- Geo170K / G-LLaVA：[原始项目](https://github.com/pipilurj/G-LLaVA)。
- MathV360K / Math-LLaVA：[原始项目](https://github.com/HZQ950419/Math-LLaVA)。
- 基座模型：[Qwen2.5-VL-3B-Instruct](https://huggingface.co/Qwen/Qwen2.5-VL-3B-Instruct)。
- GRPO方法出处：[DeepSeekMath](https://arxiv.org/abs/2402.03300)。

不同来源可能含关联图和改写题，因此最终划分做过关联题隔离；这不保证消除了所有未知语义关联。数据、题图及既有许可归各原始来源，本记录不将整个混合资料统一声明为新的开源数据许可。[Geometry3K既有署名文件](licenses/Geometry3K_SOURCE_LICENSE)按本地资料保留，其文本不代表其他数据来源的许可。

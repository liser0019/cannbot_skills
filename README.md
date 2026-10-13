# cannbot_skills

 cannbot 技能（Skills）集合，共 144 个技能，覆盖昇腾（Ascend）CANN 生态下的算子开发、图引擎、推理与训练调优、工具链等场景。

## 技能分类

| 类别 | 说明 | 示例 |
|------|------|------|
| AscendC 算子开发 | AscendC 算子设计、编码、调试、性能优化 | `ascendc-op-design`、`ascendc-code-review`、`ascendc-perf-optimize` |
| PyPTO / Catlass | PyPTO 与 Catlass 算子开发与调优 | `pypto-op-develop`、`catlass-op-design` |
| TileLang | TileLang 算子开发与最佳实践 | `tilelang-op-develop`、`tilelang-performance-best-practices` |
| Triton | Triton 算子设计、编码、验证 | `triton-op-designer`、`triton-op-coding` |
| 图引擎（GE） | 图引擎诊断、算子插件开发 | `ge-fusion-pass-skill`、`ge-memory-analysis` |
| 推理与训练 | 模型推理、训练精度与性能分析 | `model-infer-profiling`、`model-train-oom-analysis` |
| 工具链 | NPU 检测、dump、profiling 工具 | `tool-npu-check`、`ops-profiling` |
| 工作流 | 算子开发流程（CP0–CP5）等 | `workflow-cp0`、`ops-direct-invoke-workflow` |

## 目录结构

每个技能是一个独立目录，通常包含：

```
skill-name/
├── SKILL.md        # 技能定义（触发条件、使用说明）
├── core/           # 核心逻辑
├── steps/          # 分步指引
├── workflows/      # 工作流定义
├── references/     # 参考资料
├── scripts/        # 配套脚本
└── evals/          # 评测用例
```

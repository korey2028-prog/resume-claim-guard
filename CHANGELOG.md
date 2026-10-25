# 改动记录

## v1.0（2026-10-25）

从“简历事实审计”扩展为“从 JD 到面试”的完整流程。

- 新增定向模式：拆 JD → 反问经历 → 要求—证据匹配与投递建议 → 写定向简历 → 体检与面试追问预演。
- 新增 `references/`：拆 JD、反问经历、写定向简历、逐句体检、面试预演、输出格式各一份细则；`SKILL.md` 只保留入口和流程。
- 新增 `templates/facts.md` 事实清单模板、`agents/openai.yaml`、`scripts/validate.py` 和 GitHub Actions 自检。
- 新增完整示例 `examples/jd-to-interview/`。
- `PROMPT.md` 改为网页版五步流程。
- 原有体检规则（五种证据状态、两条轴动词上限、底稿自检、PDF、跨版本对比、过期与作废、内部编号）不变，移入 `references/claim-audit.md`。

## v0.1（2026-10-25）

- 简历主张审计：五种证据状态、两条轴动词上限、追问 / 对比 / 直接三种入口、网页版提示词、两个虚构示例。

# 贡献指南

参与协作请遵守 [社区行为准则](CODE_OF_CONDUCT.md)。

欢迎改进教学流程、平台兼容性与文档。提交前说明问题、改动和验证结果。
教学规则优先保持简洁、可追溯，不把单一例外扩展成复杂的通用流程。

```text
python -m pip install websockets pycryptodome
python -m unittest discover -s tests -v
python scripts/nuaa_aes.py self-test
```

修改教学流程时对照 [行为案例](tests/skill_cases.md) 检查；脚本测试不代表真实辅导已验证。
不要提交真实课程资料、账号信息、登录态、二维码或学习记录。报告问题使用脱敏材料。
保留上游版权和来源；新增依赖说明用途和许可。

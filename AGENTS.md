# 维护约定

本仓库是 `nuaaft` Agent Skill，中文名“南航飞天云课堂AI技能”。
SKILL.md 保持精简；取数、教学与记录细节分别放 references/，不要重复维护同一规则。
agents/openai.yaml 与 Skill 名称保持一致。保留 LICENSE 与上游署名。

验证：`python -m unittest discover -s tests -v`、`python scripts/nuaa_aes.py self-test`。
行为验收见 tests/skill_cases.md，未执行真实登录/教学时不得宣称通过。
不提交登录态、二维码、课程材料或学习记录，不在无授权时发布或修改远端设置。

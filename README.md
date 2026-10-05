<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/Chinese-0969da?style=for-the-badge" alt="简体中文" /></a>
  <a href="README.en.md"><img src="https://img.shields.io/badge/English-555555?style=for-the-badge" alt="English" /></a>
  <a href="README.ja.md"><img src="https://img.shields.io/badge/Japanese-555555?style=for-the-badge" alt="日本語" /></a>
</p>

# 网站设计方案撰写 Skill

将网站需求、现有方案和设计稿整理成可评审、可交付的设计方案，覆盖目标拆解、页面结构、交互规则、UI 标注、多端差异和验收要求。

适用于整站新建或改版、单功能迭代，以及设计文档的补全与评审。此 skill 负责方案写作，不直接开发或发布网站。

## 使用

将仓库克隆到 Codex 的 skills 目录：

```bash
git clone https://github.com/cloud-oc/website-design-proposal.git ~/.codex/skills/website-design-proposal
```

调用示例：

```text
用 $website-design-proposal，根据这些需求撰写网站设计方案。
```

提供网站类型、目标用户、核心行动、本期范围、设备端，以及已有需求或设计稿。信息不完整时，skill 会区分已确认事实、设计建议和待确认项。

## 文件

- `SKILL.md`：核心流程与写作要求。
- `references/proposal-framework.md`：可裁剪的方案框架。
- `references/module-guide.md`：资讯、预约、查询、落地页等模块指南。
- `references/source-notes.md`：来源与提炼边界。
- `agents/openai.yaml`：Codex UI 元数据。

Skill 指令与参考文档使用中文；需要其他语言的方案时，可在调用时指定输出语言。

原始项目图稿不随仓库分发，使用不依赖原始本地目录或外部设计链接。

## 协议

[MIT](LICENSE)

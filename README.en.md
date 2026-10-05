<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/Chinese-555555?style=for-the-badge" alt="简体中文" /></a>
  <a href="README.en.md"><img src="https://img.shields.io/badge/English-0969da?style=for-the-badge" alt="English" /></a>
  <a href="README.ja.md"><img src="https://img.shields.io/badge/Japanese-555555?style=for-the-badge" alt="日本語" /></a>
</p>

# Website Design Proposal Skill

Turn website requirements, existing proposals, and design mockups into a design proposal ready for review and handoff. Covers goal breakdown, page structure, interaction rules, UI annotations, cross-device differences, and acceptance criteria.

Use it for new websites, redesigns, individual feature updates, and improving or reviewing design documents. This skill writes proposals; it does not directly build or publish websites.

## Usage

Clone this repository into your Codex skills directory:

```bash
git clone https://github.com/cloud-oc/website-design-proposal.git ~/.codex/skills/website-design-proposal
```

Example prompt:

```text
Use $website-design-proposal to write a website design proposal based on these requirements. Write the proposal in English.
```

Provide the website type, target audience, primary user action, scope, target devices, and any existing requirements or mockups. When information is incomplete, the skill distinguishes confirmed facts, design recommendations, and items requiring confirmation.

## Files

- `SKILL.md`: Core workflow and writing requirements.
- `references/proposal-framework.md`: A proposal framework that can be adapted to the scope.
- `references/module-guide.md`: Guidance for news, reservations, result queries, landing pages, and other modules.
- `references/source-notes.md`: Source material and the boundaries of the extracted guidance.
- `agents/openai.yaml`: Codex UI metadata.

The skill instructions and reference documents are written in Chinese. Specify the desired output language in your prompt, as shown above.

Original project mockups are not distributed with this repository. The skill does not require the original local directory or external design links.

## License

[MIT](LICENSE)

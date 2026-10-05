<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/Chinese-555555?style=for-the-badge" alt="简体中文" /></a>
  <a href="README.en.md"><img src="https://img.shields.io/badge/English-555555?style=for-the-badge" alt="English" /></a>
  <a href="README.ja.md"><img src="https://img.shields.io/badge/Japanese-0969da?style=for-the-badge" alt="日本語" /></a>
</p>

# Webサイト設計提案書作成 Skill

Webサイトの要件、既存の提案書、デザイン案をもとに、レビューや引き継ぎに使える設計提案書を作成します。目標の整理、ページ構成、インタラクションのルール、UIの注釈、デバイスごとの差分、受け入れ基準を扱います。

Webサイトの新規企画やリニューアル、個別機能の改修、設計ドキュメントの補完・レビューに利用できます。このskillは提案書を作成するもので、Webサイトの実装や公開は行いません。

## 使い方

Codexのskillsディレクトリに、このリポジトリをクローンします。

```bash
git clone https://github.com/cloud-oc/website-design-proposal.git ~/.codex/skills/website-design-proposal
```

プロンプトの例：

```text
$website-design-proposal を使って、これらの要件に基づくWebサイト設計提案書を日本語で作成してください。
```

Webサイトの種類、対象ユーザー、主なユーザー行動、今回の対象範囲、対象デバイス、既存の要件やデザイン案を提供してください。情報が不足している場合は、確認済みの事実、設計上の提案、確認が必要な項目を区別します。

## ファイル構成

- `SKILL.md`：基本の作業フローと執筆要件。
- `references/proposal-framework.md`：対象範囲に合わせて調整できる提案書の構成。
- `references/module-guide.md`：ニュース、事前登録、結果照会、ランディングページなどのモジュール別ガイド。
- `references/global-interactions.md`：共通ナビゲーション、メディア、動き、画面サイズへの対応ガイド。
- `references/source-notes.md`：元資料と、抽出した指針の適用範囲。
- `agents/openai.yaml`：CodexのUIメタデータ。

skillの指示と参考ドキュメントは中国語で書かれています。上記の例のように、プロンプトで出力言語を指定してください。

元プロジェクトのデザイン画像は、このリポジトリには含まれていません。元のローカルディレクトリや外部のデザインリンクがなくても利用できます。

## ライセンス

[MIT](LICENSE)

# shukatsu-skills

就活・転職活動を支援するAIエージェントスキル集。
対話形式のインタビューによる自己分析と、体系的な面接対策を提供する。

## スキル一覧

| スキル | 概要 |
|--------|------|
| [self-analysis](skills/self-analysis/) | 対話形式のインタビューで経験・価値観・強み・弱みを引き出し、客観的な自己分析レポートを生成する |
| [interview-prep](skills/interview-prep/) | 模擬面接・回答作成・回答添削の3モードで面接対策を支援する |

## インストール

```bash
npx skills add manmaru-ai/shukatsu-skills
```

または個別にインストール:

```bash
npx skills add manmaru-ai/shukatsu-skills/skills/self-analysis
npx skills add manmaru-ai/shukatsu-skills/skills/interview-prep
```

## 使い方

### 自己分析

スキルをインストール後、エージェントに以下のように話しかける:

- 「自己分析をしたい」
- 「就活の準備を始めたい」
- 「自分の強み・弱みを知りたい」
- 「自己PRを作りたい」
- 「ガクチカを書きたい」

エージェントが対話形式でインタビューを行い、回答をもとに自己分析レポートを自動生成する。

### 面接対策

- 「面接対策をしたい」
- 「模擬面接をしてほしい」
- 「面接の回答を作りたい」
- 「面接で聞かれる質問の準備をしたい」

エージェントが面接官役として模擬面接を実施したり、頻出質問への回答作成を支援する。

## 対応エージェント

- Cursor
- Claude Code
- Codex
- その他 Skills 対応エージェント

## ライセンス

MIT License

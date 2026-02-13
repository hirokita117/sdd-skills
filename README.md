# sdd-skills

企業で仕様駆動開発（Spec-Driven Development）を実現するためのスキル・カスタムコマンドを管理するリポジトリです。

## 想定ディレクトリ構成

本リポジトリのスキルを利用する際に想定するプロジェクト構成です。

```
<your-org>/
├── teams/
│   └── <チーム名>/
│       └── <プロジェクト名>/
│           ├── discovery/ …企画・ディスカバリー
│           │   ├── prd.md                             # PRD（プロダクト要求仕様書）
│           │   └── user-stories/                      # 要求に基づく個別の振る舞い
│           │       └── example-user-story.md
│           ├── design/ …設計
│           │   ├── design-docs/                       # Design Doc / RFC（技術設計書）
│           │   │   └── example-design-doc.md
│           │   ├── adr/                               # ADR（Architecture Decision Records）
│           │   │   └── example-adr.md
│           │   ├── nfr.md                             # 非機能要件（Non-Functional Requirements）
│           │   └── data-model.md                      # データモデル / ER図
│           ├── qa/ …テスト・QA
│           │   ├── test-strategy.md                   # テスト戦略・テスト計画書
│           │   ├── nfr.md                             # 非機能要件の QA
│           │   └── user-stories/                      # 個別の振る舞いの QA
│           │       └── example-user-story.feature     # Gherkin ファイル
│           └── operations/ …運用・観測・改善
│               ├── runbook.md                         # Runbook（運用手順書）
│               ├── performance-testing.md             # 負荷検証の記録
│               └── slo-sla.md                         # SLO/SLA 定義
├── products/
│   └── <プロダクト名>/
│       └── ... (TBD)
└── ...
```

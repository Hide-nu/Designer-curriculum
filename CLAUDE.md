# Designer Curriculum Project

## プロジェクト概要
世界トップデザインスクール（RCA、Parsons、RISD）の2026年カリキュラムを分析・統合した、次世代デザイン教育の包括的カリキュラム。7冊の本で構成される。

## 技術スタック
- MkDocs + Material for MkDocs
- Mermaid.js（ダイアグラム）
- GitHub Pages（ホスティング）

## ディレクトリ構造
```
docs/
├── index.md                    # ホームページ
├── curriculum-overview.md      # カリキュラム概要
├── books/
│   ├── 01-design-thinking/     # Book 1: デザイン思考の基礎
│   ├── 02-design-futures/      # Book 2: デザイン・フューチャーズ（RCA）
│   ├── 03-social-transformation/ # Book 3: 社会変革デザイン（Parsons）
│   ├── 04-critical-making/     # Book 4: クリティカル・メイキング（RISD）
│   ├── 05-ai-partnership/      # Book 5: AIパートナーシップデザイン
│   ├── 06-sustainable-design/  # Book 6: サステナブルデザイン
│   └── 07-design-strategy/     # Book 7: デザイン戦略とリーダーシップ
├── learning-graph/             # 学習グラフ（概念依存関係）
├── glossary.md                 # 用語集
└── references.md               # 参考文献
```

## 各Bookの章構成
- 各Bookは5章で構成
- 各章は800-1200語（日本語）
- 章末に実践演習を含む
- Mermaidダイアグラム、テーブル、admonitionを活用

## コンテンツ規約
- 言語: 日本語
- マークダウン拡張: admonition, mermaid, tabbed, pymdownx
- リスト前には空行を入れる（MkDocs要件）
- ファイル名: kebab-case
- 概念名: タイトルケース（英語）/ カタカナ（日本語）

## 教育フレームワーク
- ブルームのタキソノミー（2001年改訂版）を学習目標に適用
- ISO 11179準拠の用語定義
- 学習グラフ: DAG（有向非循環グラフ）で概念依存関係を表現

## 設計原則
1. 理論と実践の均衡
2. AI共生（全科目でAIを協働パートナーとして活用）
3. サステナビリティ必須
4. 批判的視座の維持
5. 反転スタジオモデルの採用

# Naoki Kaneko

CGパイプラインエンジニアを目指しています。IT保守・Web制作の実務経験をベースに、Houdini/DCCツールとPythonを組み合わせたパイプライン開発に注力しています。

## Pipeline Tools Portfolio

| プロジェクト | 概要 | 技術 |
|---|---|---|
| [**pipeinit**](https://github.com/nokgc333/pipeinit) | プロジェクトフォルダ構成をルールYAMLから自動生成・命名規則を検証するCLI | Python / Click / PyYAML |
| [**scene-doctor**](https://github.com/nokgc333/scene-doctor) | Houdiniシーンのジオメトリ欠陥・ノード構造・命名違反を自動検出するHDA/PDGツール | Python / Houdini(hython) / PDG |
| [**pipeboard**](https://github.com/nokgc333/pipeboard) | ショット/アセット管理カンバンボード。Houdiniからステータス更新できる連携スクリプト付き | FastAPI / SQLAlchemy / Next.js / React |

いずれもTDD（RED-GREEN-REFACTOR）で実装し、実際のHoudini環境での動作確認まで実施しています。詳細は各リポジトリのREADME・docs/を参照してください。

## Tech Stack

- **DCC連携**: Houdini (hython, HDA, PDG/TOPs)
- **Backend**: Python, FastAPI, SQLAlchemy
- **Frontend**: TypeScript, Next.js, React
- **開発手法**: TDD, Ports & Adapters, ADR (Architecture Decision Records)

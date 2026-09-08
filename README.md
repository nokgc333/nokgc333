# Naoki Kaneko

CGパイプラインエンジニアを目指しています。IT保守・Web制作の実務経験をベースに、Houdini/Blender/DCCツールとPythonを組み合わせたパイプライン開発に注力しています。

## Pipeline Tools Portfolio

| プロジェクト | 概要 | 技術 |
|---|---|---|
| [**pipeinit**](https://github.com/nokgc333/pipeinit) | プロジェクトフォルダ構成をルールYAMLから自動生成・命名規則を検証するCLI | Python / Click / PyYAML |
| [**scene-doctor**](https://github.com/nokgc333/scene-doctor) | Houdiniシーンのジオメトリ欠陥・ノード構造・命名違反を自動検出するHDA/PDGツール。Houdini内蔵PySide6のカスタムドッキングパネルも搭載 | Python / Houdini(hython) / PDG / PySide6 |
| [**pipeboard**](https://github.com/nokgc333/pipeboard) | ショット/アセット管理カンバンボード。同一バックエンドをWeb(Next.js)とPySide6デスクトップクライアントの両方から利用可能 | FastAPI / SQLAlchemy / Next.js / React / PySide6 |
| [**queuewatch**](https://github.com/nokgc333/queuewatch) | レンダー/タスクキュー監視ダッシュボード。失敗ジョブの自動リトライ・稼働率可視化 | FastAPI / Celery / Redis / React |
| [**unibridge**](https://github.com/nokgc333/unibridge) | Houdini↔BlenderのUSD相互変換・検証ツール。座標系/スケール不整合を自動検出 | Python / OpenUSD(usd-core) / Houdini / Blender |

いずれもTDD（RED-GREEN-REFACTOR）・Ports & Adapters設計・ADR（設計判断の明文化）を共通の作法として実装し、実際のHoudini/Blender環境での動作確認まで実施しています。詳細は各リポジトリのREADME・docs/を参照してください。

## Tech Stack

- **DCC連携**: Houdini (hython, HDA, PDG/TOPs), Blender (bpy)
- **データ交換**: OpenUSD (usd-core)
- **Backend**: Python, FastAPI, SQLAlchemy, Celery
- **Frontend**: TypeScript, Next.js, React, Vite
- **Desktop GUI**: PySide6 (Qt)
- **開発手法**: TDD, Ports & Adapters, ADR (Architecture Decision Records)

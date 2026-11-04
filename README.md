# Naoki Kaneko

CG パイプラインエンジニア / テクニカルアーティストを目指しています。IT保守と Web 制作の実務経験をもとに、Houdini・Blender・OpenUSD と Python で、制作の流れを支えるツールを作っています。

- サイト: https://naokikaneko.com

## 代表作

- [naokikaneko](https://github.com/nokgc333/naokikaneko): 個人のポートフォリオサイト（実績・ブログ・お問い合わせ）。Next.js・TypeScript・Tailwind CSS
- [scene-doctor](https://github.com/nokgc333/scene-doctor): Houdini のシーンの欠陥・ノード構造・命名違反を検出する HDA/PDG ツール。Houdini 内蔵の PySide6 パネルつき
- [pipeboard](https://github.com/nokgc333/pipeboard): ショット/アセット管理のカンバン。同じバックエンドを、Web（Next.js）と PySide6 のデスクトップクライアントの両方から使う
- [queuewatch](https://github.com/nokgc333/queuewatch): レンダー/タスクキューの監視ダッシュボード。失敗ジョブの自動リトライと、稼働率の可視化
- [unibridge](https://github.com/nokgc333/unibridge): Houdini と Blender の間で受け渡す USD の整合検査ツール。座標系・スケール・命名の不整合を検出する
- [pipeinit](https://github.com/nokgc333/pipeinit): ルールの YAML から、プロジェクトのフォルダを作り、命名規則を検証する CLI

ほかに、[frame-slicer](https://github.com/nokgc333/frame-slicer)（フレーム範囲を分割して QueueWatch に投入する CLI）と、[space-log](https://github.com/nokgc333/space-log)（架空の CG スタジオのサイト）があります。

## 進め方

どのリポジトリも、TDD（RED-GREEN-REFACTOR）、Ports & Adapters の設計、ADR（設計判断の記録）を共通の作法にしています。実機で確かめた範囲と、確かめていない範囲は、各リポジトリの README の「検証」「既知の制限事項」に書いています。

## 技術

- DCC 連携: Houdini（hython・HDA・PDG）、Blender（bpy）
- データ交換: OpenUSD（usd-core）
- バックエンド: Python、FastAPI、SQLAlchemy、Celery
- フロントエンド: TypeScript、Next.js、React
- デスクトップ: PySide6（Qt）

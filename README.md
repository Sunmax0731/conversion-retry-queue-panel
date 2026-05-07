# 変換キュー・再実行パネル

conversion-retry-queue-panel は 素材変換、再試行、ログ確認をまとめたい制作者/開発者 向けの closed alpha プロダクトです。変換ジョブ、入力、出力、失敗理由、再実行条件をキューとして管理する。

## Source

- PICKUP Rank: 56
- Domain / Idea No: AssetPipeline / 11
- Repository: conversion-retry-queue-panel
- 主な公開先: GitHub Release / BOOTH
- created_idea: `D:/AI/AssetPipeline/created_idea_011_conversion-retry-queue-panel`
- 同梱ZIP: `D:/AI/AssetPipeline/created_idea_011_conversion-retry-queue-panel/idea_011_conversion-retry-queue-panel.zip`
- 開始時 README: 存在しない


## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- src/cli/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/conversion-retry-queue-panel-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。


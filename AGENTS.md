# Codex作業規約

フォルダごとの役割と成果物は [docs/README.md](docs/README.md) に従う。

- `Approved` 状態の要件IDに基づいてのみ実装する。
- 根拠のない内容を仕様として補完しない。不明点は質問または仮定に記録する。
- 実装前に影響範囲、変更予定ファイル、テスト計画、不明点を提示する。
- 既存動作を変更する場合は、回帰範囲と後方互換性を確認する。
- 完了時に要件ID、変更ファイル、テスト結果、残課題を報告する。
- 見積では、作業分解・前提・リスク・変更差分を整理する。単価、生産性、予備費率、最終金額を推測しない。
- 見積の内部計算は `docs/estimates/internal_estimate_calculator.xlsx`、顧客提示は `client_estimate_share_template.xlsx` を用いる。内部ブックを顧客共有用に作り替えない。

## 参照順序

1. `PROJECT_CONTEXT.md` と `docs/specification_governance.md`
2. `docs/decisions/` の承認済み決定
3. `docs/03_requirements/` の承認済み要件
4. 基本・詳細設計
5. 質問・仮定・不整合一覧
6. 現行コードとテスト

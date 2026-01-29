# codepipeline-path-filter-demo

AWS CodePipeline のパスフィルタ機能を検証するためのリポジトリです。

## 関連記事

https://zenn.dev/toshiro3/articles/codepipeline-path-filter

## ディレクトリ構成

```
├── app/          # パスフィルタ対象
├── src/          # パスフィルタ対象
├── docs/         # パスフィルタ対象外
└── infra/        # CloudFormation テンプレート
```

## 検証内容

- パスフィルタの基本設定（コンソール / CLI / CloudFormation）
- 複数パスの指定（OR条件）
- 除外パターンの設定

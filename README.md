# Recustomer-working-agreement

## 目的

> ワーキングアグリーメントを作成することでチームメンバー間のお互いの期待を明確にし、価値観を共有することができる。また、生産性を高め、心のゆとりを生み出すことができる。
> 引用
> https://www.agile-studio.jp/post/apm-working-agreement

## Recustomer-working-agreement

(追記したい場合には、この行以降に追加してください)

### コミュニケーション

- 他メンバーに相談事項がある際、事前連絡なしで Slack のハドルをかけて良い。

### Github 運用

- 対象リポジトリのデフォルトブランチから、開発用ブランチを作成し開発を進める
- ブランチ名は、Linear の issue と紐づくように設定する
- 開発が完了したら、マージしたいブランチに向けて Pull Request を作成する
- レビュワーは 1 人以上設定する。設定するレビュワーは、そのリポジトリまたは該当機能に詳しいメンバーを設定する
- リポジトリに設定されている全ての CI が成功したら、レビュワーにメンションをつけてレビュー依頼をする
- Pull Request が Approve されたら、Pull Request 作成者がマージする
- 基本的にデフォルトブランチに直接修正コードを push しない。ただしやむを得ない時には、事前に他エンジニアに連絡した上でデフォルトブランチに push しても良い

### Setup

- Slack上で`/github signin`でSlackと自身のGitHubアカウントを連携してください
- LinearとSlackを連携してLinearからSlackに対して通知が来るようにてください

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
- 開発が途中の状態で、一時的にGitHubにPRを上げたい場合は、マージしたいブランチに向けて、**Draft Pull Request** を作成する
- 開発が完了したら、マージしたいブランチに向けて Pull Request を作成する
- 変更行数が20行以下の場合は、些細な変更の可能性が高いため、レビュワーはcoderabbitのAIだけで問題はない
- レビュワーは 1 人以上設定する。設定するレビュワーは、そのリポジトリまたは該当機能に詳しいメンバーを設定する
- リポジトリに設定されている全ての CI が成功したら、レビュワーにメンションをつけてレビュー依頼をする
- Pull Request が Approve されたら、Pull Request 作成者がマージする
- 基本的にデフォルトブランチに直接修正コードを push しない。ただしやむを得ない時には、事前に他エンジニアに連絡した上でデフォルトブランチに push しても良い

### Setup

- Slack上で`/github signin`でSlackと自身のGitHubアカウントを連携してください
- LinearとSlackを連携してLinearからSlackに対して通知が来るようにてください


### Daily Stand up

- リモートワークする場合、slackの「-all-greetings」チャンネルでリモートすることを全体に周知する(正社員)
- 体調不良などで急遽有休を取得する場合、slackの「-all-greetings」チャンネルで全体に周知する(正社員)
- 稼働前にslackの「dev-daily」」チャンネルの「Daily Standup」ワークフローから送信されるメッセージのスレッドに下記を入力する。正社員については後述のDaily standup mtg前に記入する
    - 前日の対応
    - 本日の予定
- 10:15より、Daily Standup MTGを行う。
    - slackの「dev-daily」」チャンネルのハドルで行う。カメラOffで問題ない
    - 「前日の対応」「本日の予定」を共有する

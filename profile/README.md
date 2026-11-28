# mabu-bots

まぶが個人開発する **Discord Bot** の組織です。
コミュニティ運営、読み上げ、サーバーの自動化やツール系 Bot を作っています。

- 👤 開発者: [@i-mabu](https://github.com/i-mabu)
- 🌐 Web サービスの組織: [@mabu-works](https://github.com/mabu-works)
- 💬 コミュニティ「まぶ鯖」: [discord.gg/GKkW4wCAVp](https://discord.gg/GKkW4wCAVp)

## Bot 一覧

### まぶ鯖向け

| Bot | 内容 |
| --- | --- |
| [mabubot](https://github.com/mabu-bots/mabubot) | コミュニティ向け多機能 Bot（まぶさば） |
| [mabubot-play](https://github.com/mabu-bots/mabubot-play) | ゲームとレベルシステム（まぶのゲーム） |
| [mabubot-guard](https://github.com/mabu-bots/mabubot-guard) | モデレーションと荒らし対策（まぶのみまもり） |
| [mabubot-ops](https://github.com/mabu-bots/mabubot-ops) | 歓迎・投票・募集などの運営自動化（まぶのおてつだい） |

### 水無瀬組向け

| Bot | 内容 |
| --- | --- |
| [suzushiro](https://github.com/mabu-bots/suzushiro) | おみくじ・今日のコンテンツと、ポイント制ゲーム9種 |

### 夜凪鯖向け

| Bot | 内容 |
| --- | --- |
| [p1228](https://github.com/mabu-bots/p1228) | VOICEVOX 読み上げと AI 連携の Bot システム（TypeScript） |
| p1228-java | p1228 の Java 移植版 |

### 拡張基盤

| Bot | 内容 |
| --- | --- |
| [FORGE](https://github.com/mabu-bots/forgebot) | Blueprint（Trigger + Condition + Action + Persona）でサーバー自動化を組み立てる拡張型 Bot |

### ツール系

| Bot | 内容 |
| --- | --- |
| [makeitaquote-bot](https://github.com/mabu-bots/makeitaquote-bot) / [makeitaquote-bot-py](https://github.com/mabu-bots/makeitaquote-bot-py) | 発言を引用画像にする Bot（TypeScript 版 / Python 版） |
| [fake-tweet-bot](https://github.com/mabu-bots/fake-tweet-bot) | ツイート風画像を作る Bot |
| [chat-topic-bot](https://github.com/mabu-bots/chat-topic-bot) | 雑談の話題を出す Bot |
| [playlist-pool-bot](https://github.com/mabu-bots/playlist-pool-bot) | 曲を持ち寄って週次プレイリストを作る Bot |
| [event-recruit-bot](https://github.com/mabu-bots/event-recruit-bot) | イベント募集を管理する Bot |
| [invite-tracker-bot](https://github.com/mabu-bots/invite-tracker-bot) | 招待リンクの生成・使用記録・通知をする Bot |
| reishou-bot | 自分の発言の「冷笑っぽさ」をセルフチェックする Bot（非公開） |
| [test-partner-bot](https://github.com/mabu-bots/test-partner-bot) | Bot のテストを自動で相手する Bot |

### 運用

| Bot | 内容 |
| --- | --- |
| [logbot](https://github.com/mabu-bots/logbot) | サーバーのログ収集 Bot |
| server-guard | サーバーと Bot の死活監視スクリプト（非公開） |

## 技術メモ

- 主な言語: TypeScript（discord.js）/ Python（discord.py）/ Java
- 全 Bot に接続監視（READY ウォッチドッグ）を搭載し、異常時は自動で再起動する構成
- リポジトリは一部を除き公開しています

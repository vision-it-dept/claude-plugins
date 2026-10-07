# Vision Inc. Claude Code プラグイン

[English](README.md) | 日本語

Vision Inc. が公開している Claude Code プラグインです。

## プラグイン一覧

| プラグイン | 説明 |
|---|---|
| [security-audit](plugins/security-audit/) | 自社が管理する、または診断の許可を得た Web サイト・API を標準手順で脆弱性診断します。網羅的な診断（OWASP Top 10、API、設定）と、重大な脆弱性に絞った緊急トリアージの 2 つです。 |

## インストール

このマーケットプレイスを Claude Code に追加します。

```sh
claude plugin marketplace add vision-it-dept/claude-plugins
```

続けて、プラグイン名を指定してインストールします（例: `claude plugin install security-audit@vision-net`）。前提条件・使い方・アップデート方法は各プラグインの README を参照してください。

## サポート

サポートはベストエフォートです。Issue への回答や不具合の修正は保証しません。

- 不具合・誤検知・質問: [Issue を作成](https://github.com/vision-it-dept/claude-plugins/issues/new/choose)してください。英語・日本語のどちらで書いても構いません。
- プラグイン自体の脆弱性: 公開の Issue にはせず、[SECURITY.md](SECURITY.md) の手順で非公開で報告してください。

## コントリビューション

外部からのコードの提供（プルリクエスト）は受け付けていません。ご提案は [Issue](https://github.com/vision-it-dept/claude-plugins/issues/new/choose) でお寄せください。

## ライセンス

[MIT](LICENSE)

**言語：** [日本語](./README.ja.md) · [English](./README.md) · [简体中文](./README.zh-CN.md) · [Español](./README.es.md) · [Français](./README.fr.md)

# OutlineSave — ChatGPT Outline, Search & Export to HTML & PDF（コミュニティ版）

OutlineSave は、長い AI チャットを目次で移動し、検索・注釈・保存できるブラウザー拡張機能です。過去の回答を何度もスクロールして探すのではなく、会話を後から参照しやすい知識として整理できます。

このリポジトリには、**初期の機能限定・ソース閲覧可能な ChatGPT 向けデモ版**が含まれています。現在の商用正式版の完全なソースコードではなく、最新リリースの実装を示すものでもありません。OutlineSave の正式版は Chrome ウェブストアから別途インストールできます。

**[Chrome ウェブストアで OutlineSave をインストール](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[インタラクティブな HTML エクスポートのデモ](https://wisteriasoftware.uk/demo)** · **[製品情報](https://wisteriasoftware.uk/outline-pro)**

![ChatGPT Outline コミュニティ版デモ](./jump-ezgif.com-crop.gif)

> **コミュニティ版の制限：** クリックして移動できるのは目次の最初の 15 項目のみです。以下で紹介する検索・注釈・エクスポートなどの機能は、別途インストールする OutlineSave 正式版の機能であり、このリポジトリのデモには含まれません。

## コミュニティデモでできること

- ChatGPT 会話のクリック可能な目次を表示
- 会話が続くと目次を自動更新
- サイドバーの表示位置を左右に切り替え
- 長い会話での基本的な目次ナビゲーションを体験

15 項目の移動制限は**このデモ版だけ**の制限であり、OutlineSave 正式版の目次長の制限ではありません。

## OutlineSave 正式版について

正式版は **ChatGPT、Gemini、Claude、DeepSeek** の会話に対応しています。機能や操作は AI プラットフォームによって異なる場合があります。

### ChatGPT Outline：長い会話を 2 階層の目次で移動

ユーザーの質問が第 1 階層、AI 回答内の見出しが第 2 階層になります。目次のタイトルを検索し、目的の場所に移動できるので、過去のメッセージを一つずつ探す必要がありません。

非常に長い ChatGPT 会話では、目次を段階的に読み込みます。読み込み時間や網羅性は、元のプラットフォームと会話の状態によって変わります。

### Search：必要な内容を見つける

会話中の目次から質問や AI 回答の見出しを検索できます。HTML でエクスポートした後は、保存した本文の全文検索も利用できます。

### Export to HTML：検索できるオフライン知識ページ

会話を単一のレスポンシブ HTML ファイルとして保存します。元の ChatGPT 会話を開き直したり、長い履歴の再読み込みを待ったりせずに、ローカルで閲覧できます。

HTML エクスポートでは次の内容を保持できます。

- 会話の目次とナビゲーション
- 全文検索
- 既存のハイライト、下線、メモ、ブックマーク
- ブックマークとハイライト色によるフィルター
- コードブロック、数式、Mermaid 図

**[操作できる HTML エクスポートのデモを見る](https://wisteriasoftware.uk/demo)**

### PDF エクスポート

PDF エクスポートは現在開発中です。**この README 更新時点では、Chrome ウェブストアで公開中の正式版にはまだ含まれていません。** 現在利用できる機能については [Chrome ウェブストアの掲載ページ](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj) をご確認ください。

### ハイライト、メモ、ブックマーク、Markdown、JSON

正式版では 4 色のハイライト、下線、メモ、重要な箇所へのブックマークを利用できます。Markdown と JSON 形式のエクスポートにも対応しています。

### 会話データはローカル優先で処理

OutlineSave は AI 会話の内容を原則としてローカルで処理し、会話本文を Wisteria Software のサーバーにアップロードしません。OutlineSave 専用アカウントの作成も不要です。ライセンス認証や製品運用に必要なデータが処理される場合があります。任意の Google Drive バックアップはユーザーが明示的に開始し、選択したデータを自身の Drive に保存します。詳しくは[プライバシーポリシー](https://wisteriasoftware.uk/privacy)をご覧ください。

### オプション：Inbox Local と組み合わせて整理

[Inbox Local](https://github.com/sunny314woo/wisteria-suite/tree/main/apps/inbox-local) は別のローカル優先の知識管理アプリです。OutlineSave から出力した Markdown やリッチ HTML の整理に利用できます。このコミュニティデモには含まれません。

## コミュニティデモと OutlineSave 正式版の比較

| 機能 | このリポジトリのデモ | OutlineSave 正式版 |
|---|---|---|
| ChatGPT 会話の目次 | 対応 | 対応 |
| クリックして移動 | 最初の 15 項目のみ | 目次全体のナビゲーション |
| 2 階層の目次 | 非対応 | 対応 |
| 目次タイトルの検索 | 非対応 | 対応 |
| エクスポート HTML の全文検索 | 非対応 | 対応 |
| ハイライト、下線、メモ、ブックマーク | 非対応 | 対応 |
| オフライン HTML エクスポート | 非対応 | 対応 |
| Markdown と JSON のエクスポート | 非対応 | 対応 |
| Gemini、Claude、DeepSeek | 非対応 | 対応 |
| PDF エクスポート | 非対応 | 開発中。公開状況はストアをご確認ください |

## よくある質問

### ChatGPT の長い会話に目次を追加するには？

[Chrome ウェブストア](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)から OutlineSave 正式版をインストールしてください。このリポジトリのデモで移動できるのは最初の 15 項目だけです。

### ChatGPT の会話を検索できますか？

正式版では会話中の目次タイトルを検索できます。HTML にエクスポートすれば、保存した本文の全文検索も可能です。

### ChatGPT の会話をオフライン HTML として保存できますか？

はい。正式版では、目次・全文検索・対応する既存の注釈を含む単一のレスポンシブ HTML ファイルを出力できます。元の ChatGPT 会話を読み込まずにローカルで開けます。

### OutlineSave は会話をサーバーへ送信しますか？

会話本文はデフォルトでローカル処理され、Wisteria Software のサーバーにはアップロードされません。任意のバックアップと運用サービスでは別途データの取り扱いがあるため、[プライバシーポリシー](https://wisteriasoftware.uk/privacy)をご参照ください。

### OutlineSave は無料ですか？

正式版には無料の基本機能のほか、試用版と有料ライセンスがあります。エクスポート回数やライセンス条件は変更される場合があるため、[公式製品ページ](https://wisteriasoftware.uk/outline-pro)をご確認ください。

### エクスポートした HTML をスマートフォンで読めますか？

はい。HTML ファイルは画面サイズに対応しており、スマートフォンに転送して対応ブラウザーで開けます。元の ChatGPT 会話を読み込む必要はありません。

## コミュニティデモをローカルで実行する

1. Chrome で **chrome://extensions** を開きます。
2. **デベロッパーモード**を有効にします。
3. **パッケージ化されていない拡張機能を読み込む**を選びます。
4. このリポジトリのフォルダーを指定します。

## ライセンスとソースコードの公開範囲

本リポジトリは**ソースコードを閲覧できるコミュニティデモ**で、[LICENSE](./LICENSE) に記載された独自ライセンスが適用されます。**MIT または Apache-2.0 ライセンスではありません。** デモコードの公開は、商用正式版、製品ブランド、サーバーサービス、その他の専有資産の使用権を付与するものではありません。詳しくは [NOTICE](./NOTICE) をご覧ください。

**[Chrome ウェブストアで OutlineSave をインストール](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[HTML エクスポートのデモを見る](https://wisteriasoftware.uk/demo)**

**言語：** [日本語](./README.ja.md) · [English](./README.md) · [简体中文](./README.zh-CN.md) · [Español](./README.es.md) · [Français](./README.fr.md)

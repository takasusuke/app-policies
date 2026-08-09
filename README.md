# app-policies

複数アプリの利用規約・プライバシーポリシーを一元公開するリポジトリ（GitHub Pages）。
公開URL: https://takasusuke.github.io/app-policies/

## 構成

アプリごとにディレクトリを分け、ディレクトリ配下に文書ごとのページを置く。

```
<slug>/
  index.md              # そのアプリの文書一覧
  privacy-policy/
    index.md             # 日本語（正文）
    en/
      index.md            # 英語等、対応言語ごとのサブディレクトリ
  terms-of-service/      # 必要になったら追加（同様に言語ごとのサブディレクトリ）
    index.md
```

新しいアプリの文書を追加する場合は、上記の構成に合わせて`<slug>/`配下にディレクトリを作る。
本文はアプリごとの実際のデータ収集内容・機能と一致させ、使い回さない
（`~/AIFiles/docs/privacy-policy.md`, `~/AIFiles/docs/legal-review.md`参照）。

**多言語対応**: 対象言語は**App Store Connectがメタデータ（App Information / App Store掲載情報）で
サポートする全言語**とする（アプリ自体のUI対応言語に限定しない）。言語ごとにページを分ける
（例: `<slug>/privacy-policy/`が日本語、`<slug>/privacy-policy/en/`が英語、
`<slug>/privacy-policy/zh-Hans/`が中国語簡体字…）。**日本語版が正文**とし、翻訳版には
「日本語版が優先される」旨を明記する。

一度にすべて用意する必要はない。新しいアプリの文書を作るときは、まず日本語＋英語を用意し、
以降は下記の一覧から未対応の言語を順次追加していく（Issueで進捗管理してよい）。

### App Store Connect対応言語（50言語、ロケールコード）

| 言語 | コード | 言語 | コード |
|---|---|---|---|
| アラビア語 | ar | 韓国語 | ko |
| ベンガル語 | bn | マレー語 | ms |
| カタルーニャ語 | ca | マラヤーラム語 | ml |
| 中国語（簡体字） | zh-Hans | マラーティー語 | mr |
| 中国語（繁体字） | zh-Hant | ノルウェー語 | no |
| クロアチア語 | hr | オディア語 | or |
| チェコ語 | cs | ポーランド語 | pl |
| デンマーク語 | da | ポルトガル語（ブラジル） | pt-BR |
| オランダ語 | nl | ポルトガル語（ポルトガル） | pt-PT |
| 英語（オーストラリア） | en-AU | パンジャブ語 | pa |
| 英語（カナダ） | en-CA | ルーマニア語 | ro |
| 英語（イギリス） | en-GB | ロシア語 | ru |
| 英語（アメリカ） | en-US | スロバキア語 | sk |
| フィンランド語 | fi | スロベニア語 | sl |
| フランス語 | fr | スペイン語（メキシコ） | es-MX |
| フランス語（カナダ） | fr-CA | スペイン語（スペイン） | es-ES |
| ドイツ語 | de | スウェーデン語 | sv |
| ギリシャ語 | el | タミル語 | ta |
| グジャラート語 | gu | テルグ語 | te |
| ヘブライ語 | he | タイ語 | th |
| ヒンディー語 | hi | トルコ語 | tr |
| ハンガリー語 | hu | ウクライナ語 | uk |
| インドネシア語 | id | ウルドゥー語 | ur |
| イタリア語 | it | ベトナム語 | vi |
| 日本語 | ja（正文） | | |
| カンナダ語 | kn | | |

出典: [App Store Localizations（Apple公式）](https://developer.apple.com/help/app-store-connect/reference/app-store-localizations)。
本リポジトリ管理者が定期的にApple公式ページと突き合わせ、追加・変更があれば更新する。

## アプリ一覧

- [Simple Timer](simple_timer/) — 全50言語対応済み（[一覧](simple_timer/)）
- [Simple Memo](simple_memo/) — 全50言語対応済み（[一覧](simple_memo/)）
- [Stone Knights](stone_knights/) — [プライバシーポリシー(ja)](stone_knights/privacy-policy/) /
  [Privacy Policy(en)](stone_knights/privacy-policy/en/)
- [Simple Calculator](simple_calculator/) — [プライバシーポリシー(ja)](simple_calculator/privacy-policy/) /
  [Privacy Policy(en)](simple_calculator/privacy-policy/en/) /
  [サポート/Support](simple_calculator/support/)

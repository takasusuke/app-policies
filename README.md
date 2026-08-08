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

**多言語対応**: アプリが複数言語に対応している場合、対応言語ごとにページを分ける
（例: `<slug>/privacy-policy/`が日本語、`<slug>/privacy-policy/en/`が英語）。
**日本語版が正文**とし、翻訳版には「日本語版が優先される」旨を明記する。

## アプリ一覧

- [Simple Timer](simple_timer/) — [プライバシーポリシー(ja)](simple_timer/privacy-policy/) /
  [Privacy Policy(en)](simple_timer/privacy-policy/en/)
- [Stone Knights](stone_knights/) — [プライバシーポリシー(ja)](stone_knights/privacy-policy/) /
  [Privacy Policy(en)](stone_knights/privacy-policy/en/)

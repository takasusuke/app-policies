# app-policies

複数アプリの利用規約・プライバシーポリシーを一元公開するリポジトリ（GitHub Pages）。
公開URL: https://takasusuke.github.io/app-policies/

## 構成

アプリごとにディレクトリを分け、ディレクトリ配下に文書ごとのページを置く。

```
<slug>/
  index.md              # そのアプリの文書一覧
  privacy-policy/
    index.md
  terms-of-service/      # 必要になったら追加
    index.md
```

新しいアプリの文書を追加する場合は、上記の構成に合わせて`<slug>/`配下にディレクトリを作る。
本文はアプリごとの実際のデータ収集内容・機能と一致させ、使い回さない
（`~/AIFiles/docs/privacy-policy.md`, `~/AIFiles/docs/legal-review.md`参照）。

## アプリ一覧

- [Simple Timer](simple_timer/) — [プライバシーポリシー](simple_timer/privacy-policy/)
- [Stone Knights](stone_knights/) — [プライバシーポリシー](stone_knights/privacy-policy/)

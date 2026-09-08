# privacy

複数アプリのプライバシーポリシーをまとめて公開するための共有リポジトリです。
アプリごとのソースコードは含みません(各アプリは別のリポジトリで管理)。

## 構成

アプリごとにサブフォルダを切り、その中に `index.html` を置く。

```
bookshelf/index.html   わたしの本棚
```

公開URL: `https://bonuxn.github.io/privacy/<アプリのフォルダ名>/`

## 新しいアプリを追加する手順

1. `<アプリ名>/index.html` を追加してpush
2. Play Console等の「プライバシーポリシーURL」に `https://bonuxn.github.io/privacy/<アプリ名>/` を入力

## GitHub Pages設定(初回のみ)

リポジトリの **Settings → Pages** で Source を "Deploy from a branch"、Branch を `main` / `/ (root)` に設定する。

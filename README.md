# basic

## ユーザーがカスタマイズする際の手順

* [Use this template](https://github.com/naogify/basic/generate) ボタンでこのリポジトリをコピー。
* `style.yml` を編集。
* しばらくすると `gh-pages` ブランチに `style.json` がコミットされるので、Geolonia Maps で表示する場合は、その URL を以下のように指定してください。

```
<div data-style="https://raw.githubusercontent.com/<あなたのGitHubユーザー名>/<リポジトリ名>/gh-pages/style.json"></div>
```

例: https://codepen.io/naogify/pen/ZEJOErQ


## 色のカスタマイズ

[style.yml](./style.yml) を開いて下さい。 以下をお好きな色のカラーコードに変更しコミットして下さい。

```
$background: rgba(254, 254, 254, 1)

# カスタマイズここまで
```

## アイコンのカスタマイズ

[icons](./icons) にある SVG ファイルを、同じファイル名で置き換えコミットして下さい。


# basic

## ユーザーがカスタマイズする際の手順

* [Use this template] ボタンでこのリポジトリをコピー。
* `style.yml` を編集。
* しばらくすると `gh-pages` ブランチに `style.json` がコミットされるので、Geolonia Maps で表示する場合は、その URL を以下のような感じで指定してください。

```
<div data-style="<style.json の URL>"></div>
```

例: https://codepen.io/naogify/pen/ZEJOErQ


## 色のカスタマイズ

[style.yml](./style.yml) を開いて下さい。 お好きな色のカラーコードに変更しコミットして下さい。

```
$background: rgba(254, 254, 254, 1)

# カスタマイズここまで
```

## アイコンのカスタマイズ

[icons](./icons) にある SVG ファイルを編集してコミットして下さい。











<!-- 

## GitHub Pages を設定して変更したスタイルを確認する

* GitHub のリポジトリのメニューの中にある [Settings] をクリックしてください。
* 移動先のページの下の方にある [GitHub Pages] のところで、以下のように設定してください。

![](https://www.evernote.com/l/ABXqA26fEitDNZG6KDxX-Os6Qb8gciGRKSYB/image.png)

* 下の URL にアクセスすると地図が表示されます。

```
https://<あなたの GitHub ユーザー名>.github.io/<あなたのレポジトリ名>/
```
例: https://naogify.github.io/basic/

 -->

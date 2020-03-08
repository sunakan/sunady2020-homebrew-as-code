# homebrew as code(mac-app as code?)

## GitHub

[https://github.com/sunakan/sunady2020-homebrew-as-code](https://github.com/sunakan/sunady2020-homebrew-as-code)

## 以下をコードで管理したい

* HomeBrewで入れるパッケージ群
* Macに入れるGUIアプリ

## どんな時に使える？

* Macを買い替えた時
* Macをクリーンインストールした時
* MacのアプリをポチポチDLして入れたくない時

## フローチャート

![](https://raw.githubusercontent.com/sunakan/sunady2020-homebrew-as-code/master/docs/diagrams/flowchart.png)

## Brewfileにない、brewで管理しているパッケージを削除

```
# 確認するだけ
$ brew bundle cleanup
```

```
# 実行!!
$ brew bundle cleanup --force
```

## 参考

* [https://github.com/Homebrew/homebrew-bundle](https://github.com/Homebrew/homebrew-bundle)

* [【Macの環境構築】homebrewとBrewfileでアプリを一括インストールする](https://gurutaka-log.com/mac-environment-brewfile)

* [brew bundleでMacのアプリをまとめてインストール・管理](https://qiita.com/vochicong/items/f20afc89a6847cd58f0f)

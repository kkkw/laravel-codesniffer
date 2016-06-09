# Laravel CodeSniffer

Laravelを使用したプロジェクトのために用意された
phpcsのルールセット

## インストール

### パッケージをインストール

`composer.json` に記載してインストールする
`repositories` と `require-dev` にそれぞれ追記する

``` json:composer.json
"repositories": [
 {
  "type":"package",
    "package": {
      "name": "kkkw/laravel-codesniffer",
      "version":"master",
      "source": {
        "url": "https://github.com/kkkw/laravel-codesniffer.git",
        "type": "git",
        "reference":"master"
      }
    }
  }
],
"require-dev": {
    "kkkw/laravel-codesniffer": "*@dev"
},
```

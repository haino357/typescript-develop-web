## TypeScriptのインストール
npmを使ってTypeScriptをインストールする。
```
npm install -g typescript

下記はインストール時のログ
↓↓↓↓↓
added 1 package in 6s
npm notice
npm notice New minor version of npm available! 10.7.0 -> 10.8.2
npm notice Changelog: https://github.com/npm/cli/releases/tag/v10.8.2
npm notice To update run: npm install -g npm@10.8.2
```
インストールが完了すると、`tsc`コマンドが使えるようになる。

`tsc --version`でバージョンを確認できる。
```
tsc --version
Version 5.5.4

// 2024/08/07時点のバージョン
```

## TypeScriptの設定ファイルの作成
### package.jsonの作成
```
npm init -y
```
`-y`オプションをつけると、デフォルトの設定で`package.json`が作成される。

### tsconfig.jsonの作成
TypeScriptの設定ファイルは`tsconfig.json`という名前で作成する。
```
tsc --init
```
`--init`オプションをつけると、`tsconfig.json`が作成される。
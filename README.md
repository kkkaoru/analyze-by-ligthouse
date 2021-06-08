## Analyze-by-lighthouse

Lighthouseを用いて静的ページの計測を行います。

## 計測方法

dist配下にページが正常に閲覧出来る状態で静的ファイルを保存します。

dist配下をhttpで閲覧出来るように以下のコマンドの実行を行います。

```
npm run serve
```


その後に以下のコマンドを実行してLighthouseの計測を行います・

```
# トップページのみの場合
npm run analyze http://localhost:8080/

# 下層ページ(/exampleの場合)の計測
npm run analyze http://localhost:8080/example/
```

計測結果のサンプルは以下のコマンドを実行してご確認ください。

```
npm run example
```

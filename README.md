# 簡単に背景に画像を差し込めるアレ
元ソース：[愛の落書き帳 痛エディタにする話](https://blog.ishotihadus.com/archives/81)

以下のコードをatomのstyle.lessに貼り付けてご利用ください。

urlを変更させるだけで簡単に設置できます。

また、諸々の都合によりdark light頻繁に変えなければならない際はnameで変更可能です。
その他の独自スタイルテーマを好きに作成したものはコントローラーに登録すれば使えます。

```less
@import "フルパス/theme/controller.less";
// 現在は light か dark
@bgcolor: 'light';
@url: "画像のリンク";
.controller(@bgcolor, @url);
```

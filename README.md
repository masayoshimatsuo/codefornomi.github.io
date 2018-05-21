# 5374について

##「いつ、どのゴミが収集されているのか？」

ゴミの問題はどの地域でも深刻になりつつあります。
 [Code for Kanazawa](http://codeforkanazawa.org/)
では、先ずは正しいゴミの捨て方に注目しました。例えばお引っ越しをされた場合、このアプリを使えばすぐに分かるように、目的と使い方をとてもシンプルにデザインしました。

## ブランチの運用について

* **master**: ローカライズをする場合にはこのブランチをforkしてください (2014/5/7 updated v1.1)
* **kanazawa**: 5374の金沢バージョン
* **gh-pages**: 5374の金沢バージョンリリースブランチ
* **dev**: 今後kanazawaへ適用予定の開発ブランチ

## 使い方について

[HOWTOUSE.md](HOWTOUSE.md)に5374標準の文章を用意してあるので、書き換えて使ってください。

## ローカライズについて

各地域へのローカライズについては[LOCALIZE.md](LOCALIZE.md)を参照するようにしてください。




## 開発チームとライセンスについて
- 小野 祐貴(Yuki ONO)　Developer
- 五十川 員申(Kazunobu IKAGAWA)　Developer
- 高木 志宗(Yukimune TAKAGI)　Developer
- 宮田 人司(Hotoshi MIYATA)　Designer

本アプリ及びソースコードの著作権はCode for Kanazawaに帰属します。
但し、このソースコードは[MPL](http://www.mozilla.org/MPL/2.0/)のもと配布されています。MPLに従えば、どなたでも利用、改変、及び再配布が可能です。



## 5374hakusanについて

このアプリは5374能美市バージョンを元に製作しています。
したがって、現在の5374金沢版のプログラミングとは異なる部分が多いため、今の所参考にしないようにしてください。
能美市5374githubはこちらを参照
https://github.com/codefornomi/codefornomi.github.io

能美市では他言語化に対応していますが、白山市版では非対応にしています。
対応にするにはscript.jsの622行目から変更します。該当部分にコメントアウトの状態で切り替え方法を記載しています。



## 年度ごとに更新が必要なファイルについて

### HOWTOUSE.md
提供されるゴミ情報についての部分に年度と参考した資料へのリンクアドレスがあります。

### localesフォルダ > jaフォルダ > website.l20n
28行目に提供されるゴミ情報についての部分に年度と参考した資料へのリンクアドレスがあります。

### dataフォルダ > jaフォルダ > 各種csv
各地域の変更内容によって、該当のcsvファイルを変更してください。



## 作成者について・データ入力

- 松尾雅由(Masayoshi Matsuo)

白山市のゴミ収集に関してのデータを参考に入力しております。
http://www.city.hakusan.ishikawa.jp/data/open/cnt/3/9764/1/H30_gomi-nittei.pdf
不具合など発見された方はご一報ください。


## レクチャーいただいた方に感謝いたします。

- 五十川 員申(Kazunobu IKAGAWA)
- 小野 祐貴(Yuki ONO)
- 福島 健一郎 (kenichiro fukushima)
- 鳥毛 崇 (takashi torige)




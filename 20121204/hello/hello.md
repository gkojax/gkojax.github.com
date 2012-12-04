!SLIDE
## Playに触ってみよう


<br/><br/>
[@gkojax](https://twitter.com/gkojax)
<br/>
[#fantech](https://twitter.com/search/realtime?q=%23fantech)

!SLIDE
## ところでこのスライドもscala製のツールで作られています

* [ここで知った](http://d.hatena.ne.jp/tototoshi/20111026/1319644432)
* Markdown記法で記述 → コマンドを実行
* →1HTML + css + js 静的ファイルをgithubにUP

!SLIDE
## 事前準備

### [Play 2.0 のインストール](http://playdocja.appspot.com/documentation/2.0.3/Installing)

* macの人 brew install play
* windows or linulxの人 バイナリをダウンロード。
* ダウンロードに時間がかかるので、まだの人は早めに始めておいた方がいいかも。

!SLIDE
## 参加者リストを見た感じ

1. 初めて参加する方
2. 初めてじゃないけど、前回参加しなかった方
3. 前回参加している方

!SLIDE
## 前々回＆＆前々回＆前回の内容

### チュートリアルに沿ってTODO-LISTを作ろう
* [チュートリアルページ](http://playdocja.appspot.com/documentation/2.0.3/ScalaTodoList)
* [ソースコード](https://github.com/gkojax/play-todolist)
* TODO-LISTを改造してPlayの色々な機能に触れよう

!SLIDE
## 今日はテストについて

[TodoListのテスト](https://github.com/gkojax/play-todolist/tree/master/test)

[ドキュメント１](http://playdocja.appspot.com/documentation/2.0.3/ScalaTest)

[ドキュメント２](http://playdocja.appspot.com/documentation/2.0.3/ScalaFunctionalTest)

!SLIDE
## ソースのこの辺参考にした

[Helpers.scala](https://github.com/playframework/Play20/blob/master/framework/src/play-test/src/main/scala/play/api/test/Helpers.scala)

[Fakes.scala](https://github.com/playframework/Play20/blob/master/framework/src/play-test/src/main/scala/play/api/test/Fakes.scala)

!SLIDE
## なんだかんだでソースコード読むのが一番早い

git clone https://github.com/playframework/Play20.git

!SLIDE
## 機能追加
* TODOに登録時刻付与
* 編集機能（UPDATE）
* 期限をつける
* 優先度
* カテゴリを追加
* ソート順の変更

!SLIDE
## 機能追加
* [多言語対応](http://playdocja.appspot.com/documentation/2.0.3/ScalaI18N)
* memchachdを使って高速化
* websocketをどうにかする
* anorm以外のO/Rマッパーを使ってみる

!SLIDE
## 権限付与
* [play20-auth](https://github.com/t2v/play20-auth/blob/master/README.ja.md)プラグインを追加
* [ログイン画面](https://github.com/gkojax/play-todolist2)
* 閲覧は全員のタスク。編集は自分のタスクのみ。

!SLIDE
## デザインの変更
* Twitter BootStrap
* スマホ対応
* HTML5対応

!SLIDE
## 外部APIを使う
* GoogleMap連携
* twitter連携
* F

!SLIDE
## その他なんでも

!SLIDE
## スケジュール

* ～21:20 黙々と作業する時間
* 21:20～ 成果発表
* 21:40～ 後片付け

!SLIDE
* 詰まった人はお気軽に質問して下さい。


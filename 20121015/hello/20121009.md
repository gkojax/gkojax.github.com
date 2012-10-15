!SLIDE
## Playを始めてみよう


[@gkojax](https://twitter.com/gkojax)
<br/>
[@fantechstudy](https://twitter.com/fantechstudy)

!SLIDE
## 先週発表し忘れたヤツ

* [http://www.slideshare.net/gkojax/fanscala1-4](http://www.slideshare.net/gkojax/fanscala1-4)


!SLIDE
## Playframework

* JavaとScalaの<br/>webアプリケーションフレームワーク
* [公式サイト](http://www.playframework.org/)
* [日本語訳](http://playdocja.appspot.com/)

!SLIDE
## 特徴

* 強固で高速
* リアクティブ
* スケーラブル
* 素早い改善
* 楽しく、そして生産的
* 本当のスケーラビリティ

!SLIDE
## playの歴史

* 1.0 Javaのフレームワークとして開発
* Scalaプラグインが追加
* 2.0 Scalaで書き換えられる

!SLIDE
## javaとscala

* [Scala 開発者のための Play 2.0](http://playdocja.appspot.com/documentation/2.0.3/ScalaHome)
* [Java 開発者のための Play 2.0](http://playdocja.appspot.com/documentation/2.0.3/JavaHome)

!SLIDE
## [Play 2.0 のインストール](http://playdocja.appspot.com/documentation/2.0.3/Installing)

* macの人 brew install play
* windows or linulxの人 バイナリをダウンロード

!SLIDE
## [初めての Play アプリケーション](http://playdocja.appspot.com/documentation/2.0.3/ScalaTodoList)

* [http://playdocja.appspot.com/documentation/2.0.3/ScalaTodoList](http://playdocja.appspot.com/documentation/2.0.3/ScalaTodoList)
* 今日はこのチュートリアルを進めていきます。

!SLIDE

## プロジェクト作成
<br />

```sh
 $ play new todolist
```

!SLIDE

## アプリの起動
<br />

```sh
 $ cd todolist
 $ play run
```

<br />

* [http://localhost:9000/](http://localhost:9000/) にアクセス。
* うまく表示されない人は教えて下さい。
* Ctl+Dで抜けます。

!SLIDE

## Playコンソール

* 「play」と打つとコンソールに入る
* そこで「run」と打つと開発モードが起動します。
* 最初から「play run」と打つのと一緒です。

!SLIDE

## その他コマンド
* help play
* run
* compile
* console
* debug
* ~ compile
* ~ run
* ~ test

!SLIDE

## 概要

* conf/routes
* app/controllers/Application.scala
* app/views/index.scala.html

!SLIDE

## TODOリストの作成

```scala
def index = Action {
  Ok("Hello world")
}
```

<br/>
* 変更したときに再起動いらない
* エラーの時はエラー画面

!SLIDE

## 後は [チュートリアル](http://playdocja.appspot.com/documentation/2.0.3/ScalaTodoList) を見ながらサイトを作成

* タスク一覧画面
* タスクの登録フォーム
* タスク登録
* タスクの削除


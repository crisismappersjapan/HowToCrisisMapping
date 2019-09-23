# How to do Crisis Mapping

## 初心者マッパー
* 建物マッピング

## 中級者マッパー
* 道路マッピング
* Validation

## 上級者マッパー
* 
* JOSMを用いたマッピング
* RapiDを用いたマッピング

## プロジェクト管理者
* [プロジェクト登録情報テンプレート](https://github.com/dronebird/mapping/issues/4)





--- 過去のMEMO、いずれアーカイブします。

### for beginners
かんたんなHOT活動の手引はこちらから

http://dohokugeo.blogspot.jp/2015/04/blog-post.html

http://dohokugeo.blogspot.jp/2015/04/blog-post_29.html

### Task
こちらを参考にすること
http://wiki.openstreetmap.org/wiki/JA:2016_Kumamoto_earthquake


### 現況
* 道路が古いY!データのままなので適宜地理院地形図やオルソで修正を行ってから建物を作成することが望ましい
* 建物も多いためツールはJOSM＋Bulidngplugin推奨 (edited)
* 密集地は適宜分割するようにして負担を軽減するように

### Source


飯田さん20160416AM情報
http://bit.ly/1VqXzVy
>今回の震災対応として、地理院より、宇城地区の地理院地図レイヤーが公開されました。
>他の地理院地図レイヤーと同様、オブジェクトあるいは変更セットへのタグづけに "source=GSImaps/20160414kumamoto_0415dol3" >を付与することで利用が可能です。
>JOSMなどへの追加方法などについては、以下のドキュメントを参照ください。
>http://wiki.openstreetmap.org/wiki/JA:GSImaps


* 電子国土基本図（オルソ画像）
http://cyberjapandata.gsi.go.jp/xyz/ort/{z}/{x}/{y}.jpg
source=GSImaps/ort

* 地形図(道路線の参照）
http://cyberjapandata.gsi.go.jp/xyz/std/{z}/{x}/{y}.png
source=GSImaps/std


# あなたのコミュニティでHOT入力チームをつくるには

## 準備物
・PC・マウス（可能なら）

・ネット環境・OSMマッパー（HOT経験者がいると望ましい）

・モチベーションの高いメンバ、など

## 立ち上げタスクリスト
* OSM・HOT経験のあるコアメンバーの招集
* 人員募集（基本的GISスキルと時間があるやつ来て！的な内容で）
* JOSMのセットアップ
* スキルを見極めて、初心者・経験者でわけ、バランスによってコアメンバーレクチャー担当を割り振り
* 初心者にはアカウント作成→TaskingManagerの使い方説明
→JOSM＋building pluginで建物作成
* 経験者にはJOSM＋building pluginで建物作成

## 気をつけたいこと
* 各メンバーの気力体力は十分な配慮を
* 適宜休憩をとりましょう
* 無理強いはよくない


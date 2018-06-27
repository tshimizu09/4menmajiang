# 4menMajiang
HTML5 + JavaScript で動作する麻雀アプリ「電脳麻将」
を、無理矢理四面打ちに対応させつつ
PWAアプリ化してみた物

## デモ
http://tshimizu09.github.io/4menmajiang/

## ライセンス
Copyright&copy; 2018 tshimizu09<br>
Released under the MIT license<br>
https://github.com/tshimizu09/4menmajiang/blob/master/LICENSE

## ゲームエンジン部分のソースコード
https://github.com/kobalab/Majiang

### テストプレイの結果、現時点で分かっている事
・PWAアプリとして動作するようにしたので、オフラインにしても基本的に全機能動いているはずです。
（チェック漏れがあったら申し訳無い）

・オフライン動作デモはこちら
https://twitter.com/tshimizu09/status/1007889521944322049/video/1

・AndroidのGoogle ChromeやiOSのSafariで、ホーム画面に追加をしてそこから起動すると単体アプリっぽく動きます

・WindowsのGoogle Chromeの場合、その他のツール→ショートカットの作成で、ウインドウとして開くのチェックを入れたまま作成すると単体アプリっぽく動作します。

・WindowsのGoogle Chromeで単体アプリっぽく動かしたのがこちら
https://twitter.com/tshimizu09/status/1006853350409695234/video/1

・Windows10のMicrosoft Edgeの場合、メニューに出てくる　ピン留めする（恐らく2種類出ますがどちらでもいいはず）を選んで、それを起動すると単体アプリっぽく動作するはずです。
（Windows10 April Update 2018からのMicrosoft Edgeの新機能なので、それ以前では多分そうならないはず）

・Firefox 61でレンダリングの仕様に変更があり、画面サイズに合わせた画面の自動調整が完全には効かなくなってしまったため、現時点でFirefoxはお奨めしづらくなりました。
（毎回開く前にブラウザキャッシュを削除すれば自動調整が動く事は動きますが、大変不便だと思います）

・横画面で動かす事しか想定していないので、強制的に横画面で動くように設定しています。

・こしらえたのはPWA化と四面打ち用の画面作りだけなので、ゲームの基本動作は全て　電脳麻将　さんに準じます。

・Windows10専用のUWPアプリ化も一応出来そうですが、現時点では野良アプリとしての出力に失敗するため作業中です。

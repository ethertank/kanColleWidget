# 艦これウィジェット ![neko](src/img/icon.png)
艦これウィジェットは推奨環境であるChromeを艦これに最適化させるChrome拡張です

# 使い方
インストールはこちらから。で、準備完了

[Chrome ウェブストア - 艦これウィジェット](https://chrome.google.com/webstore/detail/%E8%89%A6%E3%81%93%E3%82%8C%E3%82%A6%E3%82%A3%E3%82%B8%E3%82%A7%E3%83%83%E3%83%88/iachoklpnnjfgmldgelflgifhdaebnol)

# 機能
- 機能概要
    - 艦これだけの別窓を開いてくれます
    - 遠征・入渠・建造のタイマーを自動で設定してくれます
    - 通知します
    - その他艦娘ぺろぺろ

参考資料 [加賀さんと僕〜艦これウィジェットの紹介と説明〜](http://www.slideshare.net/otiai10/ss-26631311)

# よくある質問

- 専ブラなんすか？
    - 専ブラではありません！Chrome(推奨環境)です！
- 規約違反なんすか？
    - Chromeなので、`（8）不正な方法（特殊なプログラムを介しての）でのアクセスを試みる行為`には該当しないと考えております
- チートできないんすか？
    - チート要素は一切実装しておりません。ｻーｾﾝ
- その他頂いている機能改善やバグ報告など
    - [issues/question/open](https://github.com/otiai10/kanColleWidget/issues?labels=question&page=1&state=open) 

# お問い合わせ/機能要望/バグ報告
- Twitterから
    - [twitter.com/otiai10](https://twitter.com/otiai10)
- GitHubから
    - [github.com/otiai10/kanColleWidget/issues/new](https://github.com/otiai10/kanColleWidget/issues/new) 

# 実装
- 以下の3点に最大限配慮して実装しています
    - 艦これの規約に違反しないこと
    - 艦これサーバに負荷をかけないこと
    - 艦これの面白さを損なわないこと

参考資料 [加賀さんと僕（実装編）〜艦これウィジェットの課題と実装〜](http://www.slideshare.net/otiai10/ss-26908975)

# 開発

以下のレポジトリでOSS開発をしております。ForkするなりPRするなりご自由にどうぞ！
https://github.com/otiai10/kanColleWidget

[README4DEV.md](https://github.com/otiai10/kanColleWidget/blob/develop/README4DEV.md)

# リリースノート（ながいので注意 :smiling_imp: ）
- 2013/11/15 v0.5.0.3
    - 建造時にツイート設定を見ていなかった不具合を修正
- 2013/11/15 v0.5.0.2
    - デイリー消化状況表示（クロックモード）
    - レシピメモ（クロックモード）
    - 開発報告ツイート機能
    - 建造報告ツイート機能
    - ウィジェットタイトルのバリエーション追加
- 2013/11/07 v0.3.4.5
    - 新しい任務が追加されちゃった時のUIを追加
- 2013/11/04 v0.3.4.3
    - 追加された任務の対応
- 2013/11/02 v0.3.4.2
    - 追加された任務の対応
    - 運営メンテ時の表示を改善
- 2013/10/31 v0.3.4.1
    - クロックモードの表示バグ修正（できたか不安）
    - 通知の表示順を変えれる設定を追加（終了順とかドックID順とか）
- 2013/10/23 v0.3.3.0, v0.3.4.0
    - 通知消えない詳細設定を追加
    - 数分前通知詳細設定を追加
    - リマインダーの登録後編集機能を改善（クロックモードがパワーアップ）
- 2013/10/18 v0.3.2.11
    - OCR精度向上
- 2013/10/17 v0.3.2.9
    - タイマー設定のバグ修正
    - OCR精度向上
- 2013/10/14 v0.3.2.7
    - タイマー登録後の編集を可能にしました
    - OCR精度向上
- 2013/10/12 v0.3.2.3, v0.3.2.5
    - ウィジェット化の不具合修正
    - OCR精度向上
    - 音声のリセット機能追加
- 2013/10/08 v0.3.2.2
    - サーバ安定の準備
- 2013/10/07 v0.3.2.1
    - 余黒領域が表示されているときのOCR自動取得対応
    - 送信されたOCR失敗ログを見ることができます
- 2013/10/04 v0.3.1.0
    - 通知音声のタイプ別詳細設定を追加
    - 入渠・建造の通知が1分遅いバグを修正
    - OCRサーバのスピード・安定性向上
- 2013/10/01 v0.3.0.2
    - OCRサーバのメンテナンス準備
- 2013/09/29 v0.3.0.1
    - 時間自動取得設定100%解放
    - 新規遠征への対応
- 2013/09/28 v0.3.0.0
    - 入渠・建造、時間自動取得設定の追加ァァァァ！！！！
    -【現在20％リリース中です。サーバ負荷を見つつ100%解放していきます】
- 2013/09/26 v0.2.8.1, v0.2.8.2, v0.2.8.3
    - Retinaでもふつうサイズスクショの設定追加
    - いっぷんまえ通知のバグ修正
- 2013/09/25 v0.2.8
    - Windowsの表示バグ修正
    - スクショのショートカットキーバインドを追加
        -（ctrl + shift + 0 ではたしてよかったのか？）
- 2013/09/25 v0.2.7.11
    - 戦績表示可能になりました
    - 艦隊名編集可能になりました
- 2013/09/24 v0.2.7.10
    - 一部分かりにくい表示を修正
- 2013/09/24 v0.2.7.9
    - 時計モードのバグを修正
- 2013/09/24 v0.2.7.8 
    - アイコンクリック時背景の任意設定
    - その他バグの予防・修正
- 2013/09/21 v0.2.7.7
    - 通知音量設定の追加
    - ウィジェット起動位置の記憶
    - 実績表示のデザイン変更
    - その他バグ修正
    - 第二艦隊遠征帰投時間のバグは現在調査中です
- 2013/09/18 v0.2.7.4
    - リマインダ手動登録ポップアップが閉じない問題修正
    - 第二艦隊遠征帰投時間がバグってるんじゃないか疑惑改善
- 2013/09/16 v0.2.7.3
    - 通知の発着個別設定を追加
    - 着通知時の文言変更設定を追加
    - 入渠時間自動取得はもうすぐ実装できます！...>_<...
- 2013/09/12 v0.2.7.2
    - ダウンロード・オン・スクショ！の設定追加
    - ちょっとした表示修正
- 2013/09/10 v0.2.7.1
    - ちょっとした機能(時計モード)の追加
- 2013/09/09 v0.2.7
    - スクショ機能・設定を追加
    - 通知時音声設定を追加
    - 通知ポップアップ押した時の挙動を修正
    - その他バグ修正
- 2013/09/07 v0.2.6
    - 入渠修復完了通知! (半自動)
    - 建造完了通知! (半自動)
    - 通知アイコン変更設定を追加
    - 「提督 仕事しろ」変更設定を追加
    - 他
 - 2013/09/04 v0.2.5
    - 通知をクリックしたら前面に
    - 既にある場合LAUNCHしたら前面に
    - 残り時間をバッジにする設定の追加
    - 補給回数など任務に関係ある回数を記録
    - その他バグ修正
- 2013/08/31 ver0.2.4
    - Windowsにおける絶妙なスキマを殲滅、その他表示改善
- 2013/08/29 ver0.2.3
    - 完了までの時間を表示、その他改善
- 2013/08/29 ver0.2.0
    - 遠征完了通知の実装
- 2013/08/27 ver0.1.1
    - 表示の修正
- 2013/08/24 ver0.1.0
    - 公開

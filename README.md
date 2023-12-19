# 進撃のこうかとん

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
こうかとんが仲間と協力し、ボスを倒していくシューティングゲーム

## ゲームの実装
###共通基本機能
* 主人公キャラクターに関するクラス
* 爆弾に関するクラス
* 敵に関するクラス
* ビームに関するクラス
* 爆発に関するクラス
* 画面に表示させるmainクラス
### 担当追加機能
* ライフ機能(担当:岩永): こうかとんが爆弾と衝突した場合にライフを減らし、ライフが0になったらゲームオーバーする機能の実装
### ToDo
- [ ] ライフをハートの画像で表示すること
### メモ
* スコアが500以上でlのキーを押すとライフが1増えるように実装してある。
* 初期ライフは3としている。

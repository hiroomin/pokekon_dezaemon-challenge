# pokekon_dezaemon-challenge

## 概要
デザエモン隠しメッセージにある通信機能を使う例のポケコン版です。  
サンプルゲームのランキングを書き換え出来ます。  
ユーザゲームのランキングではないので注意してください。  
  
改変は望みません。  


## 注意点
- SHARP PC-G850Vにて動作確認済みです。  
  IOポートの制御系が同等であれば、同シリーズ機種でも動くかも知れません。  
- ポケコン用BASICの場合、行番号に意味を持ちます。  
  ポケコンへのプログラム入力、またプログラム転送時は必ず記載してください。

## ピンアサイン
ポケコンのIOポートを利用してスーファミコントローラーに接続するためのピンアサインの情報をまとめました。  
ポケコンIOポート11ピンのうち、3番のGNDから6番までの4ピンを使用します。  

| ポケコンIOポート | 接続先（スーファミコントローラー側） |
|------------------|--------------------------|
| 3番 (GND)        | GND                      |
| 4番              | I/O                      |
| 5番              | DATA2                    |
| 6番              | DATA1                    |


## メモ (参考画像)
https://x.com/hiroominpps/status/1875567242680901901





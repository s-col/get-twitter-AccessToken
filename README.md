# get-twitter-AccessToken
Twitterアカウントのアクセストークンを取得して表示します．

## Demo
![demo.gif](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/289805/e848b9e1-3fae-1004-8e8a-a062f11f531c.gif)

## 必要なパッケージ
* oauth2

## 使い方
1. `TwitterOauth.py`の46, 50行目を編集して，Twitter AppのAPI keyとAPI secret keyを設定する（または引数で指定する。ブラウザも指定したい場合はそのフルパスを""で囲って指定する）
2. `python TwitterOauth.py`を実行する
3. ブラウザが開き，Twitterの認証画面が表示される
4. アクセストークンを取得したいTwitterアカウントでログインし，「連携アプリを認証」をクリックするとPINが表示される
5. ターミナルに戻ってPINを入力する
6. アクセストークンが表示される

## 参考
* https://qiita.com/wifecooky/items/d55aafb31e831f90edd8
* http://ikautimituaki.hatenablog.com/entry/20120516/1337142308

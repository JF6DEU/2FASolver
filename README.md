# 2FA-Solver

> QRコード生成・解析を含んだワンタイムパスワード(OTP)を実行するためのJavaScriptのみで作られたWebページ
> > インターネットの接続環境に依存しないため、ダウンロードしてオフラインで使用することができます。
> 
>  [@nuintun](https://github.com/nuintun/) - [nuintun/qrcode](https://github.com/nuintun/qrcode) と [@russau](https://github.com/russau/) - [russau/ArduinoOTP](https://github.com/russau/ArduinoOTP) からインスパイアされ、変更を加えました。
>
> JF6DEUが日本語へ翻訳しました。


### コンテンツ
- [概要](#概要)
- [2FA-SolverのWebページ](#2FA-SolverのWebページ)
- [ユーザーガイド](#ユーザーガイド)
  - [QRコード生成/エンコード](#QRコード生成/エンコード)
  - [QRコードスキャナ/デコード](#qr-code-image-scannerdecoder)
  - [リアルタイムのOTP作成](#retrieve-one-time-password-in-real-time)


### 概要

2FA Solverは、QRコードを生成/スキャンし、シークレットキーを使用してワンタイムパスワード(OTP)をリアルタイムで取得するのに役立つJavascript+HTMLベースのWebページです。

[2FA-Solver.html](/2FA-Solver.html) と [configs](/configs) フォルダをローカルにダウンロードすることで、オフラインでも使用できます。 

### 2FA-SolverのWebページ

[2FA Solver](https://bousai.jf6deu.net/2fa.html)

> ![image](https://user-images.githubusercontent.com/83505381/146655188-d981fdfd-2d93-4b1e-814f-7f036917708a.png)
> ![image](https://user-images.githubusercontent.com/83505381/146655222-f185a1cb-fd1e-433b-a7e6-34511aae2df9.png)
> ![image](https://user-images.githubusercontent.com/83505381/146655283-b23011c5-bc6a-4133-b36f-fd5127984ef6.png)


### ユーザーガイド

このページは以下の3つから構成されています：
- [**QRコード生成/エンコード**](#QRコード生成/エンコード) - *あらゆるコンテンツまたはURLをQRコードにエンコードします。*
- [**QRコードスキャナ/デコード**](#QRコードスキャナ/デコード) - *QRコードをスキャンしてコンテンツを抽出します。*
- [**リアルタイムのOTP作成**](#リアルタイムのOTP作成) - *Google Authenticator(Google認証システム)から提供されるようなシークレットキーからワンタイムパスワード(OTP)を生成します。*


#### QRコード生成/エンコード

テキストボックスにQRコードとしてエンコードするURLもしくはコンテンツを入力します。(下のスクリーンショット内、赤色で強調表示されている部分)
> ![image](https://user-images.githubusercontent.com/83505381/146655317-76baef16-ffd1-4a7c-adbb-fc1e75d24b30.png)

同じように強調表示されている場所、QRコードに必要な設定をして、**作成**ボタンを押します。
> ![image](https://user-images.githubusercontent.com/83505381/146655335-7bbdd3b2-cc04-4d16-8a42-9ad554798c35.png)

QRコードは、PC/MAC/ラップトップでは右クリックして、携帯電話では画像を長押しして保存またはコピーできます。
> ![image](https://user-images.githubusercontent.com/83505381/146655366-8ede28ed-f596-40a6-92ac-d5c5d2742d25.png)



#### QRコードスキャナ/デコード

スキャン/デコードしたい画像を選択します。
> ![image](https://user-images.githubusercontent.com/83505381/146655606-edf1317a-338a-49ab-bf87-919f0a4a627f.png)

**デコード**ボタンを押します。
> ![image](https://user-images.githubusercontent.com/83505381/146655626-81bd4fcf-d37d-4eb5-839f-82ca29e2e6ce.png)

**リアルタイムのOTP作成**で使用できるコードが入手できます。
> ![image](https://user-images.githubusercontent.com/83505381/146655678-327e6d9d-5f40-4a7e-9c0d-58173d9967f9.png)


#### リアルタイムのOTP作成

シークレットキーを貼り付けます。
> ![image](https://user-images.githubusercontent.com/83505381/146655795-14fb2b06-90eb-460e-895e-14b51d12a84d.png)

OTPコードを表示します。
> ![image](https://user-images.githubusercontent.com/83505381/146655754-149536fb-5783-460e-be46-adb2fa0fb8dd.png)


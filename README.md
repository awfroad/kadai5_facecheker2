# kadai5_facecheker2_1126
APIを利用した自撮りアプリ

## ①課題内容（どんな作品か）
### 以前提出した課題facechekerを改良しました。
- インカメで自分の写真を保存出来ます。
- 以前撮影した写真と見比べて普段気付けない健康状態に気付いて欲しいです。
- 追加機能
  1 Googleログイン認証を追加しました。
  1 画像の保存先をlocal StorageからFirebaseに変更しました。
  1 顔認識APIを実装。ビデオ部分に映った自分の顔の感情分析が出ます。※写真部分非対応です。

## ②工夫した点・こだわった点
### 顔認識API
- APIを使用することが要件だったので、顔認識APIを使ってみました。
### Googleログイン認証
- ログイン認証にすることで個々人の個別のデータ保存が出来る様にしました。
### Firebaseへのデータ保存
- Firebaseに保存することでlocalStorageでは不安だったセキュリティが改善しました。

## ③難しかった点・次回トライしたいこと(又は機能)
### 難しかったこと
- 顔認識APIの実装
  - 顔認識APIをまともに動かすのに時間がかかりました。

### 次回トライしたいこと
- 感情分析データの保存
  - 感情分析データを載せた状態で画像を保存したかったです。
  - また、感情分析データを数値で抜き取り、保存と表示をしたかったです。
  
## ④質問・疑問・感想、シェアしたいこと等なんでも
- [感想]顔認識APIが上手く行った時は素直に嬉しく、一人で「まじか！」を連呼してました 笑  
  初めAzureのface APIを触ってみましたが、かなりハードルが高く感じたので、諦めて使えそうなものを探しました。
- [参考]
  - かじるプログラミング URL:https://www.youtube.com/watch?v=hOsqrGesOqQ&t=25s
  - justadudewhohacks URL:https://github.com/justadudewhohacks/face-api.js
  - Build Real Time Face Detection With JavaScript URL:https://www.youtube.com/watch?v=CVClHLwv-4I

# kadai01_janken02
じゃんけんアプリの２作目です（リッチver.）。

## DEMO

  - N/A

## 紹介と使い方

  - 前回の「ONE PIECEごっこ」を、「クイズに正解すればONE PIECEごっこができる」仕様に変更
  - クイズをランダムで出題し、4問正解すればジャンケンゲームができるように

## 工夫した点

  - TailwindCSSに初挑戦、「なんとなく」でデザインができるということはよくわかった
  - 検索とChatGPTに頼りながら、見様見真似で配列とオブジェクト（？）に挑戦し、クイズをランダムに出題することができた
  - LocalStrageもおまけ程度に追加してみた
  - Git hubでコードを提出してみた

## 苦戦した点
  - ややコードが冗長に感じるが、for文をうまく使いこなせていない
  - グラフ（ex.円グラフ）で表示したかったものの、作り方を調べてもよく理解できず今回は断念
    - 本当は「クイズ問題数」に対する正答率を円グラフで表示したい
    - canvasを使うのだということはわかったものの、作り方のhowがよく分からず、、
  - TailwindCSSのCLI対応がよく分からない
    - 対応を行ったところ、変更が２０００件を超える量で表示された（が、Githubにコミット＆プッシュすると、量が大幅に減った。なぜ…？）
  - ところで、検証画面のコンソールでは以下表示が出るがこれは一体何か？

![image](https://github.com/seiponfy23/kadai01_janken_rich/assets/132619946/9b4aeb24-218d-4672-b9d1-683b20d6696e)

## 参考にした web サイトなど

  - tailwindCSSの設定
  -   https://www.youtube.com/watch?v=0ZImKleAuUY
  -   https://github.com/yamazakidaisuke/tailwindcss_youtube/blob/main/setup.txt

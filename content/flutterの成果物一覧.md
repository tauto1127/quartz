# Flutterの成果物一覧

このページではFlutterを使用して開発したプロジェクトをまとめています。

## 2025年
### 遠隔遭遇を可能とするシステム「BATTARI」
#Flutter #サーバー #ASPNET #CSharp | [発表の様子(YouTube)](https://youtu.be/NdPTe2L6rFw?t=2683) | [Github(フロント)](https://github.com/BATTARI-team/BATTARI)|[バックエンド](https://github.com/BATTARI-team/BATTARI-api)

![[/assets/products/battari/battari_app_main_gimp.png]]

遠く離れたところで暮らしているかつ，微妙な関係の人同士だと連絡が途絶えてしまい人間関係が終了してしまうという問題にアプローチしたものです．
このシステムでは遠く離れていても，道端でばったりと誰かと遭遇するような体験をすることができます．それによって人間関係を続けられるように支援をします．近くに住んでいる場合や学校が同じである場合は時間軸と場所が一致というのが遭遇のトリガーになります．しかし遠距離だと場所の一致というのが難しくなります．そこでスマホで開いているアプリの一致というのを遭遇のトリガーにしてみました．開いているスマホのアプリが一定時間同じになると，遭遇と判定され通話が開始されます．
このように何も操作しないでも通話が開始されるため，リアルな遭遇体験を遠隔でも体験することができます．2人で作りました．

最初は本当に作れるのかなと思ったのですが，それぞれの機能のプロトタイプを作っていくと意外と作れるということがわかり，完成させることができました．新雪というプログラムの中で開発したのですが，その期間は短く後半はとても苦労してしまいました．そのような経験から細かく設計をして時間の見積もりを作る作業の大事さを実感しました．

#### モバイルアプリ
- AndroidアプリとフォアグラウンドサービスはFlutterで実装しています．
- 主な機能
    - バックグラウンドでのアプリの使用状況の取得
    - 通話機能（ロックを解除していれば，遭遇した時に自動で通話が開始）
    - Sentryによるログ収集
#### バックエンド
- バックエンドはASP.NET(C#)を用いて実装しています
- アプリとバックエンドとの通信をwebsocketで行うことによって，リアルタイムでの遭遇体験を実現しています．
#### インフラ
- バックエンドは自宅サーバーへの自動デプロイを行なっています．
selfhosted-runnerがサーバー上でビルド，データベースの更新まで行いその後デーモンを再起動することで構築しました

## 2024年
### E-Motion
#Flutter #ハッカソン | [Githubリポジトリ](https://github.com/p2hacks2024/post-04)

![[/assets/products/e-motion/EMotion.png]]

p2hacks2024という学内ハッカソンで作成しました。

服を着た人の感情の昂りを動きで検知し，その感情を光で表します。

自分はアプリの実装を担当しました。主にハードウェアとの繋ぎやロジックの実装，UIの実装を行いました。このアプリはアニメーションにこだわっていて，履歴画面の横スクロールや色の反転アニメーションが自慢です。ちょうどアニメーションをやりたいなと思ってた時だったので，楽しかったです。

![[/assets/products/e-motion/annimation-trimed.gif]]
![[/assets/products/e-motion/e-motion-rec-trimed.gif]]

### NECHUSHOW
#Flutter #ハッカソン | [Githubリポジトリ](https://github.com/Atori-Ikeyama/facondan-front)

SPAJAM2024で作ったものです。
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">スマホアプリハッカソン<a href="https://twitter.com/hashtag/SPAJAM?src=hash&amp;ref_src=twsrc%5Etfw">#SPAJAM</a><br>第1回予選 テーマ『猛暑』<br><br>#9<br>猛暑を超える熱中を共有<br>『NECHUSHOW』<br><br>熱中中の動画の熱中度が推定される！最高気温より高ければ優先して表示！<br><br>関節取得で動きの激しさをとる、音量を測定、言葉のポジティブさの推定など、計算にこだわり！<br>技術遊び楽しい🤣 <a href="https://t.co/jS2KoZaUxy">pic.twitter.com/jS2KoZaUxy</a></p>&mdash; koooootake (@koooootake) <a href="https://twitter.com/koooootake/status/1822515848684478774?ref_src=twsrc%5Etfw">August 11, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

自分はアプリの実装を担当しました。睡眠なしで1日しか開発期間がなかったので，とても大変でしたが楽しかったです。

### 家計簿アプリ
#Flutter #サーバー | [Githubリポジトリ](https://github.com/tauto1127/accountbook_for_obsidian_rest_api)

このアプリは自分の家計簿をつける習慣をより定着させようと作ったものです。自分はこのアプリを作る前からずっとObsidianというマークダウンエディターで家計簿を管理していました。しかしObsidianは同期の難易度が高く，特にAndroidでの同期が難しいです。そこでObsidianにRestApiが建てられるプラグインを見つけたのでそれを使ってスマホから家計簿をつけることができるアプリを作成しました。

## 2023年
### Strollary
#Flutter #Firebase #ハッカソン | [Githubリポジトリ](https://github.com/p2hacks2023/pre-02)

![[/assets/products/strollary/strollary-logo.png]]

p2hacks2023というハッカソンで制作したスマホアプリ(SNS)です。
[[p2hacks2023|詳細はこちら]]
# はじめに
高校生の頃からプログラミングをしてきてさまざまな成果物ができました．このページでは自分の"プログラミングが好きなところ"や"若干技術力がある"というところを感じていただけたらいいなと思います．

~~このページでは新しい順（作った日付が）で紹介していきますが，言語やフレームワーク別で紹介しているページもあるのでお好みで選んでください．~~

# 2024年
## 家計簿アプリ
#Flutter #サーバー | [Githubリポジトリ](https://github.com/tauto1127/accountbook_for_obsidian_rest_api)

このアプリは自分の家計簿をつける習慣をより定着させようと作ったものです．自分はこのアプリを作る前からずっとObsidianというマークダウンエディターで家計簿を管理していました．しかしObsidianは同期の難易度が高く，特にAndroidでの同期が難しいです．そこでObsidianにRestApiが建てられるプラグインを見つけたのでそれを使ってスマホから家計簿をつけることができるアプリを作成しました．

~~詳しくはこちらの[[accountbook_for_flutter | 家計簿アプリ紹介ページ]]をご覧ください．~~


## GithubのReadmeに表示する画像を生成してくれるバックエンドアプリ
#CSharp #ASPNET #バックエンド | [Githubリポジトリ](https://github.com/tauto1127/imageProviderForGithub)

このアプリはGithubのReadmeに表示する画像を生成してくれるバックエンドアプリです．

`[![My streak](https://api.takutk.com/StreakImg?username=tauto1127)](https://github.com/tauto1127/imageProviderForGithub)`

このようにGithubのReadme.mdに書くと，以下の画像のように連続でコミットメントした日数が表示されます．

![[Screenshot 2024-04-28 at 10.46.29.png]]

このアプリはCI/CDを頑張っていて，テストはないのですが自動ビルド，自動デプロイ（[[jitakuServer|自宅サーバー]]に），自動フォーマットがあります．

~~詳しくはこちらの[[imageProviderForGithub | GithubReadme画像生成紹介ページ]]をご覧ください~~

## 応用技術者試験のキーワードを抽出してくれるスクリプト
#TypeScript | [Githubリポジトリ](https://github.com/tauto1127/apKeywordParser)

# 2023年
## p2hacks2023(ハッカソン) 
#Flutter #Firebase | [Githubリポジトリ](https://github.com/p2hacks2023/pre-02)

## Discordボット
#CSharp #バックエンド | [Githubリポジトリ](https://github.com/tauto1127/harukinDiscordBot)

## ウェブサイトのユーザー認証をASPNETで実装してみたもの
#Csharp #バックエンド | [Githubリポジトリ](https://github.com/tauto1127/aspnetMVCUserTokenTest)

これはウェブサイトのユーザー認証の仕組みを勉強して，自分で実装してみたというものです．ユーザー認証関係のフレームワークは使っていなく，ハッシュ化の関数のみライブラリに頼って作りました．

主な機能(ユーザー認証関係)はこちらです
- パスワードをハッシュ化してそのままデータベースに保存するのではなく，「パスワードソルト」と「パスワードソルト」を使って保存する
- ユーザーのセッション管理

ウェブサイトも実装していて，そこからユーザー登録やログインができます．

# 2022年
## マインスイーパーを内蔵した目覚まし時計アプリ
#大学の課題 #processing | [Githubリポジトリ](https://github.com/tauto1127/minesweeper)

## ブロック崩し
#大学の課題 #processing | [Githubリポジトリ](https://github.com/tauto1127/blockKuzusi)

# 2021年
## DisplayOFF 
#CSharp #WPF #Windows | [Githubリポジトリ](https://github.com/tauto1127/DisplayOFF)

## ツイキャスコメントビューワー
#CSharp #WPF #Windows | [Githubリポジトリ](https://github.com/tauto1127/TwitcastingCommentViewer)
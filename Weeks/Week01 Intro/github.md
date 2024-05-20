---
marp: true
theme: uncover
headingDivider: 3
# footer: GIS ![width:30px](../Week02/images/yoh%20with%20globe.png)
paginate: true
---

<style>
small {font-size:0.8em}
medium {font-size:1.6em}
large {font-size:3.5em}
xlarge {font-size:4em}
gray {padding:20px;background-color:whitesmoke;font-weight:1200;line-height:2.5}
red {color:red;font-weight:500;}
plum {padding:5px;background-color:plum;line-height:1.5;font-weight:300; font-size:1.5em}
t1 { font-size:4em;font-weight:100;line-height:1}
xl { font-size:2.5em;font-weight:100;line-height:1}
h2 { font-size:1.8em;font-weight:300;line-height:1}
xls { font-size:1.5em;font-weight:100;line-height:1}
h1,h2,h3,h4,h5{}
section {font-size:2em;font-weight:300;}
left {text-align:left;}
latex {font-size:2em;color:#444;line-height:1;font-weight:lighter}

hr {background-color:gray;width:80%;margin-top:40px;margin-bottom:40px;}

.small {font-size:0.6em}
.large {font-size:2em}
.gray {padding:20px;background-color:whitesmoke;}
.plum {padding:15px;background-color:plum;}
</style>

## GitHub & VSCode

<hr>

![alt text](images/vscode_github.png)


## 

① VSCodeインストール

<medium>☞ https://code.visualstudio.com/</medium>

<hr>

② GitHubアカウントを作る


<medium>☞ http://github.com</medium>




## アカウントを確認し、ログインできたら<br><plum>リポジトリ</plum><br>を作ろう

<hr>

リポジトリって何?

- 自分で検索してresearch! <medium>🤓</medium>


## ログインして「Create repository」

*すでにアカウント持っている人は「Repositories」→ 「New」

![width:800](../Week02/images/github7.png)

## 

<plum>gis</plum>と名付けよう

![width:500](../Week02/images/github8.png)

## VSCodeとGitHubを連携

<medium>☞</medium> 初期設定なので一回やればもうやらなくていい

##

VSCodeの中でTerminalを立ち上げる

![Alt text](../Week02/images/vscode%20terminal.png)

##

あなたのusernameで次のコマンドを打ち込む

```
git config --global user.name "yohman"
```

![width:700](../Week02/images/vscode%20terminal2.png)

##

あなたのemailで次のコマンドを打ち込む

```
git config --global user.email "ykawano@reitaku-u.ac.jp"
```

![width:700](../Week02/images/vscode%20terminal3.png)

# GISリポジトリをGitHubから<br>VSCodeに<plum>クローン</plum>しよう

##


![Alt text](../Week02/images/clone%20commit.png)

## GitHubでリポジトリのリンクをコピー

![width:800](../Week02/images/gitvs1.png)

## VSCodeでリポジトリをクローン（コピー）する

![width:800](../Week02/images/gitvs2.png)

## 自分のパソコンの覚えやすいところに保存

![width:800](../Week02/images/gitvs3.png)

## README.md　ファイルを編集しよう

![width:800](../Week02/images/gitvs5.png)

## Markdownで自己紹介

![width:800](../Week02/images/markdown%20preview.png)

##
![Alt text](../Week02/images/logo%20markdown.png)
え？Markdownって何？

グーグルで検索！

例えば：

https://notepm.jp/help/how-to-markdown

## Challenge問題

自分の写真を載せよう


![width:500](../Week02/images/readme%20with%20photo.png)

## GitHubに<plum>コミット</plum>しよう

1. 「ソース管理」タブをクリック
1. 「変更」の隣のプラスボタンをクリック

![width:600](../Week02/images/commit1.png)

##

「ステージされている変更」にファイルが入っていることを確認

![Alt text](../Week02/images/commit2.png)

##

1. コメントを記入（とりあえず「First commit」と入力）
1. 「コミットしてプッシュボタン」をクリック


![Alt text](../Week02/images/commit3.png)


##

😫　エラーがある　➽　多半数
<hr>

👽　エラーがない　➽　あなたは天才

##

エラーがなければGitHubページに戻ってrefresh!

![width:500](../Week02/images/github%20commited.png)

## エラーがあれば一緒に解決しょう


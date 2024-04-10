---
marp: true
theme: uncover
headingDivider: 3
# footer: GIS ![width:30px](images/yoh%20with%20globe.png)
paginate: true
---

<style>
small {font-size:0.6em}
medium {font-size:0.9em}
large {font-size:2em}
xlarge {font-size:4em}
gray {padding:20px;background-color:whitesmoke;font-weight:800}
plum {padding:20px;background-color:plum;line-height:3;font-weight:800}
xl { font-size:2.5em;font-weight:100;line-height:1}
xls { font-size:1.5em;font-weight:100;line-height:1}
h1,h2,h3,h4,h5{font-family:serif}
section {font-size:2em;font-weight:300;}
left {text-align:left;}
</style>


## Week 3 | April 26, 2023


<xl>
Introduction to GIS 
</xl>

<br>
GISの世界へようこそ

#

今日の目標

<large>
自分のパソコンでGISができる

環境を作る
</large>

Part I

## 準備するもの
<hr>

1. git (install)
1. VSCode (install)
1. GitHub (create account and repo)
1. miniconda (install and create python environment) ← 次回

##

インストールする

![width:800](images/gitcondavs1.png)

##

アカウントを作る

![width:800](images/gitcondavs2.png)

##

クローンする

![width:800](images/gitcondavs3.png)

#

![Alt text](images/logo%20git.png)

##

https://git-scm.com/downloads

![width:800](images/git1.png)

##

全てデフォルトの設定で進んでインストール

<hr>
アプリではないので、インストールしたらそれでおしまい

#
![Alt text](images/logo%20vscode.png)

### インストールしよう

https://code.visualstudio.com/

##

![width:800](images/vscode1.png)

# 
![Alt text](images/logo%20github.png)

アカウントを作ってクラスのrepo(リポジトリ)を作成

## 

http://github.com

![width:800](images/github1.png)

## 

![width:800](images/github3.png)

## 

![width:800](images/github4.png)

## 

![width:800](images/github5.png)

## 

![width:800](images/github6.png)

## 

アカウントを確認し、ログインできたら<plum>リポジトリ</plum>を作ろう

##


![width:800](images/github7.png)

## 

<plum>gis</plum>と名付けよう

![width:550](images/github8.png)

##

リポジトリをGitHubからVSCodeに<plum>クローン</plum>しよう

##


![Alt text](images/clone%20commit.png)

## 
GitHubでリポジトリのリンクをコピー

![width:800](images/gitvs1.png)

## 

VSCodeでリポジトリをクローン（コピー）する

![width:800](images/gitvs2.png)

## 

自分のパソコンの覚えやすいところに保存

![width:800](images/gitvs3.png)

## 

![width:800](images/gitvs4.png)

## 

README.md　ファイルを編集しよう

![width:800](images/gitvs5.png)

##

Markdownで自己紹介

![width:800](images/markdown%20preview.png)

##
![Alt text](images/logo%20markdown.png)
え？Markdownって何？

グーグルで検索！

例えば：

https://notepm.jp/help/how-to-markdown

##

自分の写真を載せよう

##

imagesフォルダーを作成

![width:800](images/images%20folder.png)

##

自分の写真をimagesに入れる

![width:800](images/images%20folder2.png)

## 

Markdownで写真を載せる
```
![Yoh](images/yoh.jpg)
```


![width:500](images/readme%20with%20photo.png)

##

GitHubに<plum>コミット</plum>しよう

##

その前にVSCodeの設定を管理

##

VSCodeの中でTerminalを立ち上げる

![Alt text](images/vscode%20terminal.png)

##

あなたのusernameで次のコマンドを打ち込む

```
git config --global user.name "yohman"
```

![width:700](images/vscode%20terminal2.png)

##

あなたのemailで次のコマンドを打ち込む

```
git config --global user.email "ykawano@reitaku-u.ac.jp"
```

![width:700](images/vscode%20terminal3.png)

##

README.mdファイルをセーブした後…

##

1. 「ソース管理」タブをクリック
1. 「変更」の隣のプラスボタンをクリック

![width:600](images/commit1.png)

##

「ステージされている変更」にファイルが入っていることを確認

![Alt text](images/commit2.png)

##

1. コメントを記入（とりあえず「First commit」と入力）
1. 「コミットしてプッシュボタン」をクリック


![Alt text](images/commit3.png)


##

エラーがある　➽　多半数
<hr>
エラーがない　➽　あなたは天才

##

エラーがなければGitHubページに戻ってrefresh!

![width:500](images/github%20commited.png)

##

エラーがあれば一緒に解決しましょう

## 今週の課題

GitHubのREADME.md紹介ページを
さらに自己紹介の情報を足しましょう。

What I want to learn from this classも教えてください。

<plum>金曜日のmidnightまでに提出</plum>
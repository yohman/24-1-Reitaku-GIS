<!-- ---
marp: true
theme: uncover
headingDivider: 3
# footer: GIS ![width:30px](images/yoh%20with%20globe.png)
paginate: true
--- -->

<style>
small {font-size:0.8em}
medium {font-size:1.4em}
large {font-size:2.5em}
xlarge {font-size:4em}
gray {padding:20px;background-color:whitesmoke;font-weight:800;line-height:2.5}
red {color:red;font-weight:500;}
plum {padding:20px;background-color:plum;line-height:3;font-weight:800}
t1 { font-size:4em;font-weight:100;line-height:1}
xl { font-size:2.5em;font-weight:100;line-height:1}
xls { font-size:1.5em;font-weight:100;line-height:1}
/* h1,h2,h3,h4,h5{} */
/* section {font-size:2em;font-weight:300;} */
left {text-align:left;}
latex {font-size:2em;color:#444;line-height:1;font-weight:lighter}

.small {font-size:0.6em}
.large {font-size:2em}
.gray {padding:20px;background-color:whitesmoke;}
.plum {padding:20px;background-color:plum;}
</style>



# Week 3

<xl>
自分のパソコンでGISができる

環境を作る

</xl>


## 確認

✅ GitHubアカウント作った

✅ VSCodeインストールしてGitHubと連携させた

## 今日のやること

1️⃣
miniconda (install and create python environment) 


2️⃣
JupyterHub (install extension in VSCode) 



## 1️⃣ miniconda


<medium>👉🏼 <https://conda.io/></medium>





![width:800](images/conda%20dot%20io.png)

##

![width:1000](images/miniconda%20install.png)

## 仮想環境の作成

マック ➜ Terminal 「ターミナル」を開く

PC ➜ anaconda promptを開く

![width:300](images/anaconda%20prompt.png)

##

ターミナルに次のコマンドを打ち込む

```ps

conda create -n gis python＝3.11

```

↓

```Proceed ([y]/n)? y```
### 仮想環境の有効化

```ps

conda activate gis

```
すると
↓
```ps

(gis) C:\Users\yohman> 

```
頭にが```(gis)```がついた！


##

新しく作った環境にGISとデータビズで使うライブラリーをインストール

##

以下のライブラリーを一つずつインストール：

```
pip install geopandas
```

![width:400](images/geopandas%20install.png)

## 
これらも一つずつ、全部インストール🧐

```
pip install osmnx
```

```
pip install contextily
```

```
pip install plotly-express
```

```
pip install folium	
```

```
pip install keplergl
```

```
pip install seaborn
```



##
<xl>😫</xl>
エラーが出た　➽　多半数

<hr>

<xl>🤨</xl>

エラーがない　➽　あなたは天才

##

<xl>2️⃣</xl>
JupyterHub (install extension in VSCode) 

##

先週作ったGitHubフォルダーに接続
（もしかしたら、もう既に接続しているかも）

![width:600](images/vscode%20with%20github.png)

##

GISフォルダーで自動的に開かなかったら、もう一度オープンする

![Alt text](<images/vscode open folder.png>)
##
![width:500](images/install%20jupyter%20extension.png)

<table>
<tr><td><red>❶</red></td><td align='left'>Extensionタブを選ぶ</td></tr>
<tr><td><red>❷</red></td><td align='left'>サーチバーに「jupyter」と記入</td></tr>
<tr><td><red>❸</red></td><td align='left'>Jupyterをクリック</td></tr>
<tr><td><red>❹</red></td><td align='left'>インストールする</td></tr>
</table>

## Let's code!
<large>
🧑🏻‍💻👩🏻‍💻

##

<large>📁</large>「week3」フォルダーを作る

![width:600](images/vscode%20make%20week4%20folder.png)
<table>
<tr><td><red>❶</red></td><td align='left'>新しいフォルダーボタンをクリック</td></tr>
<tr><td><red>❷</red></td><td align='left'>「week3」と記入</td></tr>
</table>

##

<large>📄</large>「hello.ipynb」ファイルを作る

![width:600](images/vscode%20hello.png)
<table>
<tr><td><red>❶</red></td><td align='left'>新しいファイルボタンをクリック</td></tr>
<tr><td><red>❷</red></td><td align='left'>「hello.ipynb」と記入</td></tr>
</table>

## 🧐
以下のメッセージが出たらすかさずPythonインストール！

![width:900](<images/python extension.png>)

##

<large>📄</large>「gis」カーネルを選ぶ

![width:600](images/vscode%20choose%20kernel.png)
<table>
<tr><td><red>❶</red></td><td align='left'>カーネル選択ボタンをクリック</td></tr>
<tr><td><red>❷</red></td><td align='left'>「Python環境」をクリック</td></tr>
<tr><td><red>❸</red></td><td align='left'>「gis」を選ぶ</td></tr>
</table>

##

カーネルが「gis」であることを確認
![width:600](images/vscode%20gis%20environment.png)

##

![width:600](images/vscode%20code%20cell.png)


コードセルに以下のコードを記入して隣の▶️プレーボタン(実行)をクリック


```python
print('hello world!')
```
*実行のキーボードショートカットは<span style="border: 1px solid black; padding: 5px;background-color:whitesmoke;">SHIFT</span> + <span style="border: 1px solid black; padding: 5px;background-color:whitesmoke;">Enter</span>


##

![width:800](images/vscode%20hello%20world.png)

<table>
<tr><td><red>❶</red></td><td align='left'>セルがPythonであることを確認</td></tr>
<tr><td><red>❷</red></td><td align='left'>セルの中にprintコマンド</td></tr>
<tr><td><red>❸</red></td><td align='left'>結果がセルの下に出力</td></tr>
</table>

##

Oh yeah! I can write Python!🤯

```python
# math
a = 10
b = 20
print(a+b)
print(a*b)
```

```python
# text
name = "Ryunosuke"
print(name, "is cool")
```



##

新しいコードセルを作る
次のコードを打ち込む：

```python
import folium

folium.Map(location=[35.833, 139.955])
```

##

同じセルで```zoom_start```を足す

```python
folium.Map(location=[35.833, 139.955], zoom_start=14)
```

##

![bg right:40%](images/google%20maps.png)

地図の```latlon```を変えよう

1. https://www.google.com/maps
1. zoom to your hometown (生まれた場所)
1. right click!
1. 数字をコピー
1. コードを変更！

## GitHubにアップロードしよう！

```① Save``` ➽ ```② pull``` ➽ ```③ stage ``` ➽ ```④ commit ```

##

① Save `hello.ipynb`

CMD + S
CTRL + S

![width:600](images/vscode%20save.png)
* タブの右隣のアイコンが ● から <b>Ⓧ</b> に変わったらオッケー

##

② Pull

![width:600](images/vscode%20pull.png)

##

③ Stage

![width:600](images/vscode%20stage.png)

##

④ Commit

![width:600](images/vscode%20commit.png)
<table>
<tr><td><red>❶</red></td><td align='left'>「week 3」を記入</td></tr>
<tr><td><red>❷</red></td><td align='left'>「コミット」ボタンをクリック</td></tr>
</table>

## Week 3 Challenge

もっとすごい地図を作らない？

Folium's quickstart guideに従って、「自分」の地図を作って提出しよう。

<small>

- https://python-visualization.github.io/folium/latest/getting_started.html
- https://qiita.com/Kumanuron-1910/items/12ce7aa02922927de2f4

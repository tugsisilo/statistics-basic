# はじめに

```{only} html
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![made-with-numpy](https://img.shields.io/badge/Made%20with-NumPy-1f425f.svg)](https://numpy.org/)
[![made-with-matplotlib](https://img.shields.io/badge/Made%20with-Matplotlib-1f425f.svg)](https://matplotlib.org/)
[![made-with-scikit-learn](https://img.shields.io/badge/Made%20with-scikit--learn-1f425f.svg)](https://scikit-learn.org/)
```

## この教材について
この教材は数理・データ科学・AIの導入により地域企業を変革するDXインフルエンサの養成プログラムの講座「統計プログラミングの初歩」のメインコンテンツです．利用するためには Google アカウントを持っている必要があります．

:::{panels}
:container:
:column: col-lg-6 px-2 py-2
:card:

---
**対象者**
^^^
これから統計学についての知識を深めたい人．プログラミングの経験や統計学に関する知識はないことを前提にしています．

---
**Python**
^^^
プログラミング言語 [Python](https://www.python.org/) の利用方法を紹介します．Python は機械学習法を実装するための便利なライブラリを有する，データ科学を利用した研究開発に便利な言語です．

```python
#!/usr/bin/env python3

def main():
    print("Hello world")
     
if __name__ == "__main__":
    main()
```

---
**NumPy**
^^^
[NumPy](https://numpy.org/) は Python から呼び出せる，数値計算を行うためのライブラリです．これを利用して基本統計処理や行列計算を学びます．

---
**pandas**
^^^
[pandas](https://pandas.pydata.org/) は Python から呼び出せる，データを直感的に扱うためのライブラリです．これを利用して多変量データ解析を学びます．

---
**matplotlib**
^^^
[matplotlib](https://matplotlib.org/) は Python から呼び出せる，描画をするためのライブラリです．データの可視化を行います．

---
**scikit-learn**
^^^
[scikit-learn](https://scikit-learn.org/) は機械学習法を実現するためのライブラリです．この講座では線形回帰をするために利用します．



:::

### このコンテンツで学ぶこと
このコンテンツの目的は，ウェブベースの計算環境である Jupyter Notebook（このウェブページを形作っているもの）を利用して，Python で実際にプログラミングをすることで統計解析の基本を学ぶものです．このコンテンツは東北大学大学院情報科学研究科の小池敦が主に構築したものを同じく山田和範が編集したものです．
```{note}
つまり，このコンテンツに間違いが含まれていても山田はまったく悪くなくて元の作成者が悪いです．
```
### この環境について
Jupyter Notebook は Python を実行するための環境です．メモを取りながら Python のコードを実行することができます．この環境は，Python プログラムがコマンドライン上で実行される実際の環境とは少し異なるのですが，Python プログラムがどのように動くかということを簡単に確認しながら学習することができます．

## 教材の利用方法
この教材は Google Colaboratory（グーグルコラボラトリー）を利用して作られています．グーグルコラボラトリーは Jupyter Notebook のファイルをウェブブラウザから使えるように Google が用意してくれたアプリです．各ページの上部にロケットのアイコン <i class="fa fa-rocket" aria-hidden="true"></i> があるのでこれをクリックして各ページのファイルを Google Colaboratory 上で開いて利用してください．


### 開始前に行うこと

```{hint}
グーグルコラボラトリー自体の一番上の「ファイル」をクリックし，さらにポップアップで出てくる項目から「ドライブにコピーを保存」をクリックし，自身のグーグルドライブにこのウェブページ全体のソースを保存します（グーグルのアカウントが必要です）．こうすることによって，自分で書いたプログラムを実行することができるようになります．また，メモ等を自由に以下のスペースに追加することができるようになります．
```

### コードセル

コードセルとは，Python のコードを書き込み実行するためのセルです．以下のような灰色のボックスで表示されていますす．ここにコードを書きます．実行はコードセルの左に表示される「実行ボタン」をクリックするか，コードセルを選択した状態で `Ctrl + Enter` を押します．環境によっては行番号が表示されていると思いますので注意してください（行番号の数字はプログラムの構成要素ではありません）．

```python
print("This is a code cell.")
```

### 進め方

上から順番に読み進めます．Python のコードが書かれていますので，それをコードセルに入力して実行します．コード内の値を変えたり，関数を変えたりして挙動を確かめてみてください．

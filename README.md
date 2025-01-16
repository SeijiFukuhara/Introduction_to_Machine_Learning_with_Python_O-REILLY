# 概要
![](Pythonではじめる機械学習-1.jpeg)

O'REILLYの書籍「Pythonではじめる機械学習　scikit-learnで学ぶ特徴量エンジニアリングと機械学習の基礎」を基に，コードを写しながら学習したもの．

# 1章 はじめに
[1_はじめに](./notebooks/1_はじめに.ipynb)

# 2章 教師あり学習
教師あり学習は，最もよく用いられ，そしてうまく機能しているタイプの機械学習だ．本章では教師有学習について詳しく述べ，いくつかのよく使われる教師有学習アルゴリズムについて説明する．本章では教師有学習について詳しく述べ，いくつかのよく使われる教師あり学習アルゴリズムについて説明する．
## 2.1 クラスの分類と回帰
- 教師あり機械学習問題
    - **クラス分類** あらかじめ定められた選択肢の中から**クラスラベル**を予測すること
        - **２クラス分類** ２つだけのクラスを分類する特殊ケース（答えがyes/no）
        - **多クラス分類** ３つ以上のクラスを分類する問題（アイリス，Webサイトのテキストから，そのWebサイトの使用している言語を予測する問題）
    - **回帰** 目的は連続値の予測．（ある人の年収を学歴と年齢と住所から予測する/トウモロコシ農家の収穫量を，前年の収穫量，天候，従業員数から予測する）
 
クラス分類問題と回帰分類問題を区別するには，出力に何らかの連続性があるかを考えてみればよい．出力に連続性があるなら回帰問題である．

## 2.2 汎化，過剰適合，適合不足
### 2.2.1 モデルの複雑さとデータセットの大きさ

## 2.3 教師あり機械学習アルゴリズム
### 2.3.1 サンプルデータセット
[2_3_1_サンプルデータセット](./notebooks/2_3_1_サンプルデータセット.ipynb)
### 2.3.2 k-最近傍法
[2_3_2_k-最近傍法](./notebooks/2_3_2_k-最近傍法.ipynb)
### 2.3.3 線形モデル
[2_3_3_線形モデル](./notebooks/2_3_3_線形モデル.ipynb)  
### 2.3.4 ナイーブベイズクラス分類器
[2_3_4ナイーブベイズクラス分類器](./notebooks/2_3_4_ナイーブベイズクラス分類器.ipynb)  
### 2.3.5 決定木
[2.3.5_決定木](./notebooks/2_3_5_決定木.ipynb)
### 2.3.6 決定木のアンサンブル法
[2.3.6_決定木のアンサンブル法](./notebooks/2_3_6_決定木のアンサンブル法.ipynb)  
**アンサンブル法**（Ensembles）とは、複数の機械学習モデルを組み合わせることで、より強力なモデルを構築する手法だ。機械学習の文献にはこのカテゴリの手法がたくさん存在するが、さまざまなデータセットに対するクラス分類や回帰に関して有効であることがわかっているアンサンブル法が２つある。ランダムフォレストと勾配ぶースティング法である。
### 2.3.7 カーネル法を用いたサポートベクターマシン
[2.3.7_カーネル法を用いたサポートベクターマシン](./notebooks/2_3_7_カーネル法を用いたサポートベクターマシン.ipynb)
### 2.3.8 ニュートラルネットワーク（ディープラーニング）
[2.3.8_ニューラルネットワーク（ディープラーニング）](./notebooks/2_3_8_ニューラルネットワーク（ディープラーニング）.ipynb)  
ニューラルネットワークというアルゴリズムが、最近「ディープラーニング」という名前で再度注目を集めている。ディープラーニングとは、多くの機械学習アプリケーションに対して期待できる結果を示しているが、ディープラーニングアルゴリズムの多くは特定のアプリケーションに向けて注意深く作られたものだ。ここでは、比較的簡単な**多層パーセプトロン**（multilayer perceptron: MLP）によるクラス分類と回帰についてだけ議論する。これらは、より複雑なディープラーニングを理解する上で、良い入口になるはずだ。多層パーセプトロンは、フィードフォワード・ニューラルネットワークもしくはただニューラルネットワークと呼ばれる。

## 2.4 クラス分類器の不確実性推定
[2_4_クラス分類器の不確実性推定](./notebooks/2_4_クラス分類器の不確実性推定.ipynb)
### 2.4.1 決定関数（Decision Function）
### 2.4.2 確率の予測
### 2.4.3 多クラス分類の不確実性

## 2.5 まとめと展望
[2.5_まとめと展望](./notebooks/2_5_まとめと展望.ipynb)

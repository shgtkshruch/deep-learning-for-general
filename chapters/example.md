# 🏢 事例・サービス

## 社会実装
- [BRETT: Deep-learning robot](https://engineering.berkeley.edu/brett/)
- [AlphaGo](https://ja.wikipedia.org/wiki/AlphaGo)
- [Google DeepMind's Deep Q-learning playing Atari](https://deepmind.com/research/publications/playing-atari-deep-reinforcement-learning)
- [分身ロボットカフェ DAWN](https://dawn2019.orylab.com/)
- [Facenet](https://arxiv.org/abs/1503.03832)
  - Google が開発した顔認識システム
- [Tay](https://ja.wikipedia.org/wiki/Tay_(%E4%BA%BA%E5%B7%A5%E7%9F%A5%E8%83%BD))
  - Microsoft が開発したチャットボット。間違った方向に学習が進み不適切な発言をするようになった

## Cloud

### Google
- [Natural Language](https://cloud.google.com/natural-language?hl=ja)

### AWS

### Microsoft

## Community
- [Kaggle](https://www.kaggle.com/)

## Library

##### [scikit-learn](https://scikit-learn.org/stable/index.html)
Python でもっとも利用されている機械学習ライブラリ。
教師あり学習、教師なし学習、次元削減のさまざまなアルゴリズムを備えている。

##### [NumPy](https://numpy.org/)
多次元配列を扱うためのさまざまな機能がパッケージされたライブラリ。

##### [pandas](https://pandas.pydata.org/)
配列操作の中でもデータ分析に特化したライブラリ。
表形式のデータに対するさまざまな処理をサポートしている。

### 文章データの前処理

##### mecab
日本語の形態素解析ライブラリ。

##### [NLTK](https://www.nltk.org/)
英語の形態素解析ライブラリ。

### 画像データの前処理

##### [OpenCV](https://opencv.org/)
コンピュータで画像や動画を処理するためのさまざまな処理を実装できるライブラリ。

画像のぼかしや二値化、グレースケールに拡大縮小、回転などの基本操作から、エッジ検出やヒストグラムの計算など、機械学習アルゴリズムに入力するために必要な前処理を網羅している。

### データの可視化

##### [matplotlib](https://matplotlib.org/)
折れ線グラフや棒グラフなどの基本的なグラフから、ヒストグラムなどの統計用グラフや3D散布図など、多様な表示形式を利用できる。

##### [seaborn](https://seaborn.pydata.org/)

## Framework

##### [TensorFlow](https://www.tensorflow.org/?hl=ja)
Google の開発するディープラーニングのフレームワーク。

TensorBoard という可視化ソフトフェアが付属しており、計算グラフを表示できるほか、学習がどのように進んでいったかわかりやすく可視化できる。

##### PyTorch
Facebook が開発している TensorFlow と双璧をなすフレームワーク。

デフォルトで Define-by-Run アプローチが取られ、動的に計算グラフを生成していくため、柔軟な計算ができる。

##### Keras
非常に簡単なコードでモデルを組み込み学習を行うことができる。
学習自体は裏で TensorFlow が行っている。
Keras は TensorFlow のラッパー。

##### [Caffe](https://caffe.berkeleyvision.org/)

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

## GPU

##### GPU
画像処理に必要な大規模な並列演算処理を行う。

GPU(GPGPU)の開発をリードしているのは NVIDIA。

##### GPGPU
GPU を画像以外の目的での利用に最適化したもの。

#### TPU
Google が開発したテンソル計算処理に最適化された GPU。

## セキュリティ

##### Adversarial attacks（敵対的な攻撃）
誤った学習を引き起こすように意図的に入力に小さな摂動を加えて、アルゴリズムを騙す攻撃。

## 自動運転
自動運転技術を搭載した「自動運転車」は、運転手と車(システム)のどちらが運転動作の主体となるか、また走行可能エリアはどうなるか、によってレベル0～5の6段階に分かれている。

このレベル分けはアメリカの非営利団体SAEインターナショナルが発表したもので、現在 日本はもちろんのこと、世界においても共通の基準と認識されている。

| 自動運転レベル | 名称 | 主体者 | 走行可能エリア | ルール |
| --- | --- | --- | --- | --- | --- |
| 0 | 運転自動化なし | 運転者	| –	| 運転者が全てのタスクを担当 (つまり従来の運転状態) |
| 1 | 運転支援 | 運転者 | 限定的 | 速度かハンドルを運転手が対応 走行エリアの限定あり |
| 2 | 部分運転自動化 | 運転者 | 限定的 | 常時 運転手がシステムを監督 走行エリアの限定あり |
| 3 | 条件付き運転自動化 | 車(システム) | 限定的 | 緊急時は運転手が対応 走行エリアの限定あり |
| 4 | 高度運転自動化 | 車(システム) | 限定的 | 運転手なしでの走行OK 走行エリアの限定あり |
| 5 | 完全運転自動化 | 車(システム) | 限定なし | 運転手なしでの走行OK 走行エリアの限定なし |

##### [Waymo](https://ja.wikipedia.org/wiki/%E3%82%A6%E3%82%A7%E3%82%A4%E3%83%A2)
Alphabet傘下の自動運転車開発企業。
2016年12月13日にGoogleの自動運転車開発部門が分社化して誕生した

## ドローン

まとめ
- https://www.drone-osaka.com/column/article002.html
- https://viva-drone.com/law-on-drones-in-japan/

### 飛行禁止区域
- 空港/国の重要施設/原子力事業所等の周辺、私有地上空
- 150m以上の上空
- 人家の集中地域

### 飛行状況に関してのルール
- 日中での飛行に限る(夜間は禁止)
- 目視の範囲内(見えなくなる場所に飛ばすのは禁止)
- 距離の確保(対人、対物への距離をとる)
- イベント場所での飛行禁止
- 危険物輸送/物件投下の禁止

## 軍事

##### LAWS（自律型致死性兵器）
人工知能などにより、**完全に自律し**、かつ強力な殺傷能力を持つ兵器。

現段階では存在していないが、将来、完全な自律型致死性兵器が開発された場合、民間人・味方を攻撃しかねないという倫理的な理由から、専門家の間で議論が続いている。

##### 特定通常兵器使用禁止制限条約（CCW）
過剰な傷害または無差別の効果を発生させると認定される通常兵器の使用を禁止または制限する多国間条約。
近年は LAWS に関する政府専門家会合がくり返し開催され、活発な議論が続けられている。

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

##### [Chainer](https://chainer.org/)
Preferred Network によって開発されたフレームワーク。

Define-by-Run  という形式を採用している。
開発の終了が発表されており、今はメンテナンスフェーズになっている。

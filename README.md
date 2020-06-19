# Deep Learning for General

## 歴史
- [ダートマス会議](https://ja.wikipedia.org/wiki/%E3%83%80%E3%83%BC%E3%83%88%E3%83%9E%E3%82%B9%E4%BC%9A%E8%AD%B0)  
1956年7月から8月にかけて開催された[ジョン・マッカーシー](https://ja.wikipedia.org/wiki/%E3%82%B8%E3%83%A7%E3%83%B3%E3%83%BB%E3%83%9E%E3%83%83%E3%82%AB%E3%83%BC%E3%82%B7%E3%83%BC)が主催した会議で、史上初めて「人工知能（Artificial Intelligence）」という用語が使われた。
### 第1次AIブーム
- 探索・推論
- トイ・プロブレム
- 幅優先探索
- 深さ優先探索
- ハノイの塔
- ロボットの行動計画（プランニング）
- STRIPS
- SHRDLU
- Mini-Max法
- モンテカルロ法

### 第2次AIブーム
- エキスパートシステム
- 第5世代コンピュータ
- 人工無能
- イライザ（ELIZA）
- マイシン（MYCIN）
- DENDRAL
- 意味ネットワーク
- Cycプロジェクト
- オントロジー
- ヘビーウェイトオントロジー
- ライトウェイトオントロジー
- ワトソン

### 第3次AIブーム
- ビックデータ
- ディーブラーニング
- シンギュラリティー
- 機械学習
- ディーブラーニング
- 特徴量
- ILSVRC

## 人物
- [ジェフリー・ヒントン](https://ja.wikipedia.org/wiki/%E3%82%B8%E3%82%A7%E3%83%95%E3%83%AA%E3%83%BC%E3%83%BB%E3%83%92%E3%83%B3%E3%83%88%E3%83%B3)

## 概要
- [人工知能](https://ja.wikipedia.org/wiki/%E4%BA%BA%E5%B7%A5%E7%9F%A5%E8%83%BD)
- [機械学習](https://ja.wikipedia.org/wiki/%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92)
- [ニューラルネットワーク](https://ja.wikipedia.org/wiki/%E3%83%8B%E3%83%A5%E3%83%BC%E3%83%A9%E3%83%AB%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF)
- [ディープラーニング](https://ja.wikipedia.org/wiki/%E3%83%87%E3%82%A3%E3%83%BC%E3%83%97%E3%83%A9%E3%83%BC%E3%83%8B%E3%83%B3%E3%82%B0)

## 人工知能分野の問題
- トイ・プロブレム
- フレーム問題
- チューリングテスト
- 強いAI
- 弱いAI
- シンボルグラウディング問題
- [He saw a woman in the garden with a telescope](https://www.deepl.com/ja/translator#en/ja/He%20saw%20a%20woman%20in%20the%20garden%20with%20a%20telescope)
- 特徴量設計

## 機械学習の代表的な手法
- 教師あり学習
- 教師なし学習
- 強化学習
- 回帰問題
- 分類問題

### 教師あり学習
- 線形回帰
- ロジスティク回帰
- ランダムフォレスト
- ブートストラップサンプリング
- バギング
- ブースティング
  - AdaBoost
  - 勾配ブースティング
  - XgBoost
- サポートベクターマシン
- ニューラルネットワーク
  - 単純パーセプトロン
  - 誤差逆伝播法
  - シグモイド関数

### 教師なし学習
- k-means
- 主成分分析

### 手法の評価
- 訓練データ
- テストデータ
- 交差検証
- ホールドアウト検証
- k-分割交差検証
- 検証データ
- 混同行列
- 正解率
- 適合率
- 再現率
- F値
- オーバーフィッティング
- アンダーフィッティング
- ラッソ回帰
- リッジ回帰
- Elastic Net

## ディーブラーニング
- 多層パーセプトロン
- オートエンコーダ
- ディーブオートエンコーダ
- 事前学習
- ファインチューニング

### 活性化関数
- tanh（ハイパボリックタンジェント関数）
- ReLU関数
- Leaky ReLu関数
- Parametric ReLU
- Randomized ReLU

### 学習率の最適化
- 勾配降下法
- 誤差関数
- Adagrad
- Adadelta
- RMSprop
- Adan

### テクニック
- ドロップアウト
- early stopping
- 正規化
- 標準化
- 白色化
- バッチ正規化

### CNN: 畳み込みニューラルネットワーク
- LeNet
- 畳み込み
- プーリング
- maxプーリング
- avgプーリング
- 全結合層
- データ拡張
- AlexNet
- VGG
- GoogLeNet

### RNN: リカレントニューラルネットワーク

### 深層強化学習

### 深層生成モデル


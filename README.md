# Deep Learning for General

## :scroll: 歴史
- [ダートマス会議](https://ja.wikipedia.org/wiki/%E3%83%80%E3%83%BC%E3%83%88%E3%83%9E%E3%82%B9%E4%BC%9A%E8%AD%B0)  
1956年7月から8月にかけて開催された[ジョン・マッカーシー](https://ja.wikipedia.org/wiki/%E3%82%B8%E3%83%A7%E3%83%B3%E3%83%BB%E3%83%9E%E3%83%83%E3%82%AB%E3%83%BC%E3%82%B7%E3%83%BC)が主催した会議で、史上初めて「人工知能（Artificial Intelligence）」という用語が使われた。
- ENIAC(エニアック)  
1946年に開発された世界初のコンピュータ

### 人工知能のレベル
- 人工知能（AI: Artificial Intelligence)  
コンピュータによる知的な情報処理システムを設計、または実現するための研究分野。研究者によって定義は異なる。

- 機械学習  
人工知能を実現するための手法のうち特に、人間の学習能力、予測能力をコンピュータで実現しようとする技法や手法の総称

- ディーブラーニング（深層学習）  
ディープニューラルネットワークを用いて学習を行う、機械学習のアルゴリズムの1つ。

- 特化型人工知能  
特定のタスクでのみ成果を出せる人工知能。弱い人工知能。現在の技術ではこちらしか実現できていない。

- 汎用人工知能  
人間と同等の知能を持もった人工知能。強い人工知能。

- レベル1
- レベル2
- レベル3
- レベル4

### 第1次AIブーム（1956 - 1974: 探索・推論による人工知能）
冷戦下のアメリカで、自然言語処理による機械翻訳の研究に注力されていたことが有名。しかし当時は、実用的な機械翻訳を行うことはきわめて困難であると結論された。
- チューリングテスト(1950)  
ある機械が人工知能かどうか判定するためのテスト。「機械が知能をもっているか」という問いから、「機械が知能をもっている存在として人間が認知できるか」という問題に置き換えている。

- 推論  
自分がもつ知識と知識を組み合わせることで新しい知識を見つけ出す

- 探索  
推論により導き出せる結果を、いかに早くおこなえるかを求めた手法。問題をうまく表現することができれば、効率的に解を見つけ出すことができる

- 人工知能を考える視点  
環境・状態・行動をコード化できるとそのタスクは人工知能で解くことができる。推論・探索ではこの3要素を機械が理解できる形に書けないと解くことができない。

- トイ・プロブレム  
迷路やオセロなど、機械にときやすい簡単な問題

- [ELIZA(イライザ)](https://ja.wikipedia.org/wiki/ELIZA)  
1966年に発表された自然言語処理プログラム。人工無脳の起源となった。

- [PARRY](https://ja.wikipedia.org/wiki/PARRY)  
1972年に開発された ELIZA と共に有名な初期の会話ボット。ELIZA との最初の会話記録は [RFC439](https://tools.ietf.org/html/rfc439) に残されている。

- 幅優先探索
- 深さ優先探索
- ハノイの塔
- ロボットの行動計画（プランニング）
- STRIPS
- SHRDLU
- Mini-Max法
- モンテカルロ法

### 第2次AIブーム（1980 - 1987: 知識表現による人工知能）
エキスパートシステムにより問題を解く人工知能が台頭。しかし専門家の知識の定式化は難しく、複雑な問題が解けるようにならなかった。

- エキスパートシステム  
専門家の知識をそのまま人工知能に移植する事により、さまざまな問題を解決するアイディア

- [MYCIN(マイシン)](https://ja.wikipedia.org/wiki/Mycin)  
1970年代初めに5、6年の歳月をかけて開発された抗生物質を処方するAI

- [DENDRAL](https://ja.wikipedia.org/wiki/Dendral)  
1906年代の人工知能プロジェクト。有機化合物の特定を行う

- 知識ベース  
if-then 文よって記述できる知識の集まり

- 推論エンジン  
知識ベースを用いて推論を行うプログラム

- 第5世代コンピュータ
- 人工無能
- 意味ネットワーク
- Cycプロジェクト
- オントロジー
- ヘビーウェイトオントロジー
- ライトウェイトオントロジー
- ワトソン

### 第3次AIブーム（2000 -: 機械学習と深層学習による人工知能）
- ビックデータ

- ディーブラーニング

- [シンギュラリティー（技術的特異点）](https://ja.wikipedia.org/wiki/%E6%8A%80%E8%A1%93%E7%9A%84%E7%89%B9%E7%95%B0%E7%82%B9)  
[レイ・カーツワイル](https://ja.wikipedia.org/wiki/%E3%83%AC%E3%82%A4%E3%83%BB%E3%82%AB%E3%83%BC%E3%83%84%E3%83%AF%E3%82%A4%E3%83%AB) が提唱した、人工知能が人間を超えて文明の主役に取って代わる時点。カーツワイルは 自著「The Singularity Is Near」で「シンギュラリティは2045年に到来する」と述べた。

- 機械学習

- ディーブラーニング

- 特徴量

- [ILSVRC(Large Scale Visual Recognition Challenge)](http://www.image-net.org/challenges/LSVRC/)  
2010年から始まった ImageNet データセットを用いた画像認識の精度を競うコンペ。  
2012年、トロント大学の[ジェフリー・ヒントン](https://ja.wikipedia.org/wiki/%E3%82%B8%E3%82%A7%E3%83%95%E3%83%AA%E3%83%BC%E3%83%BB%E3%83%92%E3%83%B3%E3%83%88%E3%83%B3)教授のチームが [AlexNet](https://en.wikipedia.org/wiki/AlexNet) と呼ばれる畳み込みニューラルネットワーク(CNN)で[2位以下を10%以上引き離す結果](http://image-net.org/challenges/LSVRC/2012/results.html)を出す。これがきっかけとなり、ディーブラーニングが一気に脚光を浴びる。

[人工知能](https://ja.wikipedia.org/wiki/%E4%BA%BA%E5%B7%A5%E7%9F%A5%E8%83%BD) > [機械学習](https://ja.wikipedia.org/wiki/%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92) > [ニューラルネットワーク](https://ja.wikipedia.org/wiki/%E3%83%8B%E3%83%A5%E3%83%BC%E3%83%A9%E3%83%AB%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF) > [ディープラーニング](https://ja.wikipedia.org/wiki/%E3%83%87%E3%82%A3%E3%83%BC%E3%83%97%E3%83%A9%E3%83%BC%E3%83%8B%E3%83%B3%E3%82%B0)
- [モラベックのパラドックス](https://ja.wikipedia.org/wiki/%E3%83%A2%E3%83%A9%E3%83%99%E3%83%83%E3%82%AF%E3%81%AE%E3%83%91%E3%83%A9%E3%83%89%E3%83%83%E3%82%AF%E3%82%B9)  
子供のできることほど人工知能には難しい

## 人工知能分野の問題
- トイ・プロブレム

- フレーム問題  
ある問題を解決する際に、その問題位関連する、考慮すべき事柄を抽出することが AI には難しいこと

- 強いAI  
フレーム問題を打破し、人間のようにあらゆる問題に適切に対処できるようになった AI

- 弱いAI  
フレーム問題に縛られたままの AI

- シンボルグラウディング問題  
記号システム内のシンボルがどのようにして実世界の意味と結び付けられるかという問題

- [He saw a woman in the garden with a telescope](https://www.deepl.com/ja/translator#en/ja/He%20saw%20a%20woman%20in%20the%20garden%20with%20a%20telescope)

- 特徴量設計

## 🖥️ 機械学習
- [ネオコグニトロン](https://ja.wikipedia.org/wiki/%E3%83%8D%E3%82%AA%E3%82%B3%E3%82%B0%E3%83%8B%E3%83%88%E3%83%AD%E3%83%B3)

### 代表的な手法
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

## :robot: ディープラーニング
- ニューロン  
単純な数値予測ができ予測器。ニューラルネットワークの最小単位

- ニューラルネットワーク  
ニューロンをたくさんつなげててきる予測器。入力が行わる層を「入力層」、出力される層を「出力層」、それ以外の層を「中間層」または「隠れ層」と呼ぶ。

- 単純パーセプトロン

- 多層パーセプトロン

- オートエンコーダ
- ディープオートエンコーダ
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
- Skip connection  
層を飛び越えた結合
- 転移学習  
学習済みのネットワークを利用して新しいタスクの識別に利用すること

### RNN: リカレントニューラルネットワーク
時系列データを入力して、データから時間依存性を学習できるモデル

- Backpropagation Through Time(BPTT)
- 入力重み衝突
- 出力重み衝突
- LSTM(Long Short-Term Memory)
- GRU(Gated Recurrent Unit)
- Bidirectional RNN　　
LSTM を2つ組み合わせることで、未来から過去方向も含めて学習できるモデル

- Sequence-to-Sequence  
入力が時系列なら出力も時系列で予測する。自然言語処理を中心に研究されている分野。

- RNN Encoder–Decoder

- Attention  
過去の時点それぞれの重みを学習することで、時間の重みをネットワークに組み込む。

### 深層強化学習
- 強化学習  
行動を学習する仕組み。目的とする報酬（スコア）を最大化するためにはどのような行動をとっていけばいいかを学習していく。

### 深層生成モデル
- WaveNet
- 生成モデル
- VAE(変分オートエンコーダ)
- GAN(敵対的生成ネットワーク)
- DCGAN(Deep Convolutional GAN)

## 🔬 ディープラーニングの研究分野

### 画像認識分野
- AlexNet(アレックスネット)
- R-CNN
- fast RCNN
- faster RCNN
- YOLO(You Only Look Once)
- SSD(Single Shot Detector)
- セマンティックセグメンテーション
- FCN(完全畳み込みネットワーク)
- アンサンプリング
- インスタンスセグメンテーション
- Mask RCNN

### 自然言語処理
- word2vec
- 単語埋め込みモデル
- スキップグラム
- CBOW
- fastText
- ELMo
- 普遍埋め込みモデル
- NIC(ニューラル画像脚注付け)
- NTM(ニューラルチューリングマシン)

### 音声認識
- WaveNet

### 強化学習
- DQN(Deep Q-Network)
- MCTS(モンテカルロ木探索)
- AlphaGo Zero
- セルフプレイ
- RAINBOWモデル

## 🏛️ 法律・倫理・現行の議論
- プライバシーバイ・デザイン

- 倫理的に調和された設計  
2016年にIEEEが出したレポート

- データの利用条件
1. 著作権法 2. 不正競争防止法 3. 個人情報保護法 4. 個別の契約 5. その他の理由により、データの利用に制約がかかっている場合

- 日本の著作権法  
著作権法47条の７によって、著作者にモダンで記録や翻案をしても適法となっている。2018年の著作権法改正によって、学習データを第三者と共有したり、一般に販売したり、ネット上で公開するとことも、一定の条件下で適法となっている（改正著作権法30条4）

- オープン・イノベーション
- [AI・データの利用に関する契約ガイドライン](https://www.meti.go.jp/press/2018/06/20180615001/20180615001.html)
- データセットの偏り
- プライバシーリスクを低減するデータ加工
- 協調フィルタリング
- [FAT(Fairness, Accountability, and Transparency)](https://www.fatml.org/)
- 敵対的な攻撃
- 知的財産法
- GDPR

- アルゴリズムバイアス  
Google Photos がアフリカ系の女性に「ゴリラ」とラベル付をしてしまった事件

- インセンティブ設計
- クライシスマネージメント  
危機管理対応
- エスカレーション
- 透明性レポート
  - [Twitter](https://transparency.twitter.com/ja.html)
  - [Google](https://transparencyreport.google.com/?hl=ja)
  - [Facebook](https://transparency.facebook.com/)
- [PAI(Partnership on AI)](https://www.partnershiponai.org/)
- アシロマAI原則
- [AIネットワーク社会推進会議](https://www.soumu.go.jp/main_sosiki/kenkyu/ai_network/index.html)
- [人間中心のＡＩ社会原則検討会議](https://www8.cao.go.jp/cstp/tyousakai/humanai/index.html)


## 🏢 事例
- [BRETT: Deep-learning robot](https://engineering.berkeley.edu/brett/)
- [AlphaGo](https://ja.wikipedia.org/wiki/AlphaGo)
- [Google DeepMind's Deep Q-learning playing Atari](https://deepmind.com/research/publications/playing-atari-deep-reinforcement-learning)

## :tv: Youtube

### 松尾豊
- [人工知能の未来～ディープラーニングの先にあるもの](https://www.youtube.com/watch?v=7bvfl_M5vPQ)
- [人工知能は人間を超えるか ディープラーニングの先にあるもの](https://www.youtube.com/watch?v=lqywEafvq_Q)
- [【SoftBank World 2016】 人工知能は人間を超えるか](https://www.youtube.com/watch?v=7bvfl_M5vPQ)

### NDIVIA
- [ディープ・ラーニング最新技術情報 何故GPUはディープラーニングに向いているか](https://www.youtube.com/watch?v=1aHQ2tVVlj8)

# ml-study

機械学習をゼロから学ぶための学習リポジトリです。
コード(notebook)と学んだことのメモを、トピックごとのフォルダにまとめて管理します。

進捗は下のチェックリストで管理します。完了したら `- [ ]` を `- [x]` に変更してください。

---

## 📚 学習ロードマップ

### 1. Python基礎 (`01_python_basics/`)
- [ ] 文法基礎(変数, 条件分岐, ループ, 関数)
- [ ] リスト内包表記
- [ ] クラスとオブジェクト指向の基本
- [ ] 仮想環境(venv)の使い方

### 2. NumPy, Pandas, Matplotlib (`02_numpy_pandas/`)
- [ ] NumPy配列の基本操作
- [ ] Pandasでのデータ読み込み・前処理
- [ ] Matplotlib / Seabornでのグラフ作成
- [ ] 簡単なデータ分析(欠損値処理・集計など)

### 3. 数学基礎 (`03_math_basics/`)
- [ ] 線形代数(ベクトル・行列・行列積)
- [ ] 微分・偏微分・勾配
- [ ] 確率・統計の基本(期待値・分散・正規分布)
- [ ] 勾配降下法の仕組み

### 4. 古典的機械学習アルゴリズム (`04_ml_algorithms/`)
- [ ] 線形回帰 (`linear_regression/`)
- [ ] ロジスティック回帰 (`logistic_regression/`)
- [ ] 決定木 (`decision_tree/`)
- [ ] ランダムフォレスト
- [ ] k近傍法(k-NN)
- [ ] クラスタリング(k-means)
- [ ] Kaggle初心者コンペに挑戦

### 5. ディープラーニング (`05_deep_learning/`)
- [ ] ニューラルネット基礎(全結合層・逆伝播・活性化関数)
- [ ] CNN(画像認識の基礎)
- [ ] RNN / LSTM(系列データ)
- [ ] **Transformer**
  - [ ] Attention機構の直感的理解(Query, Key, Value)
  - [ ] Self-Attentionの数式を手計算してみる
  - [ ] "Attention Is All You Need" 論文を読む
  - [ ] PyTorchでミニTransformerをスクラッチ実装
  - [ ] Hugging Face `transformers` で事前学習済みモデル(BERT, GPTなど)を触る

---

## 📁 フォルダ構成

```
ml-study/
├── README.md
├── 01_python_basics/
├── 02_numpy_pandas/
├── 03_math_basics/
├── 04_ml_algorithms/
│   ├── linear_regression/
│   ├── logistic_regression/
│   └── decision_tree/
└── 05_deep_learning/
    ├── cnn/
    ├── rnn_lstm/
    └── transformer/
```

各トピックフォルダの中には、実験用の `.ipynb` ノートブックと、学んだことをまとめた `notes.md` を置いていきます。

---

## 🔗 参考教材

- Python基礎: Progate, paiza
- 数学: ヨビノリ(YouTube)、『ゼロから作るDeep Learning』
- 古典的ML: scikit-learn公式チュートリアル → Kaggle Learn
- 体系的に学びたい場合: Andrew Ng "Machine Learning Specialization"(Coursera)
- Transformer: "Attention Is All You Need"(原論文)、"The Annotated Transformer"(Harvard NLP)
# DataScience2023


<div dir='rtl'>
産業技術大学院大学</br>
担当: 岩政</br>
2023年4月5日～5月31日
</div>


「データサイエンス特論」(2023/1Q)の講義用公開リポジトリです

講義スライドはmanabaにて配布します。

## 講義概要

- 講義日時：
  - 水曜6限(18:30-20:00)、土曜3限(13:00-14:30)
- 講義形式
  - ハイフレックス式
- 計算機環境
  - Google Colaboratory を使います
- テスト
  - 毎回、簡単なミニテストを行います
  - 中間レポート３回
  - 最終レポート

## 講義日程と実習用の jupyter notebookの配布

この講義では、計算機実習を Google Colaboratory を使って行います。以下の**Open in Colab**ボタンを押すとColaboratoryの画面に遷移します。このページを残したい場合は、右クリックで「新しいタブで開く」と新しいタブで開くこともできます。

![](https://colab.research.google.com/assets/colab-badge.svg)


- 講義スライドは manabaで提供します。
- 参考図書：[データサイエンス教本、橋本・牧野](https://www.ohmsha.co.jp/book/9784274222900/)

|講義|日程|内容|Colabへのリンク|status|
|---|---|---|---|---|
|Lecture1|4/5(水) |はじめに||
|||Colaboratryのテスト| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture1.ipynb)|ok|
|||ColabによるAlpaca-LoRA| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture1_alpaca_lora.ipynb)|ok|
|Lecture2|4/8(土) |Python入門、統計の復習|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture2.ipynb)|ok|
|Lecture3|4/12(水) |Colabotryを使ったプロジェクト例、ビジネスにけるデータ分析|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture3.ipynb)|ok|
|Lecture4|4/15(土)|データの取得と操作|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture4.ipynb)|ok|
|||pandasの利用| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture4_pandas.ipynb)|ok|
|||実習| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture4_practice.ipynb)|ok|
|Lecture5|4/19(水)|データの可視化| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture5_matplotlib.ipynb) |in preparation|
|||実習(1.棒グラフ)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture5_extra_1.ipynb) |in preparation|
|||Extra(アンケート結果)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/aiit_query_process2023.ipynb) |in preparation|
|||ChatGPTでtitanic|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/pandas_agent_sample.ipynb) |ok|
|Lecture6|4/22(土)|統計分布の基礎 |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture6.ipynb)|ok|
|Lecture7|4/26(水)|回帰分析1|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture7.ipynb)|ok|
|||事例(Game)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture7_games.ipynb)|ok|
|Lecture8|5/6(土)|回帰分析2|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture8.ipynb)|ok|
|||重回帰分析（変数選択）|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture8_AIC.ipynb)|ok|
|||重回帰分析（交絡因子）|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture8_multiple_regression.ipynb)|ok|
|||重回帰分析（ダミー変数）|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture8_multi_reg_category.ipynb)|ok|
|Lecture9|5/10(水)|パターン認識1|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture9.ipynb)|ok|
|||SVMの例|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture9_SVM.ipynb)|ok|
|||SVMを最適化で解く|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture9_svm_optimize.ipynb)|ok|
|Lecture10|5/13(土)|パターン認識2||ok|
|||クラス分類|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture10_classification.ipynb)|ok|
|||クラスタリング|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture10_clustering.ipynb)|ok|
|Lecture11|5/17(水)|動的システムの表現|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture11.ipynb)|ok|
|Lecture12|5/20(土)|時系列|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture12.ipynb)|in progress|
|Lecture13|5/24(水)|状態空間モデル|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture13.ipynb)|ok|
|||周波数分析|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture13_frequency.ipynb)|ok|
|Lecture14|5/27(土)|画像分析|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lecture14.ipynb)|ok|
|Lecture15|5/31(水)|発展的話題とまとめ|
|||Transformer入門|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lec15_transformer_intro.ipynb)|ok|
|||テキスト生成|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lec15_transformer_textgeneration.ipynb)|ok|
|||Q&A|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/lec15_transformer_qanda.ipynb)|ok|
|||ChatGPTでtitanic|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/pandas_agent_sample.ipynb) |ok|
|予備|6/3(土)|


<!-- |Lecture3|4/13(水)|データの可視化| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture3_matplotlib.ipynb)|in_progress|
|Lecture4|4/16(土)|統計分布の基礎 |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture4.ipynb)|in_progress|
|Lecture5|4/20(水)|回帰分析1|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture5.ipynb)|in_progress|
|||重回帰分析|
|Lecture6|4/23(土)|回帰分析2|
|Lecture7|4/27(水)|パターン認識1|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture7.ipynb)|in_progress|
|||SVM|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture7_SVM.ipynb)|in_progress|
|Lecture8|4/30(土)|パターン認識2|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture8.ipynb)|in_progress| -->

## テスト
- ミニテスト：manabaで行います
- 中間レポート：manabaで行います
- 最終レポート：manabaで行います

## 連絡事項

- report1の例：[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/2023report1_sample.ipynb)

- report2の例：[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2023/blob/main/notebooks/2023report2_sample.ipynb)



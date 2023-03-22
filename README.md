# DataScience2022

<div dir='rtl'>
産業技術大学院大学</br>
担当: 岩政、大久保</br>
2022年4月6日～6月2日
</div>


「データサイエンス特論」(2022/1Q)の講義用公開リポジトリです

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
|Lecture1|4/6(水) |はじめに||
|||Colaboratryのテスト| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture1.ipynb)|ok|
|||Pythonの基本| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture1_pythonbasics.ipynb)|ok|
|Lecture2|4/9(土)|データの取得と操作| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture2.ipynb)|ok|
|||pandasの利用| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture2_pandas.ipynb)|ok|
|||実習| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture2_practice.ipynb)|ok|
|Lecture3|4/13(水)|データの可視化| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture3_matplotlib.ipynb) |ok|
|||実習(1.棒グラフ)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture3_extra_1.ipynb) |ok|
|||Extra(アンケート結果)| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/aiit_query_process.ipynb) |ok|
|Lecture4|4/16(土)|統計分布の基礎 |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture4.ipynb)|ok|
|Lecture5|4/20(水)|回帰分析1|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture5.ipynb)|ok|
|||事例(Game)|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture5_games.ipynb)|ok|
|Lecture6|4/23(土)|回帰分析2|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture6.ipynb)|in_progress|
|||重回帰分析（変数選択）|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture6_AIC.ipynb)|in_progress|
|||重回帰分析（交絡因子）|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture6_multiple_regression.ipynb)|ok|
|||重回帰分析（ダミー変数）|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture6_multi_reg_category.ipynb)|ok|
|Lecture7|4/27(水)|パターン認識1|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture7.ipynb)|ok|
|||SVMの例|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture7_SVM.ipynb)|ok|
|||SVMを最適化で解く|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture7_svm_optimize.ipynb)|ok|
|Lecture8|4/30(土)|パターン認識2||ok|
|||クラス分類|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture8_classification.ipynb)|ok|
|||クラスタリング|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture8_clustering.ipynb)|ok|
|Lecture9|5/7(水)|動的システムの表現|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture9.ipynb)|ok|
|Lecture10|5/11(土)|時系列|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture10.ipynb)|in progress|
|Lecture11|5/14(水)|状態空間モデル|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture11.ipynb)|ok|
|||周波数分析|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture11_frequency.ipynb)|ok|
|Lecture12|5/18(土)|画像分析|[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/miwamasa/DataScience2022/blob/main/notebooks/lecture12.ipynb)|ok|
|Lecture13|5/21(水)|メディア情報処理（大久保先生）|
|Lecture14|5/25(土)|位置情報処理（大久保先生）|
|Lecture15|5/28(水)|センサデータ処理（大久保先生）|
|予備|6/2(土)|


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



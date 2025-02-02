# Pythonセミナー練習問題

## 概要

7/25,26に実施したPythonセミナーの練習問題です。
中にある`example.py`の内容を確認し、必要なコードを入れてみてください。

ただし、このコードは未実装でも起動することができます。
起動すると、`trib()`に記載された説明に基づき、実装が行われているかのテストを行います。

これは`doctest`という機能を使っています。
内容を読むとわかると思いますので、皆さんも是非自分でコードを書くときの参考にしてください。

## 問題1

コード中で記述されている `trib()` を実装してください。
実装が正しければテストコードを通過できます。

## 問題2

単純に実装すると、`trib()`は計算量が多くなり、時間がかかりすぎてしまいます。
各計算で1秒を超えた場合、自動的に計算を中断してしまいます。最後(`trib(99)`)まで計算できるようにしてみましょう。

この問題を解決するために、コードに手を加えてみてください。

ヒント:

* メモ化を考えてみましょう
* ループに置き換えることができるかもしれないのでそれを使うのも手です

JLOG (cpp-json-logger)
======================

アルゴリズムの実験を C++ で行う際に，結果や過程の情報の保存，および集計やグラフ描画を手際よく行うためのライブラリです．

こういった処理は，場合によってはアルゴリズムの実装よりも面倒で，本質的でない部分でソースコードも間延びし，とてもストレスが貯まります．このライブラリは，そういった苦痛を避けるために，簡単な記述を加えるだけでプログラム内のデータを自動で json にまとめることのできるライブラリです．出力は json なのでスクリプト言語を用いて簡単に処理できます．


使い方
-----

* C++ での記述は jlog_sample.cc を見れば分かると思います．
* 実行すると，jlog ディレクトリに json が保存されます．


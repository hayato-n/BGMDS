# BGMDS (Bayesian Geographical Multi-Dimensional Scaling)

BGMDS（地理的ベイズ多次元尺度構成法）は，MDS（多次元尺度構成法）のバリエーションで，地理的な地図に近い投影を構成します．手法の背景や技術的な詳細は下記論文を参照してください．

BGMDS is a variation of MDS (Multi-Dimensional Scaling). This method makes MDS projection to be similar to the original geographical map. It will be useful if you want to visualize some similarities of distances as maps (such as time-distance map) and compare it to the geographical map.

## How to use

Jupyter Notebookにソースコードと例が含まれています．２つのクラス`AdamOptimizer`と`BGMDS`が実行時に必要です．自分の問題に使う場合はcloneするか，notebookのソースコードをコピペしてください．最適化オプションの設定方法については，論文を参考にしてください．

The Jupyter Notebook contains the source codes and example. When you run BGMDS, you need 2 classes, "AdamOptimizer" and "BGMDS". If you use this method for your data, copy these classes and paste your codes.

## Publication
- [西 颯人, 浅見 泰司, 地理的制約条件に基づく統計的多次元尺度構成法, 都市計画論文集, 2019, 54 巻, 3 号, p. 826-832](https://doi.org/10.11361/journalcpij.54.826)

- [Hayato Nishi and Yasushi Asami, *Bayesian Geographical Multi-Dimensional Scaling*, Abstract on International Cartographic Conference, Tokyo (2019)](http://home.hol.is.uec.ac.jp/icc2019papers/all/756.pdf)

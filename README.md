# m1-reserch
M1の研究で構築したプログラムのアウトプット

## Inverse_Analysis.ipynb
KerasのSequentialモデルで2入力1出力のネットワークを構築し、所望の目的変数yを設定した際に、それを実現するための説明変数xを学習済みモデルと勾配降下法を用いて探索（逆解析）するノートブック。

## MOPSO.ipynb
Inverse_Analysis.ipynbのやり方では1出力に対する逆解析しか実現できない。そこで、複数の出力であっても可能な限り良いパラメータを探索（逆解析）できる粒子群最適化（MOPSO）を実装した。ネットワークはKerasのFunctional APIで2入力2出力の深層学習モデルを構築している。

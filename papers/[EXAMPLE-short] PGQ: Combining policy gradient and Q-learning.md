# PGQ: Combining policy gradient and Q-learning

<img src='../tmb/PGQ: Combining policy gradient and Q-learning.png' width=750px />

- 論文リンク: https://arxiv.org/abs/1611.01626
- 出版年: 2017
<!-- - ジャーナル・カンファレンス: -->
<!-- - 著者: -->
<!-- - 所属: -->
<!--
- 関連リンク:
  -
-->
<!--
- タグ:
  - 
-->

## まとめ

#### 概要
エントロピー正則化付きの方策勾配法とQ学習を組み合わせた新しいアルゴリズムPGQを提案し、DQNやA3Cに対する優位性をAtariドメインで実験的に示した。
Atariの50以上のゲームにおいて、DQNとA3Cと比較したとき3アルゴリズム中PGQが最下位になったのは1つのゲームだけという高い性能を示した。

<!-- #### 目的 -->

<!-- #### 貢献（新規性・差分） -->

<!-- #### 手法 -->

<!-- #### 結果 -->

<!-- ##### 1. Atariドメインでの評価 -->

<!-- #### 定理・証明していること（汎用的で重要なものであれば） -->

<!-- ## 次に読むべき論文 -->

## コメント

#### @sotetsuk: 8/10
- 方策勾配法はナイーブな定式化では探索をすることができずに方策が決定論的になりがちだが、探索を促すエントロピー正則化を使った方策勾配法がある意味でより自然な定式化かもしれない、という示唆とも捉えることができて面白い。
- Eq.4からπとVだけを使って（妥当な）Qを計算しているのがPGQのポイントだと思った。

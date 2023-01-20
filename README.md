# 研究のプログラム

## 概要

最適な練習スケジュールをつくりたい。
フィットネス疲労理論をもとに研究中

## 方法
pythonを使ってとりあえず実験

## 実験
1. jogのみ
2. ペース走導入
3. スピード練習を導入
4. 休みを導入
5. 休みを増やした
6. 途中から練習しなくなる
7. 2022年9月の練習データより実験
8. jogと休みだけのメニューのシミュレーション(10日間)
9. 強度だけでなく距離も変数化してみたシミュレーション(コードが違う)
10. ペース走追加のシミュレーション(3パターン)
11. 全てのメニュー
12. 調子がいい日悪い日のシミュレーション(パフォーマンスが度の値以下だと基本的にポイント練習がきつくなるのか)

## 結果について

画像ファイルを参照。

## 最適化問題へ(進捗)

結果を実施したところピーキングがあっていたことが分かった。
現在は論文を作成中である。
最適化問題を解く上でソルバーはどこまで解を導き出してくれるのか
というところは今後の課題に挙げられる。

## 制約式について
制約式はパフォーマンスの下限にする。
simulationの結果13日の時点のパフォーマンスで-100を下回った場合
練習をこなせていない。練習をこなせた日は-97とかで-100を下回らなかった。
制約をとりあえず1次関数の式にうまくしてやって実験して研究を終わろうと思う。

## testフォルダについて
gurobiが動くかどうかを検証するフォルダになっている。
ネットから適当にサンプルコードを引っ張ってきた。
anacondaプロンプトにて正常に動いた。

## 研究関連のリポジトリ
[最適化問題を解く](https://github.com/teru12012000/python_gurobi)


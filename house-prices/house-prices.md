house price code review

1. データの読み込み
2. データの中身を確認，空データの数を各列で算出
3. GrLivAreaとSalePriceの相関を散布図で確認
4. SalePriceの棒グラフ図と箱ひげ図を確認する．
5. 外れ値を除去する．
6. サンプル数を確認する．
7. 各列におけるサンプルの空の割合を求める．0%=空データなし．100%=すべて空．
8. 各列におけるサンプルの空の割合を図として可視化する
9. 空データがある列に対して，空を埋める処理をおこなう．
10. 空データを多く含む列については，全削除．
11. 空データは中央値・最頻値で埋める．
　　中央値→型がint, float　最頻値→型がobject（文字）







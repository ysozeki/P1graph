# P1graph
# P1課題補足資料のRC回路のグラフ例
### 2020/5/5 小関泰之

- P1課題補足資料に従い、LTspiceを用いてLPFの周波数特性とステップ応答を計算したら、理論曲線と比較してみましょう。
- グラフ化のソフトとしてはMATLAB, Excel, gnuplot, sma4winなど様々なものがありますが、ここでは、Python + matplotlib + Jupyter Notebookを使ってグラフ化を行った例を示します。
- Python 3, numpy, pandas, matplotlib, Jupyter Notebookはpip3でインストールできます。
- 動作確認はmacOS10.15.4, Python 3.7, pandas 1.0.3, numpy 1.18.2, matplotlib 3.2.1, Jupyter Notebook 6.0.1で行いました。
- 補足資料で計算する時定数0.1 ms (カットオフ周波数1.6 kHz)のLPFで得られるデータを表示することを前提としています。
 - 周波数特性データ名は 01_lpf_freq.txt としています。周波数範囲は10 Hz ~ 10 kHzです。
 - ステップ応答データ名は 02_lpf_step.txt としています。波形の時間範囲は0 ms ~ 2 msで、時間1 msから立ち上がります。
- DPI (dots per inch)を300に設定しています。
- 画像をPNGファイルで保存しています。WordやLaTeXに貼り付けることができます。
- Shift + Enterで１ブロックずつ実行することができます。

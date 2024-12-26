The following is written in Japanese:

x.mdlファイルは、Ventana Systems社Vensim用SDモデルファイルである。無償ソフトウェアのVensim PLEを利用した実行が可能。モデル内の変数と定数名は日本語で表記されている。

時系列データを読込み、誤差評価出力を行うためには、有償ソフトウェアのVensim Profesional、あるいはVensim DSSの利用が必要となる。

感度分析を行うためには、、有償ソフトウェアのVensim Profesional、あるいはVensim DSSの利用が必要となる。

Vensimは、Version10以降、モデルの表記法を独自形式に変更した。従来のシステム・ダイナミクスの表記法に変更してモデルを表示するためには、以下の指定を行う。

［ビュー］アイコン→「伝統的なスケッチスタイル」を選択する。
#
定常モデルによる近似  -> CJ_Stationary_j.mdl

逓増モデルによる近似 ->  CJ_Increment_j.mdl

定常モデルによる予測 -> CJ_Stationary_Predict_j.mdl

逓増モデルによる予測 -> CJ_Increment_Predict_j.mdl

定常モデルによる感度分析 -> CJ_Stationary_Sens_j.mdl

逓増モデルによる感度分析 -> CJ_Increment_Sens_j.mdl


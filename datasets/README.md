# datasets

ノートで使うデータや計算済みデータを保存しています。
レポジトリのサイズを削減するため一部圧縮して保存しています。

## sevir

このチュートリアルが使うデータ。SEVIR データセットを加工して作成したもの。
ファイルサイズが大きいので tar.gz2 圧縮して登録している。

## sklearnmodesls

ノート8の学習済みモデルをシリアライズして永続化したもの。
ノート8、9で学習済みモデルを使用する際に時間のかかる計算をスキップしたい場合に読み込む。

複数特徴量の回帰問題の学習モデルはランダムフォレストモデルのサイズが圧縮しても100MBバイトを超えているのでレポジトリには登録していない。

## explanations

ノート9の計算結果を保存したもの。
時間のかかる計算をスキップしたい場合に読み込む。

## explanations

ノート10の計算結果を保存したもの。
時間のかかる計算をスキップしたい場合に読み込む。

## Reference

- Chase, R. J., D. R. Harrison, A. Burke, G. M. Lackmann, and A. McGovern, 2022: A Machine Learning Tutorial for Operational Meteorology. Part I: Traditional Machine Learning. 
    Wea. Forecasting, 37, 1509–1529, https://doi.org/10.1175/WAF-D-22-0070.1.
- Veillette, M., S. Samsi, and C. Mattioli, 2020: Sevir : A storm event imagery dataset for deep learning applications in radar and satellite meteorology. 
  Advances in Neural Information Processing Systems, H. Larochelle, M. Ranzato, R. Hadsell, M. F. Balcan, and H. Lin, Eds., 
  Curran Associates, Inc., Vol. 33, 22 009–22 019, 
  URL [https://proceedings.neurips.cc/paper/2020/file/fa78a16157fed00d7a80515818432169-Paper.pdf]

# state-space-sim

ブラウザで動作する状態空間シミュレータです。

[state-space simulator(2d)](https://KakeruHashimoto.github.io/state-space-sim/src/index.html)

初期値や入力を与えたときの状態の振る舞いをリアルタイムで確認できます。

A行列、B行列、初期状態を入力し、"Apply parameter"ボタンを押すと適用されます（なお、デフォルトのモデルは $u(t), x_1(t), x_2(t)$をそれぞれ力、位置、速度とした1自由度バネマスダンパ系を想定したモデルになっています）。


## 動作環境

以下のブラウザで動作することを確認しています。

- Google Chrome 108.0.5359.125
- Microsoft Edge 108.0.1462.54

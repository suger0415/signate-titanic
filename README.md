# SIGNATE 練習問題：タイタニックの生存予測

## 概要
タイタニック号の乗客の情報から，生存したか否かを予測するモデルを作成する．

## 手法
- 欠損値処理：age→中央値，embarked→最頻値で補完
- 特徴量：pclass，sex，age，sibsp，parch，fare，embarked（ダミー変数化）
- モデル：RandomForestClassifier

## 結果
- Public AUC: 0.862



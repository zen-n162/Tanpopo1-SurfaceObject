# Tanpopo1-SurfaceObject

## 1. たんぽぽ1計画とは
- 国際ステーション上で行われている日本初のアストロバイオロジー実験
- エアロゲル（低密度ガラスの捕獲材）を用いて**宇宙塵**(micrometeoroid)などを捕集する。
　→ その物質を地上で分析する
  - **宇宙塵**(宇宙由来の有機物含有物質)
  - 地球由来の微粒子(地球由来の微生物含有物質)
  - スペースデブリ(人工物)
- 当初の目的ではないが、補修されたもの
  - 表面付着物(エアロゲル表面に付着するごみ)

## 2. 表面付着物の分類
Sputter, Block, Fiber, Bar, A/G fragmentの5種類に今の段階で分類される。
- 5クラス分類においてのアーキテクチャの比較 ([発表資料](https://docs.google.com/presentation/d/1rqKcDY-ZD6nMXzUVyrAmeh15f6_feJYe8amlotuNuPM/edit?usp=sharing))
  - VGG16
  - VGG16 + BatchNormalization
  - Vision Transformer
 
### 結果 Results
#### 交差検証（Cross Validation）
- VGG16: 平均 93.9　標準偏差 0.1166
- VGG16 + BatchNormalization: 平均 100.0　標準偏差 0.0000
- ViT: 平均 99.6　標準偏差 0.0067
- EfficientNet: 平均 88.2　標準偏差 3.9573

![テスト結果](CrossValidation/20230206TanpopoML_test1.pdf)

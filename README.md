# UE4-Shaders
UE4にて利用できるシェーダー用マテリアル

# 移行手順
1. ローカルにクローン
1. .uprojectファイルを開く
1. 使いたいプロジェクトに移行
    2. Content/Shadersで右クリック
    2. migrate(移行)で使用したいプロジェクトに移行

# 使用方法
- 末尾に"_S"とつくもの
  - Surfaceタイプのマテリアル
  - メッシュに割り当てて使用
  
- 末尾に"_PP"とつくもの
  - ポストプロセスマテリアル
  - Post Proccess Volume等に適用して使用
  
# 内容一覧(アルファベット順)
- 色収差シェーダー(ChromaticAberration)

- Glitchシェーダー(Glitch)

- Lambertシェーダー(Lambert)

- モノクロセルシェーダー(MonoCel)

- モザイクシェーダー(Mosaic)

- 砂嵐シェーダー(Noise_01)

- アウトラインシェーダー(Outline)

# UE4-Shaders
UE4にて利用できるシェーダー用マテリアル

# 移行手順
1. ローカルにクローン
2. .uprojectファイルを開く
3. 使いたいプロジェクトに移行  
    1. Content/Shadersで右クリック  
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
    [色収差シェーダー - YouTube](https://www.youtube.com/watch?v=xOERpR87FHo)  
    ![05_ChromaticAberration](https://user-images.githubusercontent.com/39930174/206061894-5b55c089-119c-463a-9b9f-270d0474fa12.png)

- Glitchシェーダー(Glitch)

- Lambertシェーダー(Lambert)  
    ![00_Lambert](https://user-images.githubusercontent.com/39930174/206061507-d29f6a19-40e0-4b56-ab03-beb8b88a27f8.png)

- モノクロセルシェーダー(MonoCel  
    ![01_Cel](https://user-images.githubusercontent.com/39930174/206061698-f848c66d-be13-4bfa-a7c5-6a5fa260128d.png)

- モザイクシェーダー(Mosaic)  
    ![06_PixelMosaic](https://user-images.githubusercontent.com/39930174/206061767-b4c97d14-1254-45f6-b73b-1aa6cc85ae64.png)

- 砂嵐シェーダー(Noise_01)  
    ![02_Noise](https://user-images.githubusercontent.com/39930174/206061848-12bbef75-2dbb-4cff-bc2d-e7ec7c978ee2.png)

- アウトラインシェーダー(Outline)  
    ![07_Outline](https://user-images.githubusercontent.com/39930174/206061860-5273377d-89c5-403d-b463-105a75bde7ff.png)

- スキャンエフェクトシェーダー(Scan)

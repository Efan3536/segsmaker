# Sagemaker Studio Lab用のStable Diffusion WebuiとComfyUIノートブック | **[English](README.md)** 
チェックポイント、LoRA、ControlNETモデル用の一時フォルダーと共に [<img align="right" src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fpantat88%2Fsegsmaker&label=Visitors&countColor=%232ccce4&style=flat">](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fpantat88%2Fsegsmaker)
<br />[<img align="right" src="https://img.shields.io/badge/Support%20me%20on%20Ko--fi-F16061?logo=ko-fi&logoColor=white&style=flat">](https://ko-fi.com/gutris1)

| SD 1.5 | [![Open in Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/gutris1/segsmaker/blob/main/Segsmaker.ipynb) |
| :---------------------------------------- | :-----------------------------------------------------------------------------------------------------------------: |
| SD Webui Forge | [![Open in Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/gutris1/segsmaker/blob/main/Segsmaker_Forge.ipynb) |
| SD 1.5 AnimateDiff | [![Open in Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/gutris1/segsmaker/blob/main/Segsmaker_AnimateDiff_SD1.5.ipynb) |
| SDXL | [![Open in Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/gutris1/segsmaker/blob/main/Segsmaker_SDXL.ipynb) |
| ComfyUI AnimateDiff Evolved | [![Open in Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/gutris1/segsmaker/blob/main/Segsmaker_ComfyUI.ipynb) |<br />

こちらで私を見つけることができます https://discord.gg/k5BwmmvJJU

# 変更履歴
### 2024-03-02
- [SD Webui Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge)のノートブックを追加
- A1111 SD Webuiを1.8.0に更新
- Condaスクリプトを更新して、Torch 2.1.2+cu121をインストール

### 2024-02-09
- civitai.comのダウンロードにaria2に切り替えました。
- Google Driveのダウンロードにgdownを追加しました。Google Driveのファイルまたはフォルダーについては、公開URLを直接貼り付けるだけです。
- それ以外の場合はCurlをデフォルトとします。

使用方法：
```python
# URLのみ
%download URL

# URLとファイル名
%download URL 123456.safetensors

# URLとパス
%download URL ~/asd/models/asdasd

# URL、パス、ファイル名
%download URL ~/asd/models/zzzzzz 789789.txt
```

### 2024-02-07
- 私たち全員、特に私のアカウントの安全のため、これからはCondaセルを再実行して自分のAPIキーを入力してください。 <br />
  <img src="https://github.com/gutris1/segsmaker/assets/132797949/7420b6ff-7080-46f2-bd20-cd2088d64ff6" width="486" height="169">
- 自分のAPIキーは https://civitai.com/user/account にアクセスし、「APIキーを追加」ボタンをクリックして名前を付け、その後コピーしてください。<br />
  <img src="https://github.com/gutris1/segsmaker/assets/132797949/d3fa05b6-4cdd-4ffc-9a50-43bf550de627" width="367" height="169">
- 心配しないでください、これは一度だけの作業です。次にCondaを再インストールする際には、再度プロンプトが表示されることはありません。

# プレビュー
<p align="center">
  <img src="https://github.com/gutris1/segsmaker/blob/4839cf9b51036d95671d5e74d49bd5fa86d0552b/preview1.gif">
  <img src="https://github.com/gutris1/sd-fast-pnginfo/blob/e59a97f28d20397da5b78bdd6a8a79299cf139f1/preview.gif">
  <img src="https://github.com/gutris1/segsmaker/assets/132797949/acc8e533-2a71-4be9-b8ce-d0dd992f9970">
</p>

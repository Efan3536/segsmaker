# Stable Diffusion Webui and ComfyUI notebook for Sagemaker Studio Lab | **[日本語で](README-JP.md)**
with temporary folder for Checkpoint, LoRA and ControlNET models [<img align="right" src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fpantat88%2Fsegsmaker&label=Visitors&countColor=%232ccce4&style=flat">](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fpantat88%2Fsegsmaker)<br />[<img align="right" src="https://img.shields.io/badge/Support%20me%20on%20Ko--fi-F16061?logo=ko-fi&logoColor=white&style=flat">](https://ko-fi.com/gutris1)

| SD 1.5 | [![Open in Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/gutris1/segsmaker/blob/main/Segsmaker.ipynb) |
| :---------------------------------------- | :-----------------------------------------------------------------------------------------------------------------: |
| SD Webui Forge | [![Open in Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/gutris1/segsmaker/blob/main/Segsmaker_Forge.ipynb) |
| SD 1.5 AnimateDiff | [![Open in Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/gutris1/segsmaker/blob/main/Segsmaker_AnimateDiff_SD1.5.ipynb) |
| SDXL | [![Open in Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/gutris1/segsmaker/blob/main/Segsmaker_SDXL.ipynb) |
| ComfyUI AnimateDiff Evolved | [![Open in Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/gutris1/segsmaker/blob/main/Segsmaker_ComfyUI.ipynb) |<br />

you can find me here https://discord.gg/k5BwmmvJJU

# Changelog
### 2024-03-02
- add notebook for [SD Webui Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge)
- update A1111 SD Webui to 1.8.0
- update Conda script to install Torch 2.1.2+cu121

### 2024-02-09
- Switch to aria2 for civitai.com downloads.
- Add gdown for Google Drive downloads. For Google Drive file or folder, simply paste the public URL directly.
- Else default to Curl.

Usage:
```python
# only url
%download URL

# url and filename
%download URL 123456.safetensors

# url and path
%download URL ~/asd/models/asdasd

# url path and filename
%download URL ~/asd/models/zzzzzz 789789.txt
```

### 2024-02-07
- For the safety of all of us, especially my account, from now on please enter your own API key by rerunning the Conda cell. <br />
  <img src="https://github.com/gutris1/segsmaker/assets/132797949/7420b6ff-7080-46f2-bd20-cd2088d64ff6" width="486" height="169">
- Get your own API key at https://civitai.com/user/account click the 'Add API Key' button, give it a name and then copy. <br />
  <img src="https://github.com/gutris1/segsmaker/assets/132797949/d3fa05b6-4cdd-4ffc-9a50-43bf550de627" width="367" height="169">
- Don't worry, you only need to do that once. next time you reinstall Conda, you will not be prompted again.

# Preview
<p align="center">
  <img src="https://github.com/gutris1/segsmaker/blob/4839cf9b51036d95671d5e74d49bd5fa86d0552b/preview1.gif">
  <img src="https://github.com/gutris1/sd-fast-pnginfo/blob/e59a97f28d20397da5b78bdd6a8a79299cf139f1/preview.gif">
  <img src="https://github.com/gutris1/segsmaker/assets/132797949/acc8e533-2a71-4be9-b8ce-d0dd992f9970">
</p>

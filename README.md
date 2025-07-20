# Readme

## 环境搭建
```bash
conda create -n peft python=3.11

# 激活环境
conda activate peft

pip install ipykernel
# pip install ipykernel --force-reinstall
python -m ipykernel install --user --name peft --display-name "Python (peft)"

pip install nbformat  # 才可以使用%run xx

pip install ipywidgets

pip install -r requirements.txt -i https://mirrors.aliyun.com/pypi/simple/

pip install autoawq
pip install huggingface_hub[hf_xet] -i https://mirrors.aliyun.com/pypi/simple/
```

下载windows版本的ffmpeg
https://www.gyan.dev/ffmpeg/builds/

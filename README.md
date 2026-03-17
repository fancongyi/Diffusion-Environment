
```
conda create -n fcy_video python=3.10 -y
conda activate fcy_video

# CUDA 12.4
pip install torch==2.6.0 torchvision==0.21.0 torchaudio==2.6.0 --index-url https://download.pytorch.org/whl/cu124
pip install https://github.com/Dao-AILab/flash-attention/releases/download/v2.7.4.post1/flash_attn-2.7.4.post1+cu12torch2.5cxx11abiFALSE-cp310-cp310-linux_x86_64.whl && python -c "import flash_attn"
pip install "xfuser[diffusers,flash-attn]"
pip install -r requirements.txt
```


conda create -n hallo python=3.10
conda activate hallo
pip install torch==2.2.2 torchvision==0.17.2 torchaudio==2.2.2 --index-url https://pypi.tuna.tsinghua.edu.cn/simple
pip install -r requirements.txt

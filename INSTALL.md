```bash
conda create -n sfd2 python=3.8 -y
conda activate sfd2
pip install torch==1.10.1+cu111 torchvision==0.11.2+cu111 torchaudio==0.10.1 -f https://download.pytorch.org/whl/cu111/torch_stable.html
pip install -r requirements.txt
```

Prepare Data

```bash
wget -r https://data.ciirc.cvut.cz/public/projects/2020VisualLocalization/Aachen-Day-Night/
wget -r https://data.ciirc.cvut.cz/public/projects/2020VisualLocalization/Extended-CMU-Seasons/
wget -r https://data.ciirc.cvut.cz/public/projects/2020VisualLocalization/RobotCar-Seasons/
```
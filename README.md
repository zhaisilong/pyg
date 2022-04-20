# pyg

## Installation

```shell
# create conda env
conda create -npyg python=3.8
conda activate pyg
# install pytorch
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch -y
# check for pytroch
python -c "import torch; print(torch.__version__)"
python -c "import torch; print(torch.version.cuda)"
# install pyg
conda install pyg -c pyg
# insstall extra packages
conda install jupyter
```

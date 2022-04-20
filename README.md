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
# install extra packages
conda install jupyter matplotlib
pip install -r requirements.txt -i"https://pypi.tuna.tsinghua.edu.cn/simple/"
```

## Links

- [pyg 深度学习实现库](https://github.com/benedekrozemberczki/pytorch_geometric_temporal)
- [PYG DOCS](https://pytorch-geometric.readthedocs.io)
- [Stanford University: A collection of graph machine learning tutorial blog posts, fully realized with PyG](https://medium.com/stanford-cs224w/featured/home)
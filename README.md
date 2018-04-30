# MyResearch
[StyleNet](http://hi.cs.waseda.ac.jp/~esimo/publications/SimoSerraCVPR2016.pdf)の手法を改良し，WEBで収集できるweakly-labeledな画像を利用したCNNの新しい学習法について提案する。

# Codes
- `train.py`: train the model on CPU.
- `load_model.py`: load the model
- `image_sampling.py`: code related to image sampling.
- `stylenet.t7`: StyleNet model which should be converted to PyTorch model.
- `convert_torch.py`: convert Torch7 model to PyTorch.

# Experimental Result
## Classification Task
Comparison of **StyleNet Ranking**(minimizing triplet loss) and **Ours Ranking**.

accuracy
StyleNet Ranking: 74.6%
Ours Ranking: 75.1%
## Predicting Fashionability
実験実装中

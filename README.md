# MyResearch
We propose new method for learning weakly-labeled data based on the [StyleNet](http://hi.cs.waseda.ac.jp/~esimo/publications/SimoSerraCVPR2016.pdf) architecture.

# Codes
- `train.py`: train the model on CPU.
- `load_model.py`: load the model
- `image_sampling.py`: code related to image sampling.
- `stylenet.t7`: StyleNet model which should be converted to PyTorch model.
- `convert_torch.py`: convert Torch7 model to PyTorch.

# Experimental Result
## Classification Task
We evaluate our model by classification task on Hipster Wars dataset which includes 5 class and 1900 images.

### Accuracy Result
- StyleNet Joint:       74.93 ± 0.45% (We're unable to reproduce the result of 75.9% in the paper)
- Ours Ranking(>0.83):  75.30 ± 0.46%
- Ours Ranking(>0.89):  76.14 ± 0.47%

![result](https://i.imgur.com/c4CU2wV.png)

## Predicting Fashionability
実験実装中

![](https://pbs.twimg.com/media/DqAN0T2U8AAvS0Y.jpg)

slide from [Rachal's TEDx](https://www.youtube.com/watch?v=LqjP7O9SxOM).

# All about mnist

## Contents

* [Project Overview](#project-overview)


* [Data](#data)
    * [MNIST](#mnist)
* [Algorithms](#algorithms)
	* [Architecture](#architecture)

## Project Overview

## Data

### MNIST


- Using MNIST dataset, which is bacis to machine learning, you can learn the core concepts of NLP and Computer vision.
- Generated arithmetic equations which has random length, [code](https://github.com/you-just-want-attention/image-captioning/blob/master/utils/dataset.py)
    * SerializationDataset: Arrange the data
    * CalculationDataset: Automatically make operations
    * ClassificationDataset: Making data lable, which is result of arithmetic
- if you want to use jupyter notebook and test it, click [code](https://github.com/you-just-want-attention/image-captioning/blob/master/scripts/mnist-data-calculation-pipeline.ipynb)


![](/assets/equation1.png)
![](/assets/equation2.png)
![](/assets/equation3.png)
![](/assets/equation4.png)

## Algorithms

### Architecture

sequence to sequence model (Enncoder-Decoder)
- Seq2seq model, *pytorch* [code](https://github.com/you-just-want-attention/image-captioning/blob/master/scripts/calculation/seq_2_seq_model_torch.ipynb)

![](/assets/seq2seq.jpeg)

- Seq2seq with attention, *pytorch* [code](https://github.com/you-just-want-attention/image-captioning/blob/master/scripts/calculation/seq_2_seq_model_attention_torch.ipynb)
- VGG classification model, *tensorflow* [code](https://github.com/you-just-want-attention/image-captioning/blob/master/tf_models/classification/models.py)


## Reference

Language modeling paper/article which is applied in these project
- [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/pdf/1409.0473.pdf)
- [Attenion? Attention!](https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html)

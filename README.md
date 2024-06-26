# 第二次作业-文本情感分类

THU 2024春 人工智能导论

## 数据位置

`./Dataset` 目录下应该有 `test.txt`、`train.txt` 、`validation.txt`、`wiki_word2vec_50.bin`，代码才可以正常运行。

## 代码

CNN 模型的代码在 `./cnn.ipynb`。

RNN 模型的代码在 `./rnn.ipynb`。

MLP 模型的代码在 `./mlp.ipynb`。

## 模型

CNN 模型在 `./cnn_sentiment_model.pth`

RNN 模型在 `./rnn_sentiment_model.pth`

MLP 模型在 `./mlp_sentiment_model.pth`

## 最终目录结构

```
.
├── Dataset
│   ├── test.txt
│   ├── train.txt
│   ├── validation.txt
│   └── wiki_word2vec_50.bin
├── README.md
├── cnn.ipynb
├── cnn_sentiment_model.pth
├── learn.ipynb
├── mlp.ipynb
├── mlp_sentiment_model.pth
├── requirements.txt
├── rnn.ipynb
└── rnn_sentiment_model.pth

1 directory, 13 files
```
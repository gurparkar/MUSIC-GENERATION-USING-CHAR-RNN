# char-rnn-keras

Multi-layer recurrent neural networks for training and sampling from texts, inspired by [karpathy/char-rnn](https://github.com/karpathy/char-rnn).

### Requirements

This code is written in Python 3, and it requires the [Keras](https://keras.io) deep learning library.

### Usage

All input data should be placed in the `data/` directory. The example `input.txt` is taken from the [Nottingham Dataset (Cleaned)](https://github.com/jukedeck/nottingham-dataset).

To train the model with default settings:
```bash
$ python train.py
```

To sample the model:
```bash
$ python sample.py 300 



depending upon i you have gpu write python sample,py 300 for greater accuracy or else write python sample.py 100 and you can also increse your dat if you decent Ram in your pc more than 8 gb 
```

Training loss/accuracy is stored in `logs/training_log.csv`.

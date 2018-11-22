# char-rnn-keras

Multi-layer recurrent neural networks for training and sampling from texts, inspired by [karpathy/char-rnn](https://github.com/karpathy/char-rnn) and you can also study the blogs of karpathy for concept clearance from
http://karpathy.github.io/2015/05/21/rnn-effectiveness/. It is a very nice blog to clear your concept and dive 
into the practicality of the concepts.

### Requirements

This code is written in Python 3, and it requires the [Keras](https://keras.io) deep learning library.

### Usage

All input data should be placed in the `data/` directory. The example `input.txt` is taken from the [Nottingham Dataset (Cleaned)](https://github.com/jukedeck/nottingham-dataset).(it will be in midi format).My dataset is of Jigs (340 tunes) 
first go to the directory in the command prompt where you have stored this all files by using cd "address" in windows and then write all the below command 

To train the model with default settings:
```bash
$ python train.py
```

To sample the model:
```bash
$ python sample.py 300 
 
1.you have to copy solution generated command prompt after paste it on https://abcjs.net/abcjs-editor.html and you can download the file 
 in midi format also
 



depending upon i you have gpu write python sample.py 300 for greater accuracy or else write python sample.py 100 and you can also increse your dat if you decent Ram in your pc more than 8 gb 
```

Training loss/accuracy is stored in `logs/training_log.csv`.

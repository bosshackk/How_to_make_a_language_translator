# Language_translator By Rawal Kumar, Ravi Kumar, Bhavesh Srivas and Dheeraj Kumar.
This is the code for "Language Translator"

Language translator using a deep learning architecture in Tensorflow. It uses Neural Machine Translation specifically. This exercise helps appreciate the full power of statistical translation techniques.


## Dependencies

* tensorflow
* nltk 
* six


## Usage

To train model on data and test it to compute the [BLEU score](https://en.wikipedia.org/wiki/BLEU) run this:

``python translate.py source_language target_language`` (i.e. python translate.py fr en for fr->en translation)

Training results are shown in plot_training_process.ipynb.

Testing results and findings are discussed in the paper.


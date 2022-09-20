# Dive into Deep Learning (Kotlin version)

This project is modified from the original [Dive Into Deep Learning (Java version)](https://d2l.djl.ai/) by Deep Java Library project (https://djl.ai/).
The Java version is modified from the original [Dive Into Deep Learning](https://d2l.ai) book by Aston Zhang, Zachary C. Lipton, Mu Li, Alex J. Smola and all the community contributors. 
GitHub of the original book: [https://github.com/d2l-ai/d2l-en](https://github.com/d2l-ai/d2l-en). 
We have adapted the book of Java version to to use Kotlin and the [Deep Java Library(DJL)](https://djl.ai).

All the notebook here can be downloaded and run using Kotlin Kernel.

This project is currently being developed and maintained by Takanori Ugai.

## How to run Jupyter Notebook in Kotlin

### Local
Please follow the instruction [here](https://d2l.djl.ai/chapter_installation/index.html) for how to run notebook using Java kernel
and Kotlin kernel from (https://github.com/Kotlin/kotlin-jupyter)


## How to contribute to this book

Please follow the contributor guide [here](documentation/contribute.md)


We have the following chapters implemented
* [preface](chapter_preface/index.ipynb)
* [installation](chapter_installation/index.ipynb)
* [notation](chapter_notation/index.ipynb)
* [introduction](chapter_introduction/index.ipynb)
* [preliminaries](chapter_preliminaries/)
* [linear-networks](chapter_linear-networks/)
* [multilayer-perceptrons](chapter_multilayer-perceptrons/)
* [deep learning computation](chapter_deep-learning-computation/)
* [convolutional-neural-networks](chapter_convolutional-neural-networks/)
* [modern-convolutional-neural-networks](chapter_convolutional-modern/)
* [recurrent-neural-networks](chapter_recurrent-neural-networks/)
* [recurrent-modern](chapter_recurrent-modern/)
* [attention-mechanisms](chapter_attention-mechanisms/)
* [optimization algorithms](chapter_optimization/)
* [computational performance](chapter_computational-performance/)
* [computer vision](chapter_computer-vision/)
* [natural-language-processing-pretraining](chapter_natural-language-processing-pretraining/)

## About Deep Java Library

[Deep Java Library (DJL)](https://djl.ai) is a Deep Learning Framework written in Java, supporting both training and inference. DJL is built on top of modern Deep Learning frameworks (TenserFlow, PyTorch, MXNet, etc). You can easily use DJL to train your model or deploy your favorite models from a variety of engines without any additional conversion. It contains a powerful ModelZoo design that allows you to manage trained models and load them in a single line. The built-in ModelZoo currently supports more than 70 pre-trained and ready to use models from GluonCV, HuggingFace, TorchHub and Keras.

Follow our [GitHub](https://github.com/deepjavalibrary/djl/tree/master/docs), [demo repository](https://github.com/deepjavalibrary/djl-demo), [Slack channel](https://join.slack.com/t/deepjavalibrary/shared_invite/zt-ar91gjkz-qbXhr1l~LFGEIEeGBibT7w) and [twitter](https://twitter.com/deepjavalibrary) for more documentation and examples of DJL!

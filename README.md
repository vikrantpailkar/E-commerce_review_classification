[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

[<img src="https://avatars1.githubusercontent.com/u/36938641?s=200&u=b2d470fe66acc157d8ca8cb3fb815dee47d4466d&v=4" align="right" />](https://github.com/machine-learning-experiments)

# Sentiment classification by text
This project uses a neural network to classify the sentiment of a review as positive or negative.
> See the [jupyter notebook](https://github.com/machine-learning-experiments/sentiment-classification-by-text/blob/master/sentiment_classification_neural_network.ipynb)

### Motivation

Practicing noise reduction and performance optimization of a neural network.

### Built With

- [Python 3](https://www.python.org/download/releases/3.0/) - Language
- [Anaconda](https://www.anaconda.com/what-is-anaconda/) - Python Data Science Platform 
- [Jupyter notebook](http://jupyter.org/) - Web application that allows to create documents that contain live code

### Dataset

List of movie reviews from IMDB

### Result

- Final speed: 1.2k reviews/sec
- Final accuracy: 85.9%
- Reviews used: 1k

## Getting Started

### Prerequisites
1. Download and install [Anaconda](https://www.anaconda.com/download/)
2. Update Anaconda
> ``` 
> $ conda upgrade conda 
> $ conda upgrade --all 
> ```

### Install

1. Clone and enter into the project's root directory by command line
> ``` 
> $ git clone https://github.com/machine-learning-experiments/sentiment-classification-by-text.git
> ```
2. Create and activate enviroment
> ``` 
> $ conda env create -f enviroment.yaml 
> $ conda activate sentiment-classification-by-text 
> ```
or
> ``` 
> conda create --name sentiment-classification-by-text python=3
> source activate sentiment-classification-by-text
> conda install numpy matplotlib scikit-learn jupyter notebook bokeh
> ```
3. Start jupyter notebook
> ``` 
> $ jupyter notebook 
> ```
4. Your browser will open showing a list of files, click on the  [sentiment_classification_neural_network.ipynb](https://github.com/machine-learning-experiments/sentiment-classification-by-text/blob/master/sentiment_classification_neural_network.ipynb) notebook file
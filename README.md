# IMDBmovie-review-classification-using-VANILLA-RNN
This repository contains code for a simple RNN model to classify movie reviews from the IMDB dataset as positive or negative. The model is implemented using TensorFlow and Keras.

## Installation
To set up the environment, you can use either `venv` or `conda`. Follow the instructions below based on your choice:
### Using venv
```bash
python3 -m venv myenv
source myenv/bin/activate
pip install -r requirements.txt
```
### Using conda
```bash
conda create -n myenv python=3.12
conda activate myenv
pip install -r requirements.txt
```
## Usage
To run the code, execute the following command in your terminal:
```bash
python main.py
```
This will train the RNN model on the IMDB dataset and evaluate its performance on the test set. The results will be printed in the terminal.
## Dataset
The IMDB dataset is a collection of 50,000 movie reviews, labeled as positive or
negative. The dataset is split into 25,000 reviews for training and 25,000 reviews for testing. The reviews are preprocessed and tokenized before being fed into the RNN model.
## Model Architecture
The RNN model consists of an embedding layer, followed by a simple RNN layer and a dense output layer. The embedding layer converts the input words into dense vectors, while the RNN layer processes the sequence of word vectors to capture the temporal dependencies in the reviews. The dense output layer produces a binary classification output indicating whether the review is positive or negative.
## Performance
The performance of the model can be evaluated using metrics such as accuracy, precision, recall, and F1-score. The results may vary based on the hyperparameters and the training process. It is recommended to experiment with different configurations to achieve better performance.
## Conclusion
This repository provides a simple implementation of a vanilla RNN for movie review classification using the IMDB dataset. It serves as a starting point for understanding how RNNs can be used for natural language processing tasks. You can further enhance the model by exploring more advanced architectures such as LSTM or GRU, or by applying techniques like dropout and regularization to improve performance. 

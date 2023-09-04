# CHARACTER BASED TEXT GENERATION RNN MODEL

This is a character level text generation model using a single layer of RNN/GRU (or alternatively LSTM) units.

The code is inspired from [tensorflow's guide](https://www.tensorflow.org/text/tutorials/text_generation) but written with Pytorch.

This is usually the first model to study / implement when learning NLP.

# SETUP
- Run the notebook `char-text-generation-rnn.ipynb` on Google Colab
    - The notebook contains:
        1. code to preprocess the text data for feeding to the ml model (note the original text - Shakespeare's works - is mostly clean so the steps mainly include steps for splitting and tokenizing the data)
        2. code to train the ml model
        3. code to generate text with the trained model

For PCs
- Install Python and dependencies `pip install -r requirements.txt`
- Run the Jupyter notebook `char-text-generation-rnn.ipynb`


TODO
- Improve setup and usage instructions to this README.md
- Add more comments to the main Jupyter notebook
- Improve text cleaning process in extract_from_pdfs Jupyter notebook

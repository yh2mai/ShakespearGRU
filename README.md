# Shakespear Text Generation with GRU

This project implements a character-level language model using a GRU (Gated Recurrent Unit) network to generate Shakespeare-style text. The implementation is provided in the Jupyter Notebook `ShakespearGRU.ipynb`.

## GitHub Repository

Original project link: https://github.com/yh2mai/ShakespearGRU

## Project Structure

├── ShakespearGRU.ipynb   # Main Jupyter Notebook

├── data/                 # Folder containing training text dataset

├── README.md             # Project documentation

└── requirements.txt      # Python dependencies

## Features

- Loads and preprocesses Shakespeare text data
- Trains a GRU-based neural network for character-level prediction
- Generates Shakespeare-like text from a starting seed

## Requirements

Install dependencies using:

pip install -r requirements.txt

## Usage

1. Ensure the `data/` folder contains the necessary dataset (e.g., Shakespeare text file)
2. Open the notebook:

jupyter notebook ShakespearGRU.ipynb

3. Run through the cells to preprocess data, train the model, and generate text.

## License

Refer to the original GitHub repository for licensing details.

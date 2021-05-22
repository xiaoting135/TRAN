# TRAN

# TRAN

## Environment

Python 3.6 & Tensorflow > 1.3

## Data

All data, including Stock Historical Sequence Data, Stock Description Document and Stock Relation, are under the data folder. These datasets can be downloaded from: https://drive.google.com/drive/folders/1ybd0XxIpBqJNAax0aioOQHPcEMMv0JoB?usp=sharing.

### Stock Historical Sequence Data

Under the 2013-01-01 folder, there are the processed data in NASDAQ and NYSE markets.

### Stock Description Document

Under the summary folder, there are the description documents of the stocks and their corresponding companies in NASDAQ and NYSE markets.

### Stock Relation

Under the relation folder, there are row relation file storing the sector_industry relations between stocks in NASDAQ and NYSE markets.


## Code

### Preprocess

sector_industry.py: Generate multi-hot binary vector of industry relation  

### Training
rank_lstm.py: Train a model of Rank_LSTM  
TRAN.py: Train a model of Time-aware Relational Attention Network  
TRAN_doc2vec.py: Replace the topic based model with the Doc2vec in the text encoder and then train a model of Time-aware Relational Attention Network  

The code is being improved and will be shared in the future.

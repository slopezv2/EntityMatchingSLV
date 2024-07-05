# EntityMatchingSLV
Repo for Entity Matching project related to known techniques for heterogeneous database matching.

## Current notebooks:
### Data Acquisition and understanding
- Exploration_products_csv: You can find there the EDA done to database: [Product Clustering, Matching & Classification](https://www.kaggle.com/datasets/lakritidis/product-clustering-matching-classification). Cartesian product done here to get 2 products in a row to compare.
- feature_engineering: Create features using text distances, scale values between [0,1] and save dataframe as parquet file.
- Embeddings: Transforms product descriptions into vectors (embeddings) and save them as parquet files. 
- Generate_synthetic_data: Calculates distributions, bayesian networks and copulas to generate new synthetic data.
### Deployment
An example architecture for a productive deployment.
### Modeling
- model_net: Modeling using neuronal networks RNN and ANN and word2vec embeddings from product descriptions.
- Models_cpus: Bayesian Naive Bayes models and traditionals modeling.
- traditiona_model: Scikit learn Multi-layer Perceptron neural network training.
- Training_Synthetic_data: Training Bernoulli NB using more than 1 million new synthetic records for matched products.
### Research
- Bayesion: Examples to calculate bayesian networks and CPDs based on observed data.
- Naive_Bayes: Examples for using Scikit-learn Naive Bayes models and how to interpret resulting models.
- string_matching: Text distance examples, first analysis about distance metrics.
## Docs
You can find here the generated reports about distribution for the dataframes.
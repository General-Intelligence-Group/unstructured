Embedding Configuration
=========================

A common embedding configuration is a critical component that allows for dynamic selection of embedders and
their associated parameters to create vectors from data. This configuration provides the flexibility to choose
from various embedding models and fine-tune parameters to optimize the quality and characteristics of the resulting vectors. It
enables users to tailor the embedding process to the specific needs of their data and downstream applications,
ensuring that the generated vectors effectively capture semantic relationships and contextual information within
the dataset.

Configs
---------------------
* ``api_key``: If an api key is required to generate the embeddings via an api (i.e. OpenAI)
* ``model_name``: The model to use for the embedder.

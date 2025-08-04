# Elasticsearch Python Examples

This repository contains Python and Jupyter Notebook examples for working with [Elasticsearch](https://www.elastic.co/elasticsearch/) using the official Python client.

## Contents

- `CreateIndex.ipynb`: Demonstrates creating indices, configuring shards and replicas, defining mappings, and inserting documents.
- `dataType.ipynb`: Shows how to use various Elasticsearch data types, including binary, object, flattened, nested, and completion types.
- `Delete_document.ipynb`: Provides examples for deleting documents by ID and by query.

## Prerequisites

- [Elasticsearch](https://www.elastic.co/downloads/elasticsearch) running locally (`http://localhost:9200`)
- Python 3.x
- Install dependencies:
  ```bash
  pip install elasticsearch
  ```

## Usage

1. Start your local Elasticsearch server.
2. Open the notebooks in JupyterLab or VS Code.
3. Run the cells to interact with Elasticsearch:
   - Create indices and mappings.
   - Insert and query documents.
   - Explore different data types.
   - Delete documents by ID or query.

## Data

- Example data for bulk insertion is expected in `Data/data.json`.

## Author

Abhishek Nangare

## License

MIT License


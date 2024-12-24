# Word Embedding Matrix Creation and Pretrained Embeddings

This script processes a pretrained word vector file to create an embedding matrix, mapping words in a given vocabulary to their corresponding vector representations. The embeddings are then used to initialize a Keras `Embedding` layer for natural language processing tasks.

## Setup Instructions

1. **Pretrained Word Vectors**:
   - Download a pretrained word vector file (e.g., `wiki-news-300d-1M.vec` from FastText).
   - Save the file to the specified location in the script.

2. **Install Dependencies**:
   Ensure the following Python libraries are installed:
   ```bash
   pip install numpy tensorflow

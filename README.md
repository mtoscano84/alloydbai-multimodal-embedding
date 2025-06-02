# AlloyDB AI - Multimodal Embedding

Note: This project is for demonstration only and is not an officially supported Google product.

## Introduction

This repository contains a Google Colab notebook demonstrating how to use the new multimodal embedding capabilities of AlloyDB AI. The notebook walks through the entire process of generating a sample image catalog, creating embeddings, and performing powerful similarity searches using both images and text as queries.

The core of this demo showcases the native AlloyDB AI feature that enables multimodal embeddings directly inside the database. For more information, see the official documentation: https://cloud.google.com/alloydb/docs/ai/generate-multimodal-embeddings?resource=ai

## Features demonstrated

- **Multimodal Embeddings**: Generating vector embeddings from images using the ai.image_embedding() SQL function in AlloyDB.
- **Image Generation**: Using Vertex AI's Imagen 4 model to create a catalog of sample images.
- **Image-to-Image** Search: Providing an input image to find the most visually similar images from the catalog.
- **Text-to-Image** Search: Providing a descriptive text string to find the most relevant images from the catalog.
- **Accelerated Search**: Creating a ScaNN index to speed up vector similarity searches.

## Getting Started

### Prerequisites

Before running the notebook, ensure you have the following:

1. A Google Cloud Project with the Vertex AI API enabled.
2. An AlloyDB Cluster (follow the instructions here to deploy a new cluster: https://cloud.google.com/alloydb/docs/cluster-create)
3. Proper authentication to access your GCP project and resources.

### Run the demo

1. Clone the Repository
```
git clone https://github.com/your-username/alloydbai-multimodal-embedding.git
cd alloydbai-multimodal-embedding
```

2. Run the notebook

Open the notebook (.ipynb file) and update the configuration cells with your project and database details to run the demo

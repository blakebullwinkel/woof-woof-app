# Woof Woof! App

React app for the Austin Pets Alive animal shelter that uses backend NLP and computer vision models trained using transfer learning.

## Description of directories

- `backend-api`: Creates a Docker container for the API server, which manages the data (images, text) needed for the app
- `backend-embedding-search`: Implements image embeddings (EfficientNetB0) and similarity search (FAISS) for dogs in the animal shelter
- `backend-model-server`: Implements a dialog model by finetuning a pretrained GPT-2 with PERSONA-CHAT and text data specific to each dog
- `frontend`: Implements a React web app frontend that allows users to "chat" with and search for visually similar dogs in the animal shelter

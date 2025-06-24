# TMDB-Multimodal-Genre-Classification
This project uses deep learning to classify movies into their primary genre by combining both poster images and plot overviews. All data was retrieved using the TMDB (The Movie Database) API.

We applied a multimodal neural network architecture combining:
- LSTM (for plot text)
- EfficientNetB0 (for poster images)

to perform single-label genre classification.

### This project includes:
- Data collection using the TMDB API with Bearer Token authorization
- Exploratory Data Analysis (EDA) on genre frequency, class imbalance, and text/visual patterns
- Multimodal model combining text and image features using Keras/TensorFlow
- Performance evaluation using accuracy, confusion matrix, and classification reports
- Visualizations of predictions vs true labels for a sample of movie posters
- Discussion of limitations such as genre imbalance and model overfitting
- Future improvements including BERT, CLIP, and metadata integration

---

### Technologies Used:
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- TensorFlow / Keras
- TMDB API
- Jupyter Notebook

---

### Note on API Access

You must provide your own TMDB Bearer Token to run this notebook. You can request one by creating an account at [TMDB Developers](https://developer.themoviedb.org/).

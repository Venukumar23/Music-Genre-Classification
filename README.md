Music Genre Classification using Deep Learning

Overview:
This project focuses on building a web-based Music Genre Classification system using deep learning techniques. The model takes an audio file as input and predicts the genre of the music (e.g., rock, pop, classical, etc.). The system leverages modern machine learning and audio processing techniques to classify music based on its features.

Features:
Genre Classification: Classifies audio files into different music genres.
Web Interface: User-friendly web interface to upload music files and display predictions.
Deep Learning Model: Uses deep neural networks to learn from music features and make accurate predictions.
Data Preprocessing: Extracts features from audio files, such as Mel-frequency cepstral coefficients (MFCCs), for effective training of the model.
Technologies Used
Python: Programming language used for building the model and the web interface.
TensorFlow/Keras: Deep learning frameworks for building the neural network model.
Librosa: A Python library for audio and music analysis, used for feature extraction from audio files.
Flask: Web framework used to build the application.
HTML/CSS/JavaScript: Used for the front-end web interface.


Installation:
git clone (https://github.com/Venukumar23/Music-Genre-Classification.git)

pip install -r requirements.txt

python app.py
This will start the Flask web server locally. You can then access the application in your browser at http://127.0.0.1:5000.

How It Works:
Upload an Audio File: The user uploads a music file through the web interface.
Preprocessing: The audio file is processed to extract relevant features, such as MFCCs.
Prediction: The preprocessed features are passed to the deep learning model for genre prediction.
Display Result: The predicted genre is displayed on the web interface.
Dataset
The model is trained on a large dataset of music tracks with labeled genres. The dataset contains various genres, including pop, rock, classical, and more. You can use publicly available datasets such as the GTZAN dataset for training the model.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
GTZAN Dataset: For providing a comprehensive dataset for training the model.
Librosa: For making audio feature extraction easy and efficient.

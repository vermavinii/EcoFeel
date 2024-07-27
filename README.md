# EcoFeel

**EcoFeel**: Decoding Emotions from Voice

EcoFeel explores the intersection of audio processing and emotional intelligence. By utilizing sophisticated algorithms, EcoFeel decodes the emotional undertones of spoken language, transforming raw audio data into meaningful emotional insights. The system is capable of classifying various emotions such as happiness, sadness, anger, and more.

## Features
- **Emotion Classification**: Accurately identify and classify a range of emotions from speech samples.
- **Feature Extraction**: Utilize Mel-frequency cepstral coefficients (MFCCs), chroma, and mel-spectrogram features to capture essential audio characteristics.
- **Model Training and Evaluation**: Implement and train machine learning models, including MLP (Multi-Layer Perceptron) classifiers, to recognize and predict emotions.
- **Interactive Interface**: Upload and process audio files to obtain emotion predictions with user-friendly feedback.

## How It Works
- **Data Collection**: The project utilizes a diverse dataset of speech recordings, each labeled with the corresponding emotion.
- **Feature Extraction**: Key audio features are extracted from the recordings using state-of-the-art libraries like Librosa.
- **Model Training**: Machine learning models are trained on these features to learn patterns associated with different emotions.
- **Emotion Prediction**: Once trained, the model can predict the emotion of new audio samples based on learned patterns.

## Setup 🔥

1. **Fork the Repo**:
   - Fork this repository to your own GitHub account by clicking the "Fork" button at the top right of this page.

2. **Clone the Repo**:
   - Clone the forked repository to your local machine using the following command:
     
     ```bash
     git clone <repo-url>
     ```

3. **Download the Dataset**:
   - The dataset used in this project is not included in the repository due to its size. You can download it from the following link:
  
     [Download Dataset](https://drive.google.com/file/d/1wWsrN2Ep7x6lWqOXfr4rpKGYrJhWc8z7/view)
   - After downloading, unzip the dataset and place it in the `dataset` folder of the project. Make sure to change the path to the dataset in the Jupyter Notebook accordingly.

4. **Install Dependencies**:
   - If you are using a Jupyter Notebook environment, you can install the required libraries directly from the notebook using:
    
     ```python
     !pip install librosa soundfile numpy scikit-learn pyaudio
     ```
   - If soundfile shows error you can also use

     ```python
     %pip install soundfile
     ```

5. **Run the Project**:
   - Open the Jupyter Notebook file `EcoFeel.ipynb` in Jupyter Notebook or Jupyter Lab. You can do this by running:
    
     ```bash
     jupyter notebook EcoFeel.ipynb
     ```
   - Follow the instructions within the notebook to execute the cells and run the project.

## Results
The project's performance is evaluated based on accuracy, precision, and recall metrics. Through rigorous testing, the model demonstrates robust capabilities in distinguishing between various emotions from speech samples.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please submit a pull request or open an issue.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Special thanks to the creators of the libraries and tools that made this project possible, including Librosa, Scikit-learn, and others.

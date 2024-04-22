## Project Title: Mental_Health_Emotion
### Description:
The Mental_Health_Emotion project aims to analyze mental health states using audio data. By leveraging machine learning algorithms and deep learning models, this project seeks to extract insights from audio recordings to understand emotional patterns and potentially assist in mental health diagnosis and support.

### Data Source:
The Data-set used in the project was obtained from kaggle. which contains the audio data of 2 actor in which each person has different voice and each has the audio data for all the 7 classes and each class inside individual person have 200 audio samples per class.
link to the data-set :https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess/data


### Project Steps:
#### 1) Data Preprocessing:
The audio data undergoes preprocessing steps to clean and normalize the recordings, ensuring consistency and quality for further analysis.

#### 2) Exploratory Data Analysis (EDA):
Exploratory data analysis is conducted to gain insights into the characteristics of the dataset. Visualizations and statistical summaries help in understanding the distribution and patterns within the data.

#### 3) Feature Extraction:
Mel-Frequency Cepstral Coefficients (MFCC) are extracted from the audio data to convert it into a numerical format suitable for machine learning analysis.

#### 4) Machine Learning Algorithms:
Various machine learning algorithms, such as Support Vector Machines (SVM), Random Forest, etc., are employed to predict mental health states based on the extracted features. Performance metrics are evaluated to assess the effectiveness of the models.

#### 5) Deep Learning Model:
A Feedforward Neural Network (FFNN) is implemented as a deep learning model to further analyze the audio data. Architecture details and optimization techniques are utilized to achieve high accuracy in predicting emotional states.

## Repository Structure
1) `Mental-Health-Emotion.ipynb`: Contains the main code of the project
2) `Readme.md`: Contains the details about the project
3) `Report`
4) `Audio Dataset`: contains the audio data used in the project
5) `Spectogram Emotion Images`: various images of Emotions in Spectogram
6) `Waveform Emotion Images`: Various waveform images of various Emotions
7) `Accuracy Curve`: Deep learning Model Accuracy Curve
8) `Loss Curve`: Deep learning Model Loss Curve on Training and Validation Data
9) `Confusion-Matrix` : Random forest and Decision Tree Confusion Matrices Image 

## Usage
1) Clone the repository to your local machine.
2) Install the required dependencies mentioned in the project files.
3) Execute the provided scripts or notebooks to reproduce the results and explore the analysis.

## Future Work
**Future enhancements to this project may include:**

1) Incorporating real-time audio analysis for continuous monitoring.
2) Expanding the dataset to encompass a broader range of emotional states and demographic diversity.

## Contributors
Sujal Thakkar: thakkar.su@northeastern.edu , sujalthakkar95@gmail.com

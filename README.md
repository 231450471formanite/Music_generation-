# Music_generation-
# Music Generation using LSTM

This project demonstrates music generation using LSTM (Long Short-Term Memory) neural networks. It uses the Lakh MIDI Dataset (LMD) as the training data to generate new musical compositions.

## Dataset

The Lakh MIDI Dataset (LMD) is a large collection of MIDI files containing musical compositions across various genres. It can be downloaded from [this website](http://hog.ee.columbia.edu/craffel/lmd/lmd_full.tar.gz). The dataset consists of MIDI files representing musical notes, timing, and other musical parameters.

## Project Structure

The project is organized as follows:

- `data`: This directory will contain the downloaded and extracted MIDI dataset.
- `models`: This directory will store the trained LSTM models.
- `notebooks`: This directory contains Jupyter notebooks for data preprocessing, model training, and music generation.
- `src`: This directory includes the source code files for data loading, preprocessing, model architecture, and music generation.
- `requirements.txt`: This file lists the required Python libraries and their versions.

## Usage

1. Download and extract the Lakh MIDI Dataset by following the link provided above.
2. Place the extracted MIDI files in the `data` directory.
3. Open the Jupyter notebooks in the `notebooks` directory to run the data preprocessing, model training, and music generation steps.
4. Refer to the documentation in the notebooks for detailed instructions and explanations.

## Requirements

Make sure you have the following libraries installed:

- Python (>=3.6)
- NumPy
- Pandas
- TensorFlow
- Keras
- Music21

Install the required libraries using the following command:


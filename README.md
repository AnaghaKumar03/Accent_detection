# Accent Detection Project

This project implements a machine learning system for detecting and classifying speech accents from audio recordings. The system can identify six different accent categories: English, Spanish, Arabic, French, Mandarin, and other accents.

## Project Overview

The project uses deep learning techniques to analyze audio recordings and determine the speaker's accent. It processes audio data through a pipeline that includes preprocessing, feature extraction, and classification using transformer-based models.

## Features

- Audio processing and resampling at 16kHz
- Support for multiple accent classifications
- Data preprocessing and augmentation
- Deep learning-based accent classification
- Handling of imbalanced datasets using oversampling and undersampling techniques

## Requirements

The project requires the following main dependencies:
- Python 3.x
- PyTorch
- Transformers (version 4.28.1)
- Torchaudio (version 0.12)
- Datasets
- pandas
- numpy
- imbalanced-learn
- ffmpeg

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/Accent_detection.git
cd Accent_detection
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Additional system requirements:
```bash
# For Ubuntu/Debian systems
sudo add-apt-repository -y ppa:savoury1/ffmpeg4
sudo apt-get install -y ffmpeg
```

## Project Structure

The project consists of two main Jupyter notebooks:
- `slp-project-1.ipynb`: Initial data processing and model setup
- `slp-project-2.ipynb`: Model training and evaluation

## Data Processing

The system processes audio files with the following specifications:
- Sampling rate: 16kHz
- Maximum audio length: 128000 samples (8 seconds)
- Supported accent labels: English, Spanish, Arabic, French, Mandarin, and Other

## Usage

1. Open the Jupyter notebooks in order:
   - Start with `slp-project-1.ipynb` for data preparation
   - Continue with `slp-project-2.ipynb` for model training and evaluation

2. Follow the instructions in each notebook to:
   - Load and preprocess the audio data
   - Train the accent detection model
   - Evaluate the model's performance
   - Make predictions on new audio samples

## Model Architecture

The project uses transformer-based models for accent classification, leveraging state-of-the-art deep learning techniques for audio processing and classification.

## License

[Add your chosen license here]

## Contributing

Contributions to improve the project are welcome. Please feel free to submit pull requests or open issues to discuss potential improvements.

## Acknowledgments


- The transformers and torchaudio communities for their excellent libraries

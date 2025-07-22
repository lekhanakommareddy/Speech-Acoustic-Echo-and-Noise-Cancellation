# Speech-Acoustic-Echo-and-Noise-Cancellation

This project presents a deep learning-based solution for enhancing real-time speech communication by performing acoustic echo cancellation and background noise reduction. The primary objective is to improve speech clarity and intelligibility in environments with unwanted interference, making it suitable for applications like VoIP, conferencing systems, and voice assistants.


## Key Features
-**Novel Deep Learning Architecture**: Combines the power of:

-**Convolutional Neural Networks (CNNs)** for feature extraction from audio signals.

-**Bidirectional LSTMs (BiLSTMs)** for modeling temporal dependencies in speech.

-**Squeeze-and-Excitation (SE) Blocks** to recalibrate feature importance dynamically.

-**Multi-Head Attention mechanism** for focusing on important parts of the signal.

-**Acoustic Echo Cancellation**: Removes echoes from far-end speech picked up by local microphones.

-**Noise Suppression**: Effectively reduces background and environmental noise from the speech input.

-**Real-time Capable**: Architecture designed for low-latency speech processing.


## Technologies Used

-**Programming Language**: Python

-**Deep Learning Frameworks**: PyTorch, TensorFlow/Keras

-**Audio Processing Libraries**: NumPy, SciPy, Librosa

-**Models and Techniques**: CNN, LSTM, SE Blocks, Multi-Head Attention


## Results
The model achieves significant improvement in speech enhancement metrics:

Improved Signal-to-Noise Ratio (SNR)

Better PESQ (Perceptual Evaluation of Speech Quality)

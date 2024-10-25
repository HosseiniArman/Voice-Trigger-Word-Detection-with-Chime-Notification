# Voice Trigger Word Detection with Chime Notification

This project implements a voice trigger word detection system using a deep learning model to identify specific audio triggers (such as "activate"). When the model detects a trigger word, it overlays a chime sound onto the audio to mark the detection. This project includes everything needed to preprocess audio, detect trigger words, and overlay chime notifications on detected segments.

## Project Structure

- **scripts/**: Contains the main Python script for running trigger word detection and chime overlay.
- **data/**: Contains the required audio files and examples for testing the model. 
  - **audio_examples/**: Includes example audio files for model testing.
  - **raw_data/**: Contains various background, activation, and negative audio samples for creating the training dataset.
- **models/**: Stores the pre-trained model files (`model.json` and `model.h5`).
- **output/**: The generated output audio files with chime overlays will be saved here.

## Features

- **Trigger Word Detection**: Detects specified keywords in audio streams.
- **Chime Notification Overlay**: Adds a chime sound overlay when a trigger word is detected.
- **Spectrogram Analysis**: Uses spectrograms to analyze audio frequency content.
- **Pre-trained Model**: Includes a model trained on trigger words and background noise to improve detection accuracy.

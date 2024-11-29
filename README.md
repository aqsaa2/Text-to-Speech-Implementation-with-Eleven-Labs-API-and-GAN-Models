# Text-to-Speech Generation with Eleven Labs API and GAN Models

This repository provides implementations for Text-to-Speech (TTS) generation using two approaches:


Eleven Labs API for quick and high-quality multilingual TTS synthesis.


GAN-based TTS Models leveraging TensorFlowTTS for advanced, customizable audio synthesis using Tacotron 2, FastSpeech, MelGAN, and Multi-band MelGAN.
Features


## 1. Eleven Labs API
Generate multilingual TTS audio with Eleven Labs.


Includes support for voices like "Brian" and model options like eleven_multilingual_v2.


Outputs high-quality audio in .mp3 format.


Simple API-based implementation.


## 2. GAN-based TTS Models


Uses TensorFlowTTS to implement state-of-the-art GAN models for TTS:


Tacotron 2 + MelGAN


Tacotron 2 + Multi-band MelGAN


FastSpeech + MelGAN


FastSpeech + Multi-band MelGAN


### Visualizations of:


Mel spectrograms.


Predicted audio waveforms.


Comparisons between models to evaluate their performance.


### Installation


#### Prerequisites


Python 3.7+


GPU-enabled environment (optional for faster processing).


Install Required Libraries


Run the following commands to set up the environment:


pip install requests


pip install elevenlabs


pip install ipython-autotime


pip install tensorflow-gpu


pip install jamo unidecode tensorflow_addons pypinyin g2p_en


git clone https://github.com/TensorSpeech/TensorFlowTTS.git


cd TensorFlowTTS


git checkout r1.6.1


pip install .


cd ..


## Usage


Eleven Labs API


Generate high-quality multilingual TTS audio using a simple script.


Customize input text, voices, and models.


## GAN-based TTS Models


Convert text to mel spectrogram using Tacotron 2 or FastSpeech.


Convert mel spectrogram to audio using MelGAN or Multi-band MelGAN.


Visualize spectrograms and audio waveforms for analysis.


Compare model performances using metrics like audio sample length and waveform characteristics.


## Visualization


Spectrograms and waveforms are plotted using Matplotlib for better insight into TTS model outputs.


Detailed comparisons allow for evaluation of model quality and characteristics.

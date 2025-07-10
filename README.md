# Real-Time-Environmental-Sound-Classification
🎙️ Real-time environmental sound classification using ESC-10 dataset and PyTorch

This project implements a real-time audio classification system using Convolutional Neural Networks (CNNs) with PyTorch. It recognizes 10 environmental sound classes from the ESC-10 dataset (e.g., dog bark, rain, siren) from microphone input or audio files with live spectrogram visualization.

🚀 Key Features

    🎤 Real-time Inference
        Classifies sounds from microphone input with <1s latency
        Interactive web-based recorder for Colab/Jupyter notebooks

    📊 Advanced Audio Processing
        Mel-spectrogram conversion with librosa
        Dynamic audio padding/trimming for consistent input size

    🧠 Deep Learning Pipeline
        Custom CNN architecture optimized for spectrogram analysis
        Data augmentation (time-stretching, gain adjustment)
        Learning rate scheduling & early stopping

    🔧 Developer Friendly
        Complete training/evaluation scripts
        Model checkpointing
        Confidence scores for predictions

🌟 Sample Outputs

      🎤 Processing audio...
      🔊 PREDICTION: dog (confidence: 88.53%)
      🎤 Processing audio...
      🔊 PREDICTION: clock_tick (confidence: 99.06%)
      🎤 Processing audio...
      🔊 PREDICTION: crying_baby (confidence: 97.91%)
      🎤 Processing audio...
      🔊 PREDICTION: crackling_fire (confidence: 79.10%)
      🎤 Processing audio...
      🔊 PREDICTION: rain (confidence: 81.62%)
      🎤 Processing audio...
      🔊 PREDICTION: chainsaw (confidence: 66.89%)
      🎤 Processing audio...
      🔊 PREDICTION: sneezing (confidence: 99.75%)

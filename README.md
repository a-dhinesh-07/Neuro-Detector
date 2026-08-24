# Neuro-Detector
EEG-signal based State Detector

## Project Overview
Neuro-Detector is a machine learning project designed to detect and classify human mental and physiological states using EEG (Electroencephalography) signals. By analyzing brain wave patterns, the system can identify which state a person is in—whether they are sleepy, awake, in deep focus, or experiencing extreme computational load.

## How It Works
The project leverages EEG signal processing to identify distinct brain wave bands and their corresponding mental states:

### EEG Brain Wave Bands
- **Delta Waves (0.5-4 Hz)**: Associated with deep sleep and unconscious states
- **Theta Waves (4-8 Hz)**: Related to drowsiness and light sleep
- **Alpha Waves (8-12 Hz)**: Dominant during relaxation and calm wakefulness
- **Beta Waves (12-30 Hz)**: Present during active thinking and focused attention
- **Gamma Waves (30+ Hz)**: Associated with high-level cognitive processing and intense concentration

### Detectable States
The model classifies EEG signals into the following mental/physiological states:
- Sleepy
- Awake
- Focused/Computing
- Extreme Concentration

## Technical Details
- **Language**: Python
- **Machine Learning Algorithm**: Random Forest
- **Dataset**: Kaggle EEG signal datasets
- **Approach**: Classification model trained on preprocessed EEG signal data to achieve high accuracy in state detection
- **Validation**: Accuracy scores from model testing and cross-validation

## Implementation
The project involves:
1. Data preprocessing and feature extraction from raw EEG signals
2. Feature engineering to identify relevant brain wave band characteristics
3. Training a Random Forest classifier on labeled EEG data
4. Evaluating model performance with accuracy metrics


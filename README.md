# EEG Signal Analysis Project

## Project Overview

This project involves the analysis of a dataset comprising electroencephalography (EEG) signals, visual stimuli, and auditory data collected from human participants. The data were recorded using a five-electrode configuration (AF3, AF4, T7, T8, Pz) at a sampling rate of 128 kHz while participants processed visual stimuli. The original EEG data has been provided in `.csv` format, along with the corresponding image and audio files. 

The project is divided into two parts: Beginner and Intermediate, each containing a set of machine learning and signal processing tasks.

## Dataset Description

- **EEG Data**: Collected using five electrodes (AF3, AF4, T7, T8, Pz) with a sampling rate of 128 kHz.
- **Image Data**: Corresponding visual stimuli presented to participants.
- **Audio Data**: Auditory stimuli associated with the visual stimuli.
- The data is available in `.csv` (EEG), image, and audio formats.

## Task Overview

### Beginner Level

1. **Random Number Generator (2 Marks)**
   - Implemented a random number generator that generates random numbers based on a given size.
   - Plotted random numbers for sizes `1×n` and `n×n`.

2. **Sample Selection from EEG Data (1 Mark)**
   - Utilized the random number generator to select 12 random samples from the EEG data.
   - Printed the metadata of the selected samples.

3. **Normalization Function (3 Marks)**
   - Implemented a normalization function that normalizes data within a specified range `[-x, x]`.
   - Normalized and plotted 4 randomly selected EEG signals.

4. **Image and Audio Processing (4 Marks)**
   - **Image Data:**
     - Reshaped images to `(3, 224, 224)`.
     - Converted images to Black & White (BW).
     - Plotted histograms for both color and BW images.
     - Calculated the Center of Mass for all images.
   - **Audio Data:**
     - Resampled audio to 16,000 Hz.
     - Converted audio signals to MelSpectrogram.
     - Plotted time-domain and frequency-domain signals.
     - Calculated the Zero Crossing Rate for all time-domain signals.

5. **Power Spectral Density (PSD) Calculation (3 Marks)**
   - Calculated and plotted the Power Spectral Density (PSD) of 4 randomly selected EEG signals.

### Intermediate Level

1. **Cross-Correlation and Auto-Correlation (4 Marks)**
   - Calculated and plotted the Cross-Correlation and Auto-Correlation of 4 randomly selected EEG signals.

2. **Exploratory Data Analysis (EDA) (4 Marks)**
   - Performed EDA on the dataset, including visualization, statistical analysis, class imbalance analysis, feature visualization, and outlier detection.
   - **EDA on Image Data**
   - **EDA on Audio Data**

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: `numpy`, `matplotlib`, `scipy`, `pandas`, `PIL` etc.

### Questions addressed in assignment - 1

1. Task attempted:
    - Task 1: `python random_number_generator`
    - Task 2: `python sample_selection`
    - Task 3: `python normalization_function`
    - Task 4: `python image_audio_processing`
    - Task 5: `python power_spectral_density`
    - Task 6: `python cross_auto_correlation`
    - Task 7: `python exploratory_data_analysis`

### Results

- Each task script generates visualizations and outputs results to the console or saved files.

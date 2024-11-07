# Music Classifier

A project to classify music genres and generate personalized playlists based on audio features.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Steps to See Results](#steps-to-see-results)
  - [Bonus: Generate Playlists](#bonus-generate-playlists)
- [Data Download **(IMPORTANT)**](#data-download)
- [Usage](#usage)

## Prerequisites

Before running the notebooks, ensure you have the following installed:

- Python 3.x
- Required Python libraries:
  - pandas
  - numpy
  - scikit-learn
  - librosa
  - h5py
  - tqdm
  - tensorflow

## Getting Started

### Steps to See Results

1. **Run `music_preprocessing.ipynb`**
   - **Description:** Processes data from the songs in the `Test_Songs` directory.
   
2. **Run `music_classifier.ipynb`**
   - **Description:** Builds the Neural Network model.
   - **Note:** This step takes approximately 6 minutes, depending on your PC's performance.
   
3. **Run `song_Info.ipynb`**
   - **Description:** Classifies songs into genres.

### Bonus: Generate Playlists

4. **Run `playlistGenerator.ipynb`**
   - **Description:** Creates a playlist based on the subset of music data used.
   - **Important:** This step requires additional data files (over 1GB) to function correctly.

## Data Download

### Before Running, Download These Files:

- [Music Data Files](https://drive.google.com/file/d/16oAAMEpAoxrEIFQXHoL-5TqrmtrsMQdb/view?usp=sharing)

**Note:** Please make sure you have downloaded and that you put these files in the right directory before running the `playlistGenerator.ipynb` notebook.

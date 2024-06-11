# An Attention-based, Context-aware Multimodal Fusion Method for Sarcasm Detection using Inter-modality Inconsistency
This repository contains the code implementation for the paper "An Attention-based, Context-aware Multimodal Fusion Method for Sarcasm Detection using Inter-modality Inconsistency". 
[Paper Link](https://www.sciencedirect.com/science/article/abs/pii/S0950705124000923)


## Introduction
Sarcasm detection is a challenging task, especially in the context of social media and meta universe applications where communication extends beyond text to include videos, images, and audio. Traditional methods relying solely on text data often fail to capture the emotional incongruities and subtleties inherent in sarcasm. This paper introduces a novel multimodal sarcasm detection method that processes multimodal data and focuses on modeling the emotional mismatch between different modalities.

<img src="./pic/contribution_in_a_nutshell.png" alt="contributions in a nutshell" width="650">



## Features
- Intermodal emotional inconsistency detection mechanism
- Contextual scenario inconsistency detection mechanism
- Cross-modal and segmented attention mechanism

## Dataset
The code implementation is evaluated on the MUStARD Extended dataset. Please refer to the paper for more details on the dataset.

## Usage
1. Clone the repository:
    ```
    git clone https://github.com/your-username/multimodal-sarcasm-detection.git
    ```
2. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Run the main script:
    ```
    python main.py
    ```

## Results
The experimental results on the MUStARD Extended dataset demonstrate the superiority of our approach compared to existing models. Please refer to the paper for detailed results and analysis.

## Citation
If you find this code implementation useful in your research, please consider citing the following paper:

> Li, Yangyang, et al. "An attention-based, context-aware multimodal fusion method for sarcasm detection using inter-modality inconsistency." Knowledge-Based Systems 287 (2024): 111457.

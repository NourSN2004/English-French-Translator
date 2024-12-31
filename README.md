# English-French-Translator
Done as an assignment for EECE 490 machine learning course
# English-to-French Machine Translation Using Seq2Seq

This repository contains a project on machine translation from English to French, developed as part of the **EECE 490: Introduction to Machine Learning** course. The project implements a Sequence-to-Sequence (Seq2Seq) model with LSTMs and explores tokenization techniques for effective translation.

## Overview
Machine translation is the process of converting text from one language to another using algorithms. This project demonstrates the use of Seq2Seq deep learning models for translating English sentences into French. It explores two main approaches for tokenization: using separate tokenizers for English and French, and a single shared tokenizer for both languages.

## Key Features
- **Dataset Preparation**: Preprocessing steps include tokenization, padding, and splitting data into training and testing sets.
- **Two Approaches**:
  - **Two Tokenizers**: Separate tokenizers for English and French.
  - **One Tokenizer**: A shared tokenizer for both languages.
- **Seq2Seq Model**:
  - Encoder-Decoder architecture with LSTMs.
  - Embedding layers for numerical representation of words.
  - Attention mechanisms for improved context handling.
- **Training and Evaluation**:
  - Model trained on English-French sentence pairs.
  - Validation and testing to assess model performance.

## Skills Demonstrated
- Natural Language Processing (NLP)
- Deep Learning with LSTM-based Seq2Seq models
- Tokenization and data preprocessing for language translation
- Model evaluation with metrics like accuracy and loss
- Architectural enhancements (attention mechanisms, normalization)

## Files
- `Machine_Translation.ipynb`: Main Jupyter Notebook containing code, explanations, and results.
- `README.md`: This document.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/machine-translation-seq2seq.git
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Machine_Translation.ipynb
   ```

## Usage
1. Open the notebook to explore the step-by-step implementation of the Seq2Seq model.
2. Train the model on the provided dataset and evaluate its performance.
3. Test the translation capability on new English sentences.

## Results
- The Seq2Seq model achieves significant translation accuracy.
- Examples of translations are provided to validate performance.
- Training and validation metrics are plotted for a comprehensive understanding of the model's behavior.

## Enhancements and Suggestions
- Incorporate **multi-head attention mechanisms** (as in Transformers) for improved context handling.
- Explore **hybrid architectures** combining CNNs and LSTMs for enhanced feature extraction.
- Apply **layer normalization** to improve training stability.
- Adapt tokenizers for different language pairs, considering specific linguistic features like morphology and script directionality.

## Consideration as a Project
This project is a strong addition to any portfolio, showcasing expertise in NLP, deep learning, and practical application of machine translation techniques.

## Acknowledgments
- Developed as part of the **EECE 490: Introduction to Machine Learning** course.
- The dataset used for translation tasks was sourced from public English-French sentence pairs.

## License
This project is licensed under the MIT License. See `LICENSE` for details.



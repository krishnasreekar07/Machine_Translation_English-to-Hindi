## Machine-Translation-English-to-Hindi

## NLP-DSCI-6004-01 Project

**Project Members:**
- Venkata P
- Ujwal Kothapally
- Indhiresh Reddy Linga Reddy

### Abstract

This repository contains the code and documentation for our NLP-DSCI-6004-01 project, focusing on an innovative approach to machine translation from English to Hindi. Leveraging state-of-the-art techniques in natural language processing (NLP) and deep learning, our model aims to address the challenges inherent in cross-language translation. The project provides a comprehensive overview, including motivation, technical details, training optimization, and thorough evaluation.

### Keywords

- Machine Translation
- English to Hindi
- Natural Language Processing
- Deep Learning
- Seq2Seq Architecture
- Attention
- Training Optimization
- BLEU Score
- Comparative Analysis

### Table of Contents

#### 1.Introduction:

- Overview of the project's focus on machine translation from English to Hindi.
Highlights the significance of breaking down language barriers using automated translation.
Related Work:

- Investigates the use of Seq2Seq models, starting with Sutskever et al.'s foundational work.
Explores advancements like attention mechanisms, Transformer models, transfer learning, and domain adaptation in English-to-Hindi translation.
Methodology:

#### 2.Data Collection:

- Manual scraping from the Yale website and translation using Google Translate.
Creation of a dataset comprising 128 samples for English-to-Hindi translation.

#### 3.Data Processing:

- Preprocessing involving the creation of dictionaries and necessary transformations.
Computation of vocabulary sizes for both English and Hindi.
#### 4.Custom Dataset Creation:

- Implementation of a custom dataset class for model training.
Illustrative example showcasing English and Hindi sentences with tensor representations.
#### 5.Data Loading:

- Splitting the dataset into training, testing, and validation subsets.
Implementation of PyTorch DataLoader with a collate function for efficient loading.
#### 6.Model:

- Utilization of the pretrained MarianMTModel with an encoder-decoder architecture.
Description of the model's components, including encoder layers, decoder layers, and positional embeddings.
Training and Fine Tuning Hyperparameters:

- Comprehensive training loop with functions for optimization and evaluation.
Fine-tuning experiments for learning rates and momentum rates.
#### 7.Simulation and Results:

- Plotted graphs illustrating training and validation loss over epochs for learning rate and momentum rate tuning.
Discussion of the BLEU score of 0.23 as an evaluation metric, indicating reasonable translation accuracy.
#### 8.Tokenization:

- Implementation of tokenization using the transformers library.
Explanation of key steps, including padding, truncation, and conversion to PyTorch tensors.
#### 9.Conclusion:

- Reflection on the project's contribution to English-to-Hindi translation and broader machine translation research.
Acknowledgment of challenges and proposed avenues for future work, emphasizing the understanding gained from pre-trained models


### Contribution Guidelines

If you'd like to contribute to the project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request, explaining the changes made and providing any necessary context.

### License

This project is licensed under the MIT License.

### Acknowledgments

We would like to acknowledge the contributions of the entire team and the supportive community.





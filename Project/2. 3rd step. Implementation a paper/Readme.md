# EDA: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Taskss (Wei and Zou 2019👨‍💻)
This repository contains the implementation of the Easy Data Augmentation (EDA) techniques, as described in the paper by Wei and Zou (2019), aimed at improving performance on text classification tasks.

### Overview 📝
The EDA techniques focus on generating more diverse training examples by applying simple transformations to existing text data. These techniques are especially helpful when working with small datasets and can enhance model performance by creating variations of the original text.

### EDA Techniques: 🔧
Synonym Replacement: Replaces words in the text with their synonyms.
Random Insertion: Inserts random words into the text.
Random Swap: Swaps the positions of words in the text.
Deletion: Deletes random words from the text to generate shorter variations.

You can read the full paper here: https://aclanthology.org/D19-1670/
https://github.com/jasonwei20/eda_nlp

The core implementation of the EDA techniques is adapted from the repository of Jason Wei's EDA implementation. The code provided here implements these augmentations and can be used to enhance the text classification tasks by generating more diverse training samples.

### Key Features ✨
Synonym Replacement: Replaces words with synonyms using a pre-trained word embedding model.
Random Insertion: Randomly inserts words from the vocabulary into the text.
Random Swap: Randomly swaps words within the text.
Deletion: Randomly deletes words to create shortened versions of the text.
These augmentation techniques are designed to be fast, simple, and effective, allowing you to generate varied training samples for improving your text classification models.

### License 📝
This repository is licensed under the MIT License. See the LICENSE file for more details.

### Citation 📚
If you use this code or reference these techniques in your work, please cite the following paper:
@inproceedings{wei-zou-2019-eda,
    title = "{EDA}: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks",
    author = "Wei, Jason and Zou, Kai",
    booktitle = "Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)",
    month = nov,
    year = "2019",
    address = "Hong Kong, China",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/D19-1670",
    pages = "6383--6389",
}

### Acknowledgment and Gratitude for the Pioneering Work on EDA Techniques 🙏🌹
I would like to express my sincere gratitude to the authors of the paper ‘EDA: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks’ for their valuable contributions to the field of text classification. Their innovative work has been a significant source of inspiration, and I am truly appreciative of the effort they put into developing such a useful methodology.

In this project, I have implemented their approach as a means of testing and practice. The results I obtained have been very promising, and I am thrilled with the outcomes. This implementation not only helped me gain deeper insights into the topic but also reinforced the effectiveness of their techniques in enhancing model performance on text classification tasks.

## Evolution of Text Data Augmentation Techniques: From Rule-Based to Deep Learning 🎯
1. Early Techniques (Pre-2015) - The Foundations
These techniques were simple and rule-based, commonly used in early projects:
Synonym Replacement: Replacing words with synonyms using WordNet.
Random Deletion: Randomly deleting words to create new samples.
Random Swap: Swapping words to create sentence variety.
Back Translation: Translating text to another language and back to the original.

3. Intermediate Techniques (2015-2020) - Deep Learning Introduction
This period saw the rise of deep learning models for more complex augmentations:
Contextual Augmentation: Replacing words using language models like BERT and GPT.
Word Embedding Noise Injection: Adding noise to word embeddings for data variety.
GANs for Text Augmentation: Using GANs to generate new text samples.
Adversarial Examples: Creating new samples for model robustness testing.

3. Advanced Techniques (2020-Present) - The Cutting Edge
These techniques leverage large models and reinforcement learning:
Pre-trained Language Models (PLMs): Using models like GPT, BERT, and T5 for text generation.
Prompt-based Data Augmentation: Guiding models with prompts to generate relevant data.
Reinforcement Learning-based Augmentation: Optimizing the data generation process with reinforcement learning.
Paraphrase Generation: Generating rewritten sentences while preserving meaning.
Current Noteworthy Techniques

Back Translation: Still popular, especially for low-resource data improvement.
Contextual Augmentation with BERT and GPT: Known for high accuracy and deep semantic understanding.
Prompt-based Augmentation: Valued for its flexibility in generating task-specific data.




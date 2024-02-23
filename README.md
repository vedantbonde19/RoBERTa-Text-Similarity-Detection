# RoBERTa-Text-Similarity-Detection

This project leverages the power of RoBERTa, a state-of-the-art language model, to identify similar text in English.

**Steps:**

1. **Data Preparation:**
    * Load and preprocess the Webis Crowd Paraphrase Corpus 2011 dataset. ✅
    * Tokenize text using `RobertaTokenizer`. ✨
    * Split data into training, validation, and test sets. 
    * Create PyTorch datasets for efficient training. 

2. **Model Fine-tuning:**
    * Download a pre-trained RoBERTa model from Hugging Face Transformers. 
    * Fine-tune the model using the `Trainer` class with specified parameters. ⚙️
    * Adjust hyperparameters like epochs, batch size, and learning rate. 

3. **Model Evaluation:**
    * Evaluate the trained model on the test set. 
    * Calculate accuracy and generate a confusion matrix. 
    * Visualize the confusion matrix using Matplotlib (optional). 

**Technologies:**

* Hugging Face Transformers 
* PyTorch 
* scikit-learn
* Matplotlib

**Ready to explore?**

Clone this repository and follow the instructions in the included notebook to embark on your text similarity detection journey!




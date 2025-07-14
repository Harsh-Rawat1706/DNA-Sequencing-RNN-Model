# DNA Sequencing RNN Model
This project focuses on classifying DNA sequences from humans, dogs, and chimpanzees using a hybrid deep learning architecture that combines a 1D Convolutional Neural Network (CNN) and a Bidirectional GRU (Gated Recurrent Unit). The goal is to build a robust model that can accurately analyze DNA sequences and predict the species they belong to.

## 🔬 Potential Applications
* Genomic Research: Identify species based on genetic data.

* Medical Diagnostics: Detect genetic disorders by analyzing DNA sequences.

* Bioinformatics: Classify DNA sequences from different organisms.

* Forensic Science: Identify species from DNA samples in crime investigations.

## 🧭 Project Workflow
**Step 1: Import Required Libraries**
Essential libraries used in this project include:

* NumPy, Pandas – Data manipulation

* Matplotlib, Seaborn – Visualization

* Scikit-learn (sklearn) – Data preprocessing and evaluation

* TensorFlow, Keras, SciKeras – Deep learning model creation and training
<img width="1088" height="356" alt="Screenshot 2025-07-14 134655" src="https://github.com/user-attachments/assets/26d3a2f9-d6a9-47cc-9580-43834f73addc" />

**Step 2: Data Loading & Preprocessing**
* Loaded DNA sequence dataset using the os library.

* Performed data preprocessing including:

* Label encoding of species

* Reshaping sequences for neural network input

Splitting the dataset into training and testing sets
<img width="1136" height="556" alt="Screenshot 2025-07-14 135101" src="https://github.com/user-attachments/assets/c3d5fa26-0d58-4fb4-96ca-7a91fd817a2b" />

**Step 3: Model Building & Training**
* Constructed a hybrid model using:

   * 1D CNN for extracting spatial patterns in DNA sequences

   * Bidirectional GRU for capturing long-range dependencies in both directions

* Trained the model using the preprocessed dataset
<img width="1154" height="617" alt="Screenshot 2025-07-14 135256" src="https://github.com/user-attachments/assets/db327a2a-5b72-4957-9296-3a68ac044e87" />

**Step 4: Model Evaluation**
* Visualized:

    * Training vs. Validation Loss

    * Training vs. Validation Accuracy

* Evaluated the model’s learning progress and potential overfitting/underfitting
<img width="564" height="408" alt="Screenshot 2025-07-14 135528" src="https://github.com/user-attachments/assets/21312d51-7f91-492e-af2a-6a76cb3f80bc" />
<img width="559" height="411" alt="Screenshot 2025-07-14 135554" src="https://github.com/user-attachments/assets/8811baa8-8d99-41d9-9693-74db8e6a7bc0" />

**Step 5: Testing & Prediction**
* Performed testing on unseen DNA sequences

* Made predictions and evaluated the model’s generalization ability
<img width="590" height="431" alt="Screenshot 2025-07-14 135736" src="https://github.com/user-attachments/assets/3ee77932-a5ee-4772-a052-340533905230" />

## 📊 Confusion Matrix & Metrics
* To better understand the model’s performance, we use classification metrics:

* Precision: Measures how many of the predicted positive samples are actually correct.

* Recall: Measures how many actual positive samples were correctly predicted.

* F1-Score: The harmonic mean of precision and recall — ideal for imbalanced datasets.

* Support: The number of actual samples per class in the test set.
​
 

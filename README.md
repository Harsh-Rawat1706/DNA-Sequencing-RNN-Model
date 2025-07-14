# DNA-Sequencing-RNN-Model
This project classifies DNA sequences from humans, dogs, and chimpanzees using a 1D Convolutional Neural Network (CNN) and a Bidirectional GRU (Gated Recurrent Unit). The goal is to build a model that can analyze DNA sequences and predict the species they belong to.

**Potential Applications**

*   **Genomic Research:** Identify species based on genetic data.
*   **Medical Diagnostics:** Detect genetic disorders by analyzing DNA sequences.
*   **Bioinformatics:** Classify DNA sequences from different organisms.
*   **Forensic Science:** Identify species from DNA samples in crime investigations.

**steps use in this project are:**
* **Step1** = Import all important libraries.
  In  this project i use libraries like numpy , pandas , matplotlib , sklearn , tensorflow , keras and scikeras. 
<img width="1088" height="356" alt="Screenshot 2025-07-14 134655" src="https://github.com/user-attachments/assets/26d3a2f9-d6a9-47cc-9580-43834f73addc" />

* **Step2** = Data loading and preprocessing. for data loading i use os library so i load the data set by giving the path.
  after loading data i perform preprocessing like encoding , reshaping and split of data.
<img width="1136" height="556" alt="Screenshot 2025-07-14 135101" src="https://github.com/user-attachments/assets/c3d5fa26-0d58-4fb4-96ca-7a91fd817a2b" />

* **Step3** = Create Model and run it on training data.
<img width="1154" height="617" alt="Screenshot 2025-07-14 135256" src="https://github.com/user-attachments/assets/db327a2a-5b72-4957-9296-3a68ac044e87" />

* **Step4** = Analyse training loss and validation loss , training accuracy and validation accuracy.
<img width="564" height="408" alt="Screenshot 2025-07-14 135528" src="https://github.com/user-attachments/assets/21312d51-7f91-492e-af2a-6a76cb3f80bc" />
<img width="559" height="411" alt="Screenshot 2025-07-14 135554" src="https://github.com/user-attachments/assets/8811baa8-8d99-41d9-9693-74db8e6a7bc0" />

* **Step5** = Model Testing and Prediction.
<img width="590" height="431" alt="Screenshot 2025-07-14 135736" src="https://github.com/user-attachments/assets/3ee77932-a5ee-4772-a052-340533905230" />

**All about Confusion matrix**
1. Precision
Measures how many of the predicted positive instances were actually correct.

2. Recall
Measures how many of the actual positive instances were correctly identified.

3. F1-Score
The harmonic mean of precision and recall. Useful when you want a balance between precision and recall.
​
4. Support
The number of actual instances in the dataset for each class.
 

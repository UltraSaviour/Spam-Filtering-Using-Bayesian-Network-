## Spam Filtering Using Bayesian Networks  

This project demonstrates a **spam filtering system** using **Bayesian Networks** to classify SMS messages as either **ham (non-spam)** or **spam**. The model leverages probabilistic reasoning to detect patterns in text, providing an effective way to identify unwanted messages.  

### Key Features  
- **Bayesian Network Model:** Establishes conditional dependencies between the message label and word occurrences.  
- **TF-IDF Vectorization:** Converts the text data into numerical features to represent the significance of words.  
- **Binary Feature Transformation:** Simplifies TF-IDF features by detecting the presence or absence of words, making them suitable for Bayesian modeling.  
- **Training & Evaluation:** Trained using **Maximum Likelihood Estimation**, with performance evaluated through metrics like precision, recall, and F1-score.  

### Dataset  
The dataset contains 5,572 SMS messages labeled as either **spam** or **ham**. The project focuses on two columns:
- **Label:** The target class (spam or ham)  
- **Message:** The content of the SMS  

### Results  
After training, the model generates a **classification report** with key metrics, including precision, recall, F1-score, and accuracy. This helps assess the effectiveness of the Bayesian network in differentiating between spam and non-spam messages.  

This project offers a practical implementation of Bayesian networks for text classification, providing a foundation for further exploration in **probabilistic machine learning**.

# NLP
This repo consists of few exercises, projects, tasks related to NLP, Transformer models, ML. Check it out.

# Tweet_Emotion_Recognition
## Project Overview

- The dataset used for training and evaluation consists of labeled tweets, where each tweet is associated with a specific emotion.
- The project involves text preprocessing, including tokenization and padding, to prepare the data for input into the neural network.
- The Sequential model architecture is employed for sentiment classification.
- The model is trained using the labeled tweet data and evaluated on a validation set.
- The trained model is then used to predict the emotions in unseen tweets.

## Problems Encountered and Further Improvements
While achieving an accuracy of over 89%, the model struggles to make accurate predictions due to imbalanced class distribution. Classes like "sadness" and "joy" are oversampled, affecting prediction accuracy for minority classes. Balancing techniques, such as oversampling or weighted loss, are needed to improve predictions across all classes.
After some research:
Using SMOTE balances classes, enhancing model predictions, ensuring accuracy and reliability across all categories.


# Fitting_texts 
This task invloves comparing two sheets, Evaluating them by extracting the answers from one sheet using OCR and fitting them in empty spaces sheet.
Used: Segmentation, extracting contours, OCR.

# GetPrescription (project undergoing)
This task focuses on extracting medicine names and its corresponding frequency mentioned in prescription image using OCR. This info is stored in final_info function which returns dictionary of medicine names and frequency.  
Requirements: (Image has specified format) 

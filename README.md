# Music-Genre-Classification
This project is based on music genre classification using neural network model.


Overview: 
This project is a deep learning-based application to classify audio files into their respective music genres. It uses audio feature extraction, data augmentation, and machine learning techniques to achieve accurate predictions. The system processes audio files to extract features like MFCCs, chroma, and spectral attributes and applies data augmentation techniques, such as noise addition, time-stretching, and pitch shifting, to enhance model performance and robustness.


Dataset: 
The dataset comprises audio files categorized into ten music genres: blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae, and rock. Each file is processed to extract meaningful features, which are then used for training and testing the model. Data augmentation further enhances the dataset by creating varied versions of the audio files.


Model Architecture: 
Initially, various models like XGBoost and feed-forward neural networks were explored for classification, both with and without data augmentation. However, the accuracy achieved by these models were below 70%. By having data augmentation techniques, the results significantly improved, achieving accuracy above 90%. 
After experimenting the model with all combination of techniques to increase accuracy nad reduce loss, the current deep learning model uses only 2 layers, built with TensorFlow/Keras, batch normalization, and dropout layers.


Results: 
With data augmentation, the model achieves accuracy around 90%. It provides comprehensive evaluation metrics, including confusion matrices and classification reports, which are reliable in genre prediction. The approach highlights the importance of data augmentation in improving model performance.

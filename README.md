This project focuses on building a machine learning model to classify news articles based on their textual features, including the author, title, and content. After cleaning the dataset by removing irrelevant columns and handling missing values, I encountered a major challenge: extreme class imbalance. For example, the fake category contained only 19 samples, while the conspiracy category had over 10,000.

To address this issue, I applied both undersampling (for dominant classes) and oversampling using SMOTE (to boost minority classes). The chosen model was a Random Forest classifier, which achieved strong performance on the classes with abundant data but struggled to accurately predict underrepresented categories.

Despite these challenges, the project was an important step forward in my machine learning journey. It allowed me to work with real-world text data, handle imbalanced datasets, and apply more advanced ML techniques, all of which significantly improved my skills and understanding.
The link to the csv file i worked on  : https://drive.google.com/file/d/1l8sgvKpV2x4u8jr-VFnkBki3OJj3UN5J/view (the file was too large to upload here even after the data cleaning)

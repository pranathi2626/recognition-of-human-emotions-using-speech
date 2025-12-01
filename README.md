This project identifies human emotions from speech audio using machine learning.
Audio files are first loaded, cleaned, and normalized for consistency.
Key sound features like MFCCs, chroma, ZCR, and spectral contrast are extracted.
All extracted features are combined into a structured dataset.
Each audio sample is labelled with its corresponding emotion class.
The dataset is split into training and testing sets for model evaluation.
A classifier such as SVM / Random Forest is trained to learn emotion patterns.
The trained model predicts emotions from new, unseen audio clips.

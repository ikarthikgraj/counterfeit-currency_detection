# counterfeit-currency_detection-MATLAB
### MATLAB code for Fake Indian Currency Detection.

## Features:

Preprocessing: Resizes and converts the input image to grayscale.

Segmentation: Uses masking and morphological operations to isolate relevant areas of the note.

Feature Extraction: Extracts texture-based features like Contrast, Energy, Homogeneity, and statistical measures (Mean, Entropy, RMS, etc.) using GLCM (Gray-Level Co-occurrence Matrix).

Classification: Employs SVM with an RBF kernel to classify notes as genuine or fake.

Interactive Testing: Accepts user-uploaded test images and displays the classification result.

## Practical Applications:
1. Financial security in ATMs or cash counters.

2. Real-time fake currency detection for retail and banking sectors.

Applicable to any currency depending upon the currency in your dataset

Support Vector Machine classification is done on these texture features.
It will classify whether the note is genuine or fake.

Image segmentation done using Color thresholder app.

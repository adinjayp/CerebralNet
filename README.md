# CerebralNet: A Deep Learning Approach to Alzheimer Detection from MRI

## Authors
- **Adinjay Phadkule**, Northeastern University (phadkule.a@northeastern.edu)
- **Shaswat Sinha**, Northeastern University (sinha.sha@northeastern.edu)
- **Raghavi Dube**, Northeastern University (dube.ra@northeastern.edu)

## Abstract
Alzheimer's disease (AD) is a debilitating neurodegenerative disorder characterized by progressive cognitive decline. Early and accurate diagnosis of AD is crucial for timely intervention and management. This research focuses on developing a deep learning model for AD classification using magnetic resonance imaging (MRI) scans. The study utilizes a dataset comprising MRI images from patients with varying degrees of AD severity. Preprocessing techniques, including image resizing and normalization, are applied to standardize the input data. A convolutional neural network (CNN) architecture is designed and trained on the preprocessed images, with evaluation conducted using metrics such as accuracy, loss, confusion matrix, and classification report. The results demonstrate the effectiveness of the proposed model in accurately classifying AD severity levels, contributing to the advancement of automated AD diagnosis and laying the foundation for further exploration in medical image analysis and neuroimaging.

## Keywords
Alzheimer’s disease, CNN, ReLu, MRI, SoftMax, Adam, cross entropy, EfficientNetB0

## Introduction
Alzheimer's disease (AD) stands as one of the most challenging public health issues, affecting millions worldwide. This research aims to improve diagnostic accuracy and patient outcomes by leveraging deep learning techniques to analyze MRI scans for early AD detection.

## Dataset
The dataset comprises MRI images from individuals at different stages of AD progression. It is divided into training, validation, and test sets:
- **Training set**: 8960 MRI images
- **Validation set**: 1920 MRI images
- **Test set**: 1920 MRI images

## Methodology
### Data Preprocessing
- **Rescaling**: Images resized to 176x176 pixels.
- **Normalization**: Pixel intensity values scaled to [0, 1].
- **Data Augmentation**: Techniques applied to enhance model robustness and prevent overfitting.

### Model Architecture
Several CNN architectures were evaluated, including EfficientNetB0. The best-performing models were trained using the Adam optimizer and evaluated on the test dataset using metrics such as accuracy, loss, confusion matrix, and classification report.

### Training and Evaluation
The models were trained with early stopping to prevent overfitting and evaluated on the test dataset. The best models demonstrated high accuracy and low loss, with detailed performance metrics provided in the research paper.

## Results
The proposed CNN models showed high accuracy in classifying AD severity levels, significantly contributing to the field of automated AD diagnosis.

## Conclusion
This research showcases the potential of deep learning techniques in improving the early detection and classification of Alzheimer's disease from MRI scans. The models developed in this study lay the groundwork for further advancements in medical image analysis and neuroimaging.

## How to Use This Repository
1. **Clone the repository**: `git clone https://github.com/your-username/CerebralNet.git`
2. **Navigate to the project directory**: `cd CerebralNet`
3. **Install dependencies**: 
    ```sh
    pip install -r requirements.txt
    ```
4. **Run the preprocessing script**: 
    ```sh
    python preprocess.py
    ```
5. **Train the model**: 
    ```sh
    python train.py
    ```
6. **Evaluate the model**: 
    ```sh
    python evaluate.py
    ```

## Contact
For any questions or inquiries, please contact:
- Adinjay Phadkule (phadkule.a@northeastern.edu)
- Shaswat Sinha (sinha.sha@northeastern.edu)
- Raghavi Dube (dube.ra@northeastern.edu)

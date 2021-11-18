## A Fast and Efficient CNN Model for B-ALL (B-Cell Acute Lymphocytic Leukemia) Diagnosis and its Subtypes Classification using Peripheral Blood Smear Images

The definitive diagnosis of acute lymphoblastic leukemia (ALL), as a highly prevalent cancer, requires invasive, expensive, and time-consuming diagnostic tests. ALL diagnosis using peripheral blood smear (PBS) images plays a vital role in the initial screening of cancer from non-cancer cases. The examination of these PBS images by laboratory users is riddled with problems such as diagnostic error because the nonspecific nature of ALL signs and symptoms often leads to misdiagnosis. Herein, a model based on deep convolutional neural networks (CNNs) is proposed to detect ALL from hematogone cases and then determine ALL subtypes. In this paper, we build a publicly available ALL data set, comprised 3562 PBS images from 89 patients suspected of ALL, including 25 healthy individuals with a benign diagnosis (hematogone) and 64 patients with a definitive diagnosis of ALL subtypes. After color thresholding-based segmentation in the HSV color space by designing a two-channel network, 10 well-known CNN architectures (EfficientNet, MobileNetV3, VGG-19, Xception, InceptionV3, ResNet50V2, VGG-16, NASNetLarge, InceptionResNetV2, and DenseNet201) were employed for feature extraction of different data classes. Of these 10 models, DenseNet201 achieved the best performance in diagnosis and classification. Finally, a model was developed and proposed based on this state-of-the-art technology. This deep learning-based model attained an accuracy, sensitivity, and specificity of 99.85, 99.52, and 99.89%, respectively. The proposed method may help to distinguish ALL from benign cases. This model is also able to assist hematologists and laboratory personnel in diagnosing ALL subtypes and thus determining the treatment protocol associated with these subtypes.

<h1 align="center">
 <a href="https://github.com/MehradAria/ALL-Subtype-Classification"><img src="https://github.com/MehradAria/ALL-Subtype-Classification/blob/main/Model.png?raw=true" alt="A fast and efficient CNN model for B-ALL diagnosis and its subtypes classification using peripheral blood smear images"></a>
</h1>

Public Dataset: [Acute Lymphoblastic Leukemia (ALL) image dataset](https://www.kaggle.com/mehradaria/leukemia)

Research article: [A fast and efficient CNN model for B-ALL diagnosis and its subtypes classification using peripheral blood smear images](https://doi.org/10.1002/int.22753)

### Citation
Please kindly cite as:

    Ghaderzadeh M, Aria M, Hosseini A, Asadi F, Bashash D, Abolghasemi H.
    "A fast and efficient CNN model for B-ALL diagnosis and its subtypes classification using peripheral blood smear images" 
    Int J Intell Syst. 2021;1‐21.
    URL: https://www.jmir.org/2021/4/e27468
    DOI: 10.1002/int.22753

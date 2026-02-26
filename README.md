# Computer-vision
In this repository there are three transfer learning models based on MobileNetV3. Each model was trainned with two different datasets and compared with metrics such as trainning time, model size, number of parameters, Precision, recall and F1-score. The first model employs a fully connected layer as the classifier, while the second incorporates three additional convolutional layers on top of the base architecture. Both approaches were trained using pre-trained weights. Performance was assessed in terms of training time, accuracy, precision, recall, F1-score, model size, and parameter count. The results revealed no substantial differences across these metrics. Nevertheless, the study recommends the MobileNetV3-Small model with the added convolutional layers, as it demonstrated greater robustness when trained on a slightly unbalanced dataset. 

The datasets were obtained from the links:
Wheat dataset : RADOWAN, M. I. R. and AYON, R. A., 2025. Disease Dataset of Wheat: Original, Augmented, and Balanced for Deep Learning. Mendeley Data [online]. V1. Available from: https://doi.org/10.17632/5gc7hwydwg.1 
Coffe dataset: CHELANGAT, S., ANIRWOTH, R., MAYANJA, K. N., SSERWADDA, A., 2025. A Machine Learning Dataset for Classification of Common Coffee Leaf Diseases in Uganda. Mendeley Data [online], V1, Available from: https://doi.org/10.17632/k36wnd6knb.1 Accessed 19 September 2025].



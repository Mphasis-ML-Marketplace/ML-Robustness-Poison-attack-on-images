# ML Robustness: Poison attack on images
The solution measures ML robustness towards induction of predesigned noises in the dataset while training image classifier.

## Product Overview
In posioning attack, attacker designed noises- such as image objects, variables value changes, label changes- are induced to the training data to test fidelity and robustness of model training. The model trained on such adverse dataset could systematically result in model vulnerability issues.  For example, in anomaly detection model the anomalous training samples fed with back door object (possibly, signature pattern) and modify the label to non-anomalous. This solution measures effect of adversial backdoor attacks during training on model robustness and performance.

## Product Highlight 

* Model Robustness is the immunity of ML model towards any intended attack to alter its performance. Poisoning attacks are intended to degrade the performance of image classifier by injecting adverse/modified data samples to training phase. This solution identifies the robustness of image classifier by performing a Black box poisoning attack. Inputing a back door- which is an attacker designed noise- to the training data samples typically results in out come of trained model to drift to the existence of back door, leading to compromise of model security.
* The solution requires a labeled Image (original) training dataset and a pre-trained Keras model with structural information. The user can define the Back door pattern and select the class labels and sample of original training data to impute. The Keras model is trained with imputed (attacked) data. The number of images of selected class label to perturb can be controlled by the user. The difference in accuracies of the target model over the samples with attacked class label to those samples with non-attacked class labels give the robustness of the model to poison attack.  
* PACE - ML is Mphasis Framework and Methodology for end-to-end machine learning development and deployment. PACE-ML enables organizations to improve the quality & reliability of the machine learning solutions in production and helps automate, scale, and monitor them. Need customized Machine Learning and Deep Learning solutions? Get in touch!

## Amazon Marketplace Link
The product can be found [here]().

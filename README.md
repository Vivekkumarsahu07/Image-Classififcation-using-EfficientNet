# Image-Classification-using-EfficientNet
-> This project demonstrates the application of transfer learning for image classification using a pre-trained model. It involves leveraging the knowledge gained by a model trained on a large dataset (such as ImageNet) and applying it to a new, task of image classification.

## Steps Covered:
-> Dataset Preparation:
~ The dataset consists of images belonging to three classes: earphone, headphone, and phones. Images are loaded, resized, and preprocessed.
-> Model Building:
~ The pre-trained EfficientNetB0 model, pre-trained on ImageNet, is utilized as a feature extractor.
~ The classification head of the pre-trained model is removed, and a new classification layer is added.
~ Top layers are frozen, and only the new classification layer is trained on the new dataset.
-> Training:
~ The model is trained on the prepared dataset with a relatively large learning rate for a few epochs.
~ Model performance is evaluated using accuracy metrics.
-> Evaluation:
~ Model performance is evaluated on a separate test set to assess its accuracy.
-> Prediction:
~ Finally, the trained model is used to make predictions on unseen images.

## Technologies Used:
-> Python
-> TensorFlow
-> EfficientNetB0
-> OpenCV

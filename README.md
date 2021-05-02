# Document Structure Classification for Information-Retrieval

[Computer Vision] For OCR tasks, document structure (e.g. email, letter, memo, etc.) may provide critical insight and helps to improve overall quality of the OCR task. With this use case in mind, I used the RVL-CDIP dataset to predict the structure of a document given a scanned image.

- Trained deep learning model using EfficientNet B3 architecture
- Achieved 91.17 accuracy using a single model (12 Million parameters)
- The state of the art accuracy is 92.2 which uses a stack of 5 VGG16 networks ( 134.2 * 5 = 671 Million parameters)

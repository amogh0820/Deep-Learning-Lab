Lab 4: Object Detection

Aim
To implement object detection using pre-trained deep learning models and display detected objects with bounding boxes, labels, and confidence scores.

Programs
1. **EfficientDet:** Uses a pre-trained EfficientDet-D0 model to detect objects in an image in a single stage.
2. **VGG16 + Selective Search:** Generates candidate image regions using Selective Search and classifies them using a pre-trained VGG16 model. Non-Maximum Suppression removes overlapping detections.

Dataset Used
- **Program 1:** COCO dataset, containing 80 object categories.
- **Program 2:** ImageNet, containing 1,000 classification categories.

Both programs accept a user-uploaded image as input.

Results
EfficientDet detects objects and displays their labels, confidence scores, and bounding boxes. VGG16 classifies proposed image regions and displays confident predictions after removing overlapping boxes. Detection accuracy depends on the image and the model's predictions.
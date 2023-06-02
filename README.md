# AI Demo for Bottlenose Cameras

Please see the setup instructions [here](https://docs.labforge.ca/docs/bottlenose-file-utility).

| **No.** | **Model**                                             | **Type** | **Description**                                                                    |
|-----|---------------------------------------------------------|------------|--------------------------------------------------------------------------------------|
| 1   | [Tomato-tiny](models/tomato-tiny_1_416_416_3.tar)       | Detector   | A vegetable and fruit detector trained on the Yolov3-tiny model                      |
| 2   | [Tomato-full](models/tomato-full_1_416_416_3.tar)       | Detector   | A vegetable and fruit detector trained on the full Yolov3 model                      |
| 3   | [Yolov3-tiny](models/yolov3-tiny_1_416_416_3.tar)       | Detector   | The generic Yolov3-tiny detector trained on the COCO datasets to recognize 80 classes |
| 4   | [Yolov3](models/yolov3_1_416_416_3.tar)                 | Detector   | The generic Yolov3 detector trained on the COCO datasets to recognize 80 classes     |
| 5   | [SSD-Mobilenetv2](models/mobilenet-ssd_1_3_300_300.tar) | Detector   | A generic SSD-Mobilenetv2 trained on the VOC datasets with 20 classes                |
| 6   | [ResNet50](models/resnet50_1_3_224_224.tar)             | Classifier | ResNet50 classifier trained on Imagenet with 1000 classes                            |

## Exp Results on Potsdam

|      | Code                   | Datasets                | mIoU（potsdam） | OA   |
| ---- | ---------------------- | ----------------------- | --------------- | ---- |
| 1    | mnist数字识别代码      | mnist数据集             | /               | /    |
| 2    | ResNet                 | Potsdam                 |                 |      |
| 3    | FCN（Based on VGG_16） | VOC、Potsdam            | 52.5            | 73.7 |
| 4    | FCN（Based on ResNet） | VOC、Potsdam            | 67.6            | 84.8 |
| 5    | SegNet                 | Cityscapes、Potsdam     | 62.5            | 81.4 |
| 6    | PSPNet                 | VOC                     | /               | /    |
| 7    | UNet                   | 脑血管数据集、Potsdam   | 61.9            | 80.1 |
| 8    | DlinkNet               | DeepGlobe、Potsdam      | 71.7            | 87   |
| 9    | FastFCN                | Potsdam                 | 68.3            | 85   |
| 10   | SE-DlinkNet            | DeepGlobe、Potsdam      | 72.1            | 87.1 |
| 11   | SE-FastFCN             | Potsdam                 | 63.8            | 88.7 |
| 12   | SETR                   | Potsdam                 | /               | /    |
| 13   | Segmenter              | Pascal Context、Potsdam | 72.3            | 87.8 |
| 14   | SegFormer              | Cityscapes、Potsdam     | 73              | 88.4 |
| 15   | Swin Transformer       | Potsdam                 | 76.8            | 88.8 |
| 16   | MaskFormer             | Potsdam                 | 74.9            | 88.9 |
| 17   | BeiT                   | Potsdam                 | 75.5            | 89.2 |
| 18   | Swin V2                | Potsdam                 | 72.6            | 86.3 |
| 19   | Vit-Adapter            | Potsdam                 | 73              | 87.9 |
| 20   | SeMask                 | Potsdam                 |                 |      |
| 22   | Mask2Former            | Potsdam                 | 76.8            | 87.8 |
| 23   | BeiTv2                 | Potsdam                 |                 |      |
| 23   | SegNeXt                | Potsdam                 | 80.01           | 90.9 |

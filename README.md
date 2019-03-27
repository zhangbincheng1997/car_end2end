# car_end2end

## Nvidia Model
![alt text](docs/nvidia.jpg)

效果好

|  Model  |  Loss  |  Val Loss  |  Map  |
|  -----  |  :----:  |  :----:  |  :----:  |
| train         | ![alt text](train/loss.svg) | ![alt text](train/val_loss.svg) | ![alt text](train/overlay.gif) |
| train-dropout | ![alt text](train-dropout/loss.svg) | ![alt text](train-dropout/val_loss.svg) | ![alt text](train-dropout/overlay.gif) |

## Fine Tune
![alt text](docs/vgg.jpg)

过拟合

|  Model  |  Loss  |  Val Loss  |  Map  |
|  -----  |  :----:  |  :----:  |  :----:  |
| train-vgg16 | ![alt text](train-vgg16/loss.svg) | ![alt text](train-vgg16/val_loss.svg) | ![alt text](train-vgg16/overlay.gif) |
| train-vgg19 | ![alt text](train-vgg19/loss.svg) | ![alt text](train-vgg19/val_loss.svg) | ![alt text](train-vgg19/overlay.gif) |

## 错误场景
|  Type  |  Image  |
|  -----  |  :----:  |
| 1.切着跑道 | ![alt text](docs/1.切着跑道.png) |
| 2.压到跑道 | ![alt text](docs/2.压到跑道.png) |
| 3.卡在跑道 | ![alt text](docs/3.卡在跑道.png) |
| 4.冲出跑道 | ![alt text](docs/4.冲出跑道.png) |
| 5.路线错误 | ![alt text](docs/5.路线错误.png) |


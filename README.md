# car_end2end

## Nvidia Model
![alt text](docs/nvidia.jpg)

稳如狗......

|  Model  |  Loss  |  Val Loss  |  Map  |
|  -----  |  :----:  |  :----:  |  :----:  |
| train-noraml  | <img src="train-normal/loss.svg" width=256 height=256 />  | <img src="train-normal/val_loss.svg" width=256 height=256 />  | ![alt text](train-normal/overlay.gif)  |
| train-dropout | <img src="train-dropout/loss.svg" width=256 height=256 /> | <img src="train-dropout/val_loss.svg" width=256 height=256 /> | ![alt text](train-dropout/overlay.gif) |

## Fine Tune
![alt text](docs/vgg.jpg)

存在过拟合现象......

|  Model  |  Loss  |  Val Loss  |  Map  |
|  -----  |  :----:  |  :----:  |  :----:  |
| train-vgg16 | <img src="train-vgg16/loss.svg" width=256 height=256 /> | <img src="train-vgg16/val_loss.svg" width=256 height=256 /> | ![alt text](train-vgg16/overlay.gif) |
| train-vgg19 | <img src="train-vgg19/loss.svg" width=256 height=256 /> | <img src="train-vgg19/val_loss.svg" width=256 height=256 /> | ![alt text](train-vgg19/overlay.gif) |

## 失败场景
|  Type  |  Image  |
|  -----  |  :----:  |
| 切着跑道 | ![alt text](docs/1.切着跑道.png) |
| 压到跑道 | ![alt text](docs/2.压到跑道.png) |
| 卡在跑道 | ![alt text](docs/3.卡在跑道.png) |
| 冲出跑道 | ![alt text](docs/4.冲出跑道.png) |
| 路线错误 | ![alt text](docs/5.路线错误.png) |


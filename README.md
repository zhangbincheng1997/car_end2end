# car_end2end

## Nvidia Model
![alt text](nvidia.jpg)
|  Model  |  Train Loss  |  Val Loss  |  Loss  |  Map  |
|  -----  |  :-----:  |  :----:  |  :----:  |  :----:  |
| train          |  0.0328  |  0.0347  |  ![alt text](train/loss.jpg)  |  ![alt text](train/overlay.gif)  |
| train-dropout  |  0.0121  |  0.0305  |  ![alt text](train-dropout/loss.jpg)  |  ![alt text](train-dropout/overlay.gif)  |
| train-bn       |  0.0196  |  0.0364  |  ![alt text](train-bn/loss.jpg)  |  ![alt text](train-db/overlay.gif)  |

## Fine Tune
![alt text](vgg.jpg)
| train-vgg16    |  0.0386  |  0.0306  |  ![alt text](train-vgg16/loss.jpg)  |  ![alt text](train-vgg16/overlay.gif)  |
| train-vgg19    |  0.0326  |  0.0313  |  ![alt text](train-vgg19/loss.jpg)  |  ![alt text](train-vgg19/overlay.gif)  |

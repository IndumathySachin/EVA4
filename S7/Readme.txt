Parameters
Requirement already satisfied: torchsummary in /usr/local/lib/python3.6/dist-packages (1.5.1)
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1           [-1, 16, 32, 32]             432
              ReLU-2           [-1, 16, 32, 32]               0
       BatchNorm2d-3           [-1, 16, 32, 32]              32
           Dropout-4           [-1, 16, 32, 32]               0
            Conv2d-5           [-1, 16, 32, 32]           2,304
              ReLU-6           [-1, 16, 32, 32]               0
       BatchNorm2d-7           [-1, 16, 32, 32]              32
           Dropout-8           [-1, 16, 32, 32]               0
         MaxPool2d-9           [-1, 16, 16, 16]               0
           Conv2d-10           [-1, 32, 16, 16]           4,608
             ReLU-11           [-1, 32, 16, 16]               0
      BatchNorm2d-12           [-1, 32, 16, 16]              64
          Dropout-13           [-1, 32, 16, 16]               0
        MaxPool2d-14             [-1, 32, 8, 8]               0
           Conv2d-15             [-1, 64, 6, 6]             576
             ReLU-16             [-1, 64, 6, 6]               0
      BatchNorm2d-17             [-1, 64, 6, 6]             128
          Dropout-18             [-1, 64, 6, 6]               0
        MaxPool2d-19             [-1, 64, 3, 3]               0
           Conv2d-20            [-1, 128, 3, 3]          73,728
             ReLU-21            [-1, 128, 3, 3]               0
      BatchNorm2d-22            [-1, 128, 3, 3]             256
          Dropout-23            [-1, 128, 3, 3]               0
        AvgPool2d-24            [-1, 128, 1, 1]               0
           Conv2d-25             [-1, 10, 1, 1]           1,280
================================================================
Total params: 83,440
Trainable params: 83,440
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.01
Forward/backward pass size (MB): 1.41
Params size (MB): 0.32
Estimated Total Size (MB): 1.74
----------------------------------------------------------------

Training loss:
[1,  2000] loss: 2.304
[1,  4000] loss: 2.307
[1,  6000] loss: 2.306
[1,  8000] loss: 2.305
[1, 10000] loss: 2.305
[1, 12000] loss: 2.308
[2,  2000] loss: 2.304
[2,  4000] loss: 2.307
[2,  6000] loss: 2.309
[2,  8000] loss: 2.305
[2, 10000] loss: 2.304
[2, 12000] loss: 2.310
Finished Training

Test accuracy:
Accuracy of the network on the 10000 test images: 11.1 %
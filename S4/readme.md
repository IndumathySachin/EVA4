Assignment 4

Parameters:
================================================================
Total params: 18,722
Trainable params: 18,722
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.00
Forward/backward pass size (MB): 0.24
Params size (MB): 0.07
Estimated Total Size (MB): 0.32
----------------------------------------------------------------

Model:
        self.conv1 = nn.Conv2d(1, 8, 3, padding=1) #input -? OUtput? RF
        self.conv2 = nn.Conv2d(8, 8, 3, padding=1)
        self.pool1 = nn.MaxPool2d(2, 2)
        self.conv3 = nn.Conv2d(8, 16, 3, padding=1)
        self.conv4 = nn.Conv2d(16, 16, 3, padding=1)
        self.pool2 = nn.MaxPool2d(2, 2)
        self.conv5 = nn.Conv2d(16, 32, 3)
        self.conv6 = nn.Conv2d(32, 32, 3)
        self.conv7 = nn.Conv2d(32, 10, 3 )
        self.batch8 = nn.BatchNorm2d(8)
        self.batch16 = nn.BatchNorm2d(16)
        self.batch32 = nn.BatchNorm2d(32)
        self.drop =  nn.Dropout(0.25)

Accuracy details for each epoch(19)		
		
 0%|          | 0/469 [00:00<?, ?it/s]/usr/local/lib/python3.6/dist-packages/ipykernel_launcher.py:26: UserWarning: Implicit dimension choice for log_softmax has been deprecated. Change the call to include dim=X as an argument.
loss=0.05997633561491966 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 45.39it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0627, Accuracy: 9785/10000 (97.85%)

loss=0.07222364842891693 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 45.99it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0467, Accuracy: 9848/10000 (98.48%)

loss=0.048015985637903214 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 44.88it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0389, Accuracy: 9867/10000 (98.67%)

loss=0.11880288273096085 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 45.16it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0278, Accuracy: 9912/10000 (99.12%)

loss=0.037012580782175064 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 45.73it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0303, Accuracy: 9899/10000 (98.99%)

loss=0.0165615975856781 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 46.71it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0296, Accuracy: 9905/10000 (99.05%)

loss=0.04282568022608757 batch_id=468: 100%|██████████| 469/469 [00:09<00:00, 47.43it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0259, Accuracy: 9909/10000 (99.09%)

loss=0.05051098391413689 batch_id=468: 100%|██████████| 469/469 [00:09<00:00, 46.97it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0228, Accuracy: 9931/10000 (99.31%)

loss=0.044122710824012756 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 46.87it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0226, Accuracy: 9927/10000 (99.27%)

loss=0.011322383768856525 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 46.62it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0257, Accuracy: 9920/10000 (99.20%)

loss=0.02489069662988186 batch_id=468: 100%|██████████| 469/469 [00:10<00:00, 46.38it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0228, Accuracy: 9926/10000 (99.26%)

loss=0.01895497739315033 batch_id=468: 100%|██████████| 469/469 [00:09<00:00, 47.36it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0207, Accuracy: 9928/10000 (99.28%)

loss=0.059186067432165146 batch_id=468: 100%|██████████| 469/469 [00:09<00:00, 47.58it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0213, Accuracy: 9932/10000 (99.32%)

loss=0.17084760963916779 batch_id=468: 100%|██████████| 469/469 [00:09<00:00, 47.62it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0225, Accuracy: 9930/10000 (99.30%)

loss=0.030221352353692055 batch_id=468: 100%|██████████| 469/469 [00:09<00:00, 47.62it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0209, Accuracy: 9932/10000 (99.32%)

loss=0.01448532473295927 batch_id=468: 100%|██████████| 469/469 [00:09<00:00, 47.66it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0195, Accuracy: 9934/10000 (99.34%)

loss=0.02479301393032074 batch_id=468: 100%|██████████| 469/469 [00:09<00:00, 47.73it/s]
  0%|          | 0/469 [00:00<?, ?it/s]
Test set: Average loss: 0.0219, Accuracy: 9933/10000 (99.33%)

loss=0.01111382246017456 batch_id=468: 100%|██████████| 469/469 [00:09<00:00, 47.53it/s]
Test set: Average loss: 0.0214, Accuracy: 9934/10000 (99.34%)

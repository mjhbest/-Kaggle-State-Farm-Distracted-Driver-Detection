# State-Farm-Distracted-Driver-Detection
[kaggle competition for "State Farm Distracted Driver Detection"](https://www.kaggle.com/owenmyung/ml-project)

# Final Model  
- Base_Optimizer : Adam  
- Optimizer : SAM  
- Loss Function :  CrossEntropyLoss  
- Model : ResNet50 (not pretrained)  
- Learning Rate Scheduler : CosineAnealing Warm Up Restart  

# Data Augmentation  
- RandomResizedCrop  
- ColorJitter  

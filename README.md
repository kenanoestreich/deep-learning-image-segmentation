# DeepLearningImageSegmentation
Ideally, a package that streamlines the process of Deep Segmentation from choosing model architecture all the way through to generating model predictions on unseen data

## Core Features
- Use `keras-tuner` to manage hyperparameter tuning with as little user interaction as possible. 
- Allow for different approaches to model training (automated or supervised). In general, the less user interaction required the better. 
  - Allow for transfer learning in addition to training a model from scratch. 
- Use existing models (stored locally and used as input) to make predictions on input volumes (computational efficiency is very important here). 
- Provide useful metrics on model performance. 

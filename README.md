# Facial Emotion Recognition using FER2013 with pytorch


## Summary

| Model    | Test Accuracy | Train Loss | Test Loss |
| -------- | ------- | -------- | ------- |
| Custom (Normal Transform)  | 49.6%    | 1.613    | 1.663    |
| Custom (Horizontal Flip) | 51.1%     | 1.633    | 1.650   |
| Custom (Trivial Aug)    | 50.2%    | 1.730    | 1.656    |
| Custom (Trivial Aug, LR = 0.01)    | 47.1%   | 1.751    | 1.684   |
| VGG19 (Trivial Aug)   | 59.0%    | 1.604    | 1.570   |

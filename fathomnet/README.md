# Applying YoloV8 for Bounding Box Prediction on the FathomNet dataset

Dataset taken from: [FathomNet 2023 - Shifting seas, shifting species: Out-of-sample detection in the deep ocean](https://www.kaggle.com/competitions/fathomnet-out-of-sample-detection)

Article summarising project can be found [here](https://wonderfulcuriosities.super.site/fathomnet-exploring-computer-vision-for-marine-species-identification).

Model can be loaded with

```python
from ultralytics import YOLO

# Load a model
model = YOLO('path/to/best.pt')  
```

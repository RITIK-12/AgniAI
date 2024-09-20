
# AgniAI: Visual AI for Precision Wildfire Monitoring in Satellite Imagery

## Author
**Ritik Bompilwar**  
MS AI Candidate  
Northeastern University

---

## Project Overview
AgniAI leverages advanced Visual AI technologies to provide precise and timely monitoring of wildfires using satellite imagery. This project aims to harness the power of the latest YOLOv8 model, fine-tuned to identify and track the progression of wildfires from space, offering a crucial tool for emergency response teams and environmental monitoring agencies.

---

## Dataset Used
For this project, the **Satellite Wildfire Detection Dataset** provided by HTW Berlin on Roboflow was utilized. This dataset is a collection of annotated satellite images designed specifically for training models to detect wildfires. The images in this dataset are diverse, covering various landscapes and wildfire scenarios, which helps in building a robust model. Data augmentation techniques such as flips and brightness adjustments (±15%) were applied to enhance the model's ability to generalize across different lighting and orientations.

- **Dataset Source:** Roboflow Universe
- **Provider:** HTW Berlin
- **Dataset Link:** [Satellite Wildfire Detection Dataset](https://universe.roboflow.com/htw-berlin-xv7eo/satellite-wildfire-detection)

---

## Model and Training
The YOLOv8 model, known for its speed and accuracy in object detection tasks, was chosen for this project. The model was fine-tuned for 10 epochs on the Satellite Wildfire Detection Dataset to adapt its detection capabilities to the unique characteristics of wildfire in satellite imagery.

- **Model:** YOLOv8
- **Epochs:** 10
- **Optimizations:** Adjustments were made to the learning rate and augmentation strategies to optimize performance for high-resolution satellite images.

---

## Results and Discussion
*Initial testing shows promising results with high precision in detecting wildfire affected areas. Further validations and real-time testing will be conducted to ensure reliability under various conditions.*

---

## Future Work
Future enhancements will focus on integrating real-time data feeds to enable live monitoring capabilities. Additional layers of analysis will also be explored to predict the spread of wildfires based on wind and weather data.

---

## References
1. HTW Berlin. (2023). Satellite Wildfire detection Dataset. Roboflow Universe. Retrieved on 2024-09-20 from [Roboflow: Satellite Wildfire Detection](https://universe.roboflow.com/htw-berlin-xv7eo/satellite-wildfire-detection).
2. Redmon, Joseph, et al. (2016). YOLOv8: Real-Time Object Detection. Available at [arXiv:1602.08511](https://arxiv.org/abs/1602.08511).

---

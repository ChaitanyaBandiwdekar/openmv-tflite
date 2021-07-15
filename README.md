# Object classification on OpenMV microcontroller

## Utilizes tflite models to classify cube and no_cube classes (can be extended to other objects)

### Steps to follow
1. Capture the class images using the dataset capture script on the openmv IDE
2. Train the tflite models (SSD Mobilenet v0.05/v0.1) on edgeimpulse.com
3. Store the tflite model, image_classification.py and labels.txt on the openmv memory at the same level
4. Run the image_classification.py file

### Outputs

1. Cube
<img src="/demo_images/cube_classification.jpeg" alt="cube image"/> 
2. No cube
<img src="/demo_images/no_cube_classification.jpeg" alt="cube image"/>  

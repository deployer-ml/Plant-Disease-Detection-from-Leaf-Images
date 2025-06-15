# Plant Leaf Disease Detection System 

 Home page ![Screenshot (565)](https://github.com/user-attachments/assets/78ef8f09-7a16-4374-8e1f-3326a6297061)
 Prediction page ![Screenshot (568)](https://github.com/user-attachments/assets/cef2a01e-dae0-4873-bc4f-6530452759c6)
 ![Screenshot (568)](https://github.com/user-attachments/assets/9ccdb63c-66ea-4d24-9a2c-7523880def2f)
 About page ![Screenshot (570)](https://github.com/user-attachments/assets/9555045d-573d-4a6b-8194-1076f7ff6f97)


 


## Key Features
- 🖼️ Image classification for 38 types of plant diseases
- 🌱 Supports multiple plant species including tomato, potato, pepper, etc.
- 🔬 Uses convolutional neural networks (CNN) for accurate detection
- 📱 Lightweight model suitable for mobile deployment
- 📊 Detailed classification reports and confidence scores

## Installation
```bash
git clone https://github.com/yourusername/plant-leaf-disease-detection.git
cd plant-leaf-disease-detection
pip install -r requirements.txt
```

## Usage
1. Place your plant leaf images in the `test_images/` folder
2. Run the detection script:
```bash
python app.py --image_path test_images/your_image.jpg
```

## Dataset
The model was trained on the [PlantVillage Dataset](https://plantvillage.psu.edu/) containing over 54,000 images of healthy and diseased plant leaves.

## Model Architecture
The system uses a custom CNN architecture with:
- 5 convolutional layers with ReLU activation
- 3 max-pooling layers
- 2 fully connected layers
- Dropout for regularization

## Results
| Metric        | Value   |
|---------------|---------|
| Accuracy      | 98.2%   |
| Precision     | 98.1%   |
| Recall        | 98.0%   |
| F1-Score      | 98.0%   |

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)# Plant-Disease-Detection-from-Leaf-Images

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/afb585e0-d9fb-45f1-9e57-8689596c2482" width="400" style="margin-right: 10;"></td>
    <td><h1 style="margin: 0;">Artificial Intelligence Driven Marine Vessel Detection Using Satellite Imagery</h1></td>
  </tr>
</table>

## Project Overview
This project focuses on building an AI-driven system for detecting marine vessels from satellite imagery. Leveraging deep learning techniques, the system analyzes satellite images to accurately identify the presence of marine vessels. This project has potential applications in maritime surveillance, illegal fishing detection, and maritime traffic management.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Data Collection](#data-collection)
5. [Model Architecture](#model-architecture)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Results](#results)
9. [Contributing](#contributing)
10. [License](#license)
11. [Author](#author)

## Features
- Detection of marine vessels in satellite imagery using AI models.
- Automated preprocessing of satellite images (cropping, resizing, etc.).
- Integration with various deep learning frameworks for model training.
- Visualization of results with bounding boxes and confidence scores.
- Support for both optical and radar satellite imagery.

## Technologies Used
- **Deep Learning Frameworks**: TensorFlow, PyTorch
- **Satellite Image Processing**: OpenCV, GDAL
- **Model Visualization**: Matplotlib, Plotly
- **Data Handling**: NumPy, Pandas
- **Deployment**: Flask/Django (optional for web integration)

## Data Collection
The dataset comprises satellite imagery from various sources such as:
- **Publicly Available Datasets**: Open Access satellite images from agencies like NASA and ESA.
- **Custom Datasets**: Curated satellite images obtained through partnerships or purchased from providers.

### Data Preprocessing
- Image augmentation techniques applied for model robustness.
- Normalization and scaling of pixel values.
- Splitting data into training, validation, and test sets.

## Model Architecture
The model utilizes Convolutional Neural Networks (CNN) and Transfer Learning to detect vessels. Key components include:
- Pre-trained networks (e.g., ResNet, EfficientNet) for feature extraction.
- Fully connected layers to classify marine vessels.
- Post-processing techniques like Non-Maximum Suppression (NMS) to refine bounding box predictions.

## Installation
**To set up the project, follow these steps:**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/AI-Driven-Marine-Vessel-Detection.git
   ```
2. **Create a virtual environment:**
    ```bash
    python -m venv venv
    ```
3. **Activate the virtual environment:**
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

4. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```
    
## Usage
1. **Traning the model:**
```bash
    python train.py --dataset path_to_dataset --epochs 50
```

2. **Testing/Inference:**
```bash
    python detect.py --image path_to_image
```

3. **Visualizing the Results: The results (detected vessels) will be saved with bounding boxes drawn around the vessels in the specified output directory.**

   
## Results
**The model achieved an accuracy of X% on the test dataset, with a precision of Y% and recall of Z%.**

Sample Results:

## Contributing
**Contributions are welcome! Please follow these steps to contribute:**

**Fork the repository**

1. **Create a new feature branch:**
```bash
 git checkout -b feature/your-feature-name.
```
2. **Commit your changes:**
 ```bash
git commit -m 'Add your feature here'.
```
4. **Push to the branch:**
```bash
git push origin feature/your-feature-name.
```
5. **Open a pull request.**

## License
**This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.**

## Author
**For any questions or suggestions, please contact:**
- Harsh Singh: [harshjuly12@gmail.com](harshjuly12@gmail.com)
- GitHub: [harshjuly12](https://github.com/harshjuly12)

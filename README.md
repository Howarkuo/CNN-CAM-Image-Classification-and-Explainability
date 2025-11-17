# CNN-CAM-Image-Classification-and-Explainability
This repository contains the code and resources for a deep learning project focused on building a Convolutional Neural Network (CNN) for image classification, coupled with **Class Activation Mapping (CAM)** for model interpretability.

The primary goal is to not only classify images accurately but also to visualize *which parts* of the image the CNN is focusing on when making a prediction.
![image] (https://github.com/Howarkuo/CNN-CAM-Image-Classification-and-Explainability/main/download.png)
---
## 🚀 Getting Started

### Prerequisites



To run the main notebook, you will need a Python environment with Jupyter support and the standard deep learning libraries installed.

* **Python 3.x**
* **TensorFlow / Keras**
* **NumPy**
* **Matplotlib**
* **Pillow (PIL)**


### Installation
Clone the repository to your local machine:

```bash
git clone https://github.com/Howarkuo/CNN-CAM-Image-Classification-and-Explainability.git
Data Structure

The main notebook expects the dataset to follow the directory structure below:

bash
Copy code
.
├── Data/
│   ├── AD_Data/      # Alzheimer’s Disease images
│   ├── ASD_Data/     # Autism Spectrum Disorder images
│   └── ICH_Data/     # Intracerebral Hemorrhage images
├── CNN_CAM.ipynb
└── README.md
```
To create the required folders automatically:

bash
Copy code
mkdir -p Data/AD_Data Data/ASD_Data Data/ICH_DataBefore running the notebook, ensure your training and testing image files are placed into the corresponding subdirectories within the Data/ folder.

📂 Project Files

CNN_CAM.ipynb

This is the main Jupyter/Colab notebook containing the complete workflow:

Data Loading and Preprocessing: Reading images and preparing them for the CNN.

CNN Model Definition: Building the sequential or functional CNN model.

Training: Training the model on the specified datasets.

Evaluation: Calculating performance metrics.

CAM Implementation: Functions to generate and overlay Class Activation Maps onto input images, highlighting the regions of importance for prediction.

💡 Usage

The project is best run within a Google Colab environment (as suggested by the notebook's structure) or a local Jupyter environment.

Open the Notebook: Launch Jupyter Lab or Jupyter Notebook, or upload the file directly to Google Colab.

Set Paths and Load Data: Run the initial cells to define file paths and load the image data (assuming you have populated the Data/ structure).

Train Model: Execute the model building and training cells.

Analyze Results: Use the final sections of the notebook to generate the CAM visualizations and interpret the model's decisions.

Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

License

[Specify your license here, e.g., MIT, Apache 2.0, or leave blank if unspecified.]

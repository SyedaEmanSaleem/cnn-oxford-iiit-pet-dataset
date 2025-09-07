# CNN Project – Oxford-IIIT Pet Dataset  

This project applies **Convolutional Neural Networks (CNNs)** with **transfer learning (EfficientNet-B6)** to classify images from the [Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/).  
The dataset contains **37 breeds of cats and dogs**, each with around 200 images, making it a challenging fine-grained classification task.  

## 📂 Contents  
- `Oxford_Pets.ipynb` – Main notebook with model implementation and training  
- `requirements.txt` – Dependencies used in the project  
- `training_log.csv` – Training accuracy and loss logs  

## ⚙️ Requirements  
- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- scikit-learn  

Install dependencies:  

```bash
pip install -r requirements.txt
```
## 🚀 How to Run

Download the Oxford-IIIT Pet Dataset from the official website
or via TensorFlow Datasets.

Place the dataset in a folder named data/ (or update the dataset path in the notebook).

Run the notebook:
```bash
jupyter notebook Oxford_Pets.ipynb
```
## 📊 Results

Training Accuracy: 98.12%

Validation Accuracy: 94.79%

## Notes
Transfer learning with EfficientNet-B6 was used for feature extraction and fine-tuning.
Data augmentation techniques (random flips, rotations, and zooms) were applied to improve generalization.

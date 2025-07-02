# 🌱 The Plant Guard

An intelligent plant health monitoring system that leverages deep learning and computer vision to identify plant species and diagnose diseases. This project demonstrates expertise in machine learning, data science, and agricultural technology applications.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.10.1-orange.svg)](https://tensorflow.org)
[![Keras](https://img.shields.io/badge/Keras-2.10.0-red.svg)](https://keras.io)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3.0-green.svg)](https://scikit-learn.org)

## 🚀 Project Overview

The Plant Guard is a comprehensive machine learning solution that addresses two critical challenges in agriculture and gardening:

1. **Plant Species Identification**: Accurately classify plant species from images
2. **Disease Detection**: Identify and diagnose plant diseases for early intervention

This project showcases end-to-end machine learning pipeline development, from data exploration to model deployment, with practical applications in precision agriculture and plant health management.

## 🎯 Key Features

- **Multi-Model Architecture**: Implements both vanilla CNN and transfer learning approaches using VGG16
- **Comprehensive EDA**: Detailed exploratory data analysis for both plant identification and disease detection
- **Model Comparison**: Systematic evaluation of different neural network architectures
- **Production-Ready Code**: Well-structured Jupyter notebooks with clear documentation
- **Scalable Design**: Modular approach suitable for integration into larger agricultural systems

## 🛠 Technical Stack

- **Deep Learning**: TensorFlow/Keras, PyTorch
- **Computer Vision**: CNN architectures, Transfer Learning (VGG16)
- **Data Science**: Pandas, NumPy, Scikit-learn
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Additional Tools**: XGBoost, ImageHash, IPython widgets

## 📊 Dataset

The project utilizes the comprehensive [Plant Disease Expert dataset](https://www.kaggle.com/datasets/sadmansakibmahi/plant-disease-expert/data) from Kaggle, which provides:
- High-quality plant images across multiple species
- Diverse disease categories with clinical annotations
- Balanced representation for robust model training

## 🏗 Project Structure

```
the-plant-guard/
├── 📊 EDA Notebooks
│   ├── plant_id_eda.ipynb           # Plant identification analysis
│   └── plant_disease_id_eda.ipynb   # Disease detection analysis
├── 🤖 Model Training
│   ├── plant-identification.ipynb    # Plant species classification
│   └── plant-disease-identification.ipynb # Disease detection models
├── 🎯 Trained Models
│   ├── disease-vanilla.h5           # Vanilla CNN for disease detection
│   ├── disease-vgg16.h5             # VGG16 transfer learning model
│   ├── plant-disease-vanilla.h5     # Combined plant-disease model
│   ├── vanilla.h5                   # Vanilla CNN for plant ID
│   └── vgg16_vanilla.h5             # VGG16 for plant identification
├── 📄 Documentation
│   ├── docs/                        # HTML exports of notebooks
│   └── documentation/               # Additional project docs
├── 🔧 Development
│   └── dev/                         # Development utilities
└── 📋 Configuration
    ├── requirements.txt              # Python dependencies
    └── README.md                     # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Git (optional, for cloning)
- 8GB+ RAM recommended for model training

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/coachlivinglegend/the-plant-guard.git
   cd the-plant-guard
   ```

2. **Set up virtual environment**
   ```bash
   # Create virtual environment
   python -m venv plant-guard-env
   
   # Activate virtual environment
   # Windows (PowerShell/CMD)
   .\plant-guard-env\Scripts\activate
   
   # macOS/Linux
   source plant-guard-env/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

### 🔬 Running the Analysis

#### Exploratory Data Analysis
Start with the EDA notebooks to understand the dataset:

```bash
# Plant species analysis
jupyter notebook plant_id_eda.ipynb

# Disease detection analysis  
jupyter notebook plant_disease_id_eda.ipynb
```

#### Model Training
Train and evaluate the machine learning models:

```bash
# Plant identification models
jupyter notebook plant-identification.ipynb

# Disease detection models
jupyter notebook plant-disease-identification.ipynb
```

> **Note**: Select the `plant-guard-env` kernel when prompted in Jupyter. If the environment doesn't appear, restart your IDE/Jupyter server.

## 🎯 Model Performance

The project implements multiple neural network architectures:

- **Vanilla CNN**: Custom convolutional neural network designed for plant image classification
- **VGG16 Transfer Learning**: Pre-trained VGG16 model fine-tuned for plant and disease recognition
- **Ensemble Approaches**: Combination of multiple models for improved accuracy

## 💼 Business Applications

- **Precision Agriculture**: Early disease detection for crop management
- **Smart Gardening**: Plant identification and health monitoring for home gardeners  
- **Agricultural Research**: Data-driven insights for plant pathology studies
- **Mobile Applications**: Integration potential for field-ready diagnostic tools

## 🔮 Future Enhancements

- [ ] Real-time inference API development
- [ ] Mobile application integration
- [ ] Edge device deployment optimization
- [ ] Multi-language plant database expansion
- [ ] Temporal disease progression tracking

## 📈 Skills Demonstrated

- **Machine Learning**: Deep learning model development and optimization
- **Computer Vision**: Image preprocessing and augmentation techniques
- **Data Science**: Statistical analysis and feature engineering
- **Software Engineering**: Clean, maintainable code with proper documentation
- **Research**: Systematic experimentation and model comparison
- **Domain Knowledge**: Understanding of agricultural and botanical applications

## 🤝 Contributing

This project is open for collaboration and improvements. Feel free to:
- Report issues or bugs
- Suggest new features
- Submit pull requests
- Share feedback on model performance

## 📄 License

This project is available for educational and research purposes. Please cite appropriately if used in academic work.

---

**Developed with 🌱 for sustainable agriculture and plant health management**

# 🍃 Leaf Buddy – AI-Powered Plant Leaf Identification

**Leaf Buddy** is an AI-powered plant leaf identification application that uses Deep Learning and Computer Vision to analyze leaf images and predict their corresponding plant categories. It provides a simple interface for exploring image-based plant classification using a trained TensorFlow/Keras model.

---

## 🌱 Project Overview

Leaf Buddy aims to make plant identification easier through Artificial Intelligence. Users can provide a leaf image, and the application processes the image using a deep learning model to generate a classification prediction.

The project demonstrates how machine learning and image processing can be integrated into a Python application to build an AI-powered plant identification system.

## ✨ Key Features

- 🍃 **Leaf Image Analysis:** Analyze uploaded plant leaf images.
- 🧠 **Deep Learning Integration:** Uses a TensorFlow/Keras model for image classification.
- 🔍 **Automated Prediction:** Predicts the corresponding class from an input image.
- 🖼️ **Image Processing:** Prepares leaf images for model inference.
- 📊 **Class Mapping:** Uses a JSON file to maintain classification labels.
- ⚡ **Lightweight Model:** Uses the Keras model format for loading trained model weights.
- 🧪 **Sample Testing:** Includes a sample leaf image and a utility script for generating testing assets.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| TensorFlow | Deep learning framework |
| Keras | Neural network model |
| NumPy | Numerical operations |
| Pillow (PIL) | Image processing |
| JSON | Classification label management |

## 📂 Project Structure

```text
Leaf-Buddy/
│
├── app.py                  # Main application
├── plant_model.keras       # Deep learning model
├── class_names.json        # Classification labels
├── create_dummy_assets.py  # Testing asset generator
├── sample_leaf.jpg         # Sample leaf image
├── requirements.txt        # Project dependencies
├── README.md               # Project documentation
│
└── __pycache__/            # Python cache files
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Pavanateja2007-aiml/Leaf-Buddy.git
```

### 2. Navigate to the Project Directory

```bash
cd Leaf-Buddy
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows:**
```bash
venv\Scripts\activate
```

**Linux / macOS:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python app.py
```

Open the local application address displayed in your terminal, if the application starts a web server.

## 🧠 Model Information

The project includes a TensorFlow/Keras model saved in the `.keras` format.

**Model file:** `plant_model.keras`

**Classification labels:** `class_names.json`

The model is intended for image-based plant classification. The application uses the saved model and its associated class labels to generate predictions.

## 🧪 Testing

A utility script is included to generate dummy model assets and a sample leaf image when they are not already available.

Run:

```bash
python create_dummy_assets.py
```

**Note:** The generated dummy model is intended for application testing, not for producing scientifically meaningful plant identification results. Use a properly trained model for actual predictions.

## 🚀 Future Enhancements

- Improve classification accuracy using larger and more diverse datasets.
- Support additional plant species.
- Add plant disease detection.
- Provide disease prevention and treatment recommendations.
- Integrate explainable AI techniques such as Grad-CAM.
- Develop a responsive mobile-friendly interface.
- Deploy the application as an accessible web service.

## 🎯 Project Objective

To explore the practical application of Artificial Intelligence, Deep Learning, and Computer Vision in plant identification by developing an image-based classification application.

## 👨‍💻 Developer

**Pavanateja Vemuri**

B.Sc. Artificial Intelligence | AI & ML Engineering

- GitHub: [@Pavanateja2007-aiml](https://github.com/Pavanateja2007-aiml)
- Project: [Leaf Buddy](https://github.com/Pavanateja2007-aiml/Leaf-Buddy)

---

⭐ If you find this project interesting, consider giving the repository a star!

**Built with Python, Deep Learning, and a passion for AI.** 🍃

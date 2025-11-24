# MNIST ANN Project

A simple end-to-end project that builds and deploys an Artificial Neural Network (ANN) to classify handwritten digits from the MNIST dataset.

---

## 🚀 Project Overview  
- Built an ANN model using Python and Keras/TensorFlow to recognize handwritten digits (0–9) from the [MNIST dataset](https://en.wikipedia.org/wiki/MNIST_database).  
- Trained, validated, and saved the model (`ANNModel.pkl`).  
- Developed a Flask web API (`app.py`) to serve predictions from the trained model.  
- Demonstrates a complete ML pipeline: data preprocessing → model training → export → deployment.

---

## 🛠 Technologies & Tools  
- **Language:** Python  
- **Libraries/Frameworks:** NumPy, Pandas, Matplotlib, scikit-learn, Keras/TensorFlow, Flask  
- **Files Included:**  
  - `ANN_MNIST.ipynb` — Jupyter Notebook for model training  
  - `ANNModel.pkl` — Saved trained model  
  - `app.py` — Flask application for inference  
  - `requirements.txt` — Project dependencies  

---

## 📂 Getting Started

1. Clone the repository  
   ```bash
   git clone https://github.com/parshavpatil/Mnist_ANN_project.git
   cd Mnist_ANN_project

2. Create and activate a virtual environment

python3 -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate

3. Install required packages

pip install -r requirements.txt

4. Run the Flask application

python app.py

# 👕 AI-Based Virtual Clothes Try-On System

An AI-powered **Virtual Clothes Try-On System** that allows users to digitally try clothes on a person’s image using **Computer Vision and Deep Learning**.
  
The system takes an image of a person and a clothing item, then intelligently overlays the garment onto the person to generate a realistic try-on result.  

This project simulates a **virtual dressing room** experience for online fashion platforms. 
 
---

# 📌 Table of Contents   
 
- Introduction 
- Features
- Technologies Used
- Project Structure
- Installation
- Usage
- Working Pipeline
- Applications
- Future Improvements
- Academic Use
- Author

---

# 📖 Introduction

Online shoppers often struggle to visualize how clothes will look on them. This project solves that problem using AI.

It applies:

- Image Segmentation  
- Deep Learning  
- Image Warping  
- Computer Vision  

to digitally fit garments onto a person’s photo.

---

# ✨ Features

✔ Upload person & clothing images  
✔ Automatic background removal  
✔ Clothing mask generation  
✔ Garment alignment and warping  
✔ Realistic virtual try-on results  
✔ Easy execution using Python  
✔ Optional Gradio web interface  

---

# 🧠 Technologies Used

## Programming Language
- Python

## Libraries
- OpenCV  
- PyTorch  
- NumPy  
- torchvision  
- PIL  
- Gradio  

## Concepts
- Computer Vision  
- Image Segmentation  
- Deep Learning  
- Neural Networks  
- Mask Generation  
- Image Warping  

---

# 📂 Project Structure

clothes-virtual-try-on/

│

├── assets/ # Images and model files

├── datasets.py # Dataset loading

├── network.py # Neural network model

├── cloth-mask.py # Cloth segmentation

├── remove_bg.py # Background removal

├── utils.py # Helper functions

├── test.py # Testing script

├── run.py # Main execution

├── setup_gradio.ipynb # Gradio interface

├── setup_ngrok.ipynb # Online sharing setup

└── README.md



---

# ⚙️ Installation

## 1️⃣ Clone Repository


git clone https://github.com/nutanshinde1/clothes-virtual-try-on.git
cd clothes-virtual-try-on

## 2️⃣ Create Virtual Environment
python -m venv venv

### Activate environment:


#### Windows:

venv\Scripts\activate

#### Mac/Linux:

source venv/bin/activate


## 3️⃣ Install Dependencies

pip install -r requirements.txt

## ▶️ Usage

### Run the project:

python run.py

### For testing:

python test.py

### Provide:

Person image

Clothing image

### Output:

Virtual try-on result image

---

# 🔍 Working Pipeline
## 1️⃣ Input Images
Person image

Clothing image

## 2️⃣ Preprocessing
Resize

Normalize

Background removal

## 3️⃣ Segmentation
Generate clothing mask

## 4️⃣ Warping
Align clothing to body

## 5️⃣ Synthesis
Neural network generates final output

---

# 🛍️ Applications
- Online fashion stores

- Virtual fitting rooms

- E-commerce platforms

- Fashion technology research

- AI shopping assistants

  ---

# 🚀 Future Improvements
- Real-time webcam try-on

- Mobile app integration

- Diffusion models for realism

- Multi-clothing support

- Better segmentation models

  ---

# 👩‍💻 Author
Developed for academic learning and research purposes.
Maintained and improved for AI/ML practice.


---


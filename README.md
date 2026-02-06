👕 AI-Based Virtual Clothes Try-On System

An AI-powered Virtual Clothes Try-On System that allows users to digitally try clothes on a person’s image using Computer Vision and Deep Learning.
The system takes an image of a person and a clothing item, then intelligently overlays the garment onto the person to generate a realistic try-on result.

This project demonstrates the use of image segmentation, deep learning, and image processing to simulate a virtual dressing room experience.

📌 Features

✔ Upload a person image and clothing image
✔ Automatic background removal
✔ Clothing mask generation
✔ Garment alignment and warping
✔ Realistic virtual try-on output
✔ Simple execution using Python scripts
✔ Optional web demo using Gradio

🧠 Technologies Used
Programming

Python

Libraries & Frameworks

OpenCV

PyTorch

NumPy

torchvision

PIL (Python Imaging Library)

Gradio (for demo UI)

Concepts

Computer Vision

Image Segmentation

Deep Learning

Mask Generation

Image Warping

Neural Networks

📂 Project Structure
clothes-virtual-try-on/
│
├── assets/              # Images, models, resources
├── datasets.py          # Dataset loading & preprocessing
├── network.py           # Neural network architecture
├── cloth-mask.py        # Cloth segmentation & mask generation
├── remove_bg.py         # Background removal
├── test.py              # Testing script
├── run.py               # Main execution file
├── utils.py             # Helper functions
├── setup_gradio.ipynb   # Gradio demo setup
├── setup_ngrok.ipynb    # Ngrok setup for sharing demo
└── README.md

⚙️ Installation
Step 1 — Clone Repository
git clone https://github.com/your-username/clothes-virtual-try-on.git
cd clothes-virtual-try-on

Step 2 — Create Virtual Environment (Recommended)
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

Step 3 — Install Dependencies
pip install -r requirements.txt

▶️ Usage
Run the Project
python run.py

Testing
python test.py


Provide:

Person image

Clothing image

The system will generate a virtual try-on result.

🧪 How It Works

Input Images
User provides a person image and a clothing image.

Preprocessing

Background removal

Image resizing

Normalization

Clothing Segmentation
A mask is generated to isolate the clothing region.

Garment Warping
The clothing is adjusted to match body shape and position.

Image Synthesis
Neural networks generate the final try-on output.

🎯 Applications

Online fashion stores

Virtual fitting rooms

E-commerce platforms

Fashion technology research

AI-based shopping assistants

🚀 Future Improvements

Real-time camera try-on

Better segmentation models

Diffusion model integration

Mobile app version

Multi-clothing support

🎓 Academic Use

This project is suitable for:

Machine Learning courses

Computer Vision projects

Deep Learning research

Final year/semester projects

📸 Sample Output

Input:

Person Image

Clothing Image

Output:

Person wearing selected clothes virtually

🤝 Contributing

Contributions are welcome!
Feel free to fork and improve the project.

📜 License

This project is for educational and research purposes.

👩‍💻 Author

Developed as part of an academic AI/ML project.
Maintained and improved for learning and research.

 
 

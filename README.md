# 🧠 Image Recognition Website  

A simple and elegant **Flask-based Image Recognition Web App** built by **Hemangi Popat (23IT101)**.  
It allows users to upload an image and get real-time recognition results using **YOLOv5**, **OpenCV**, and **Pillow**.

---

## 🚀 Features
- 🖼️ Upload any image (JPG, PNG, etc.)
- 🔍 Detect and classify objects or people
- ⚙️ Uses YOLOv5 for accurate detection
- 🎨 Image preprocessing with Pillow
- 🌐 Simple, responsive front-end UI
- 💾 Stores uploads temporarily in `/uploads` folder

---

## 🗂️ Project Structure

image_recognization_website/
│
├── app.py
├── requirements.txt
├── index.html
│
├── static/
│ └── (CSS, JS, assets)
│
├── uploads/
│ └── (uploaded user images)
│
├── Output/
│ └── (example result images)
│
└── README.md

## 🖼️ Output Results

Here are a few example outputs from the Image Recognition Website:

![Result 1](https://raw.githubusercontent.com/23it101PopatHemangi/image_recognization_website/main/Output/Screenshot%202025-10-19%20134418.png)
![Result 2](https://raw.githubusercontent.com/23it101PopatHemangi/image_recognization_website/main/Output/Screenshot%202025-10-19%20134534.png)
![Result 3](https://raw.githubusercontent.com/23it101PopatHemangi/image_recognization_website/main/Output/Screenshot%202025-10-19%20134723.png)

## 🧩 Tech Stack  

| Component | Technology |
|------------|-------------|
| Backend | Flask (Python) |
| Frontend | HTML, CSS, JavaScript |
| ML Model | YOLOv5, mobilenet_v2 |
| Image Processing | OpenCV, Pillow |


---

## 🧠 How It Works  

1. User uploads an image via the web interface  
2. Image is preprocessed using Pillow  
3. YOLOv5 detects and classifies objects in the image  
4. The processed image is displayed back to the user with detected labels  

---

## 💻 Run Locally  

```bash
# Clone the repository
git clone https://github.com/23it101PopatHemangi/image_recognization_website.git

# Navigate into the folder
cd image_recognization_website

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py

Then open your browser and go to 👉 http://127.0.0.1:5000/




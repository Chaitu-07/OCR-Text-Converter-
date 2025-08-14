Handwritten to Digital Text Recognition

A hybrid application that combines Machine Learning and a Web Interface to extract and process text from images.  
It uses a Python-based deep learning module for the core text processing, with a Node.js backend API and a modern Vite + TailwindCSS frontend.

---

📂 Project Structure
Handwritten to Digital Text Recognition/
│
├── be/ # Backend (Node.js + TypeScript)
├── fe/ # Frontend (Vite + TailwindCSS + TypeScript)
├── mp_rsnet/ # Python ML module for text extraction
│ ├── Img/ # Image data/scripts
│ ├── generate_label.py
│ ├── labels_len.py
│ ├── model.py
│ ├── predict-text.py
│ ├── predict.py
│ └── segmentation_*.py
└── README.md

---

⚙️ Installation

1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/TextConverter.git
cd TextConverter

2️⃣ Backend Setup

cd be
npm install
npm run build
npm start

3️⃣ Frontend Setup

cd ../fe
npm install
npm run dev

4️⃣ Python ML Module Setup

cd ../mp_rsnet
python -m venv venv
# Activate:
# Windows:
venv\Scripts\activate

pip install -r requirements.txt

---

🚀 Usage
1. Start the backend (be folder).

2. Start the frontend (fe folder).

3. Ensure the Python environment in mp_rsnet is set up.

4. Open the frontend in your browser, upload an image, and get extracted text results.

---

🛠️ Tech Stack
- Backend: Node.js, TypeScript

- Frontend: Vite, TailwindCSS, TypeScript

- ML Module: Python, OpenCV, TensorFlow/PyTorch (depending on model)

- Other Tools: Git, npm, pip


# 🚗 Automatic Number Plate Recognition (ANPR) System

## 🔗 Test Link
[Live Demo](https://bravo-security.netlify.app/)

## 📌 Project Definition
The **Automatic Number Plate Recognition (ANPR) System** is an AI-powered solution designed to detect and recognize vehicle license plates in real-time. Leveraging advanced computer vision and deep learning techniques, this system automates vehicle identification, reducing manual intervention, enhancing security, and improving efficiency in traffic management and access control.

## 📝 Introduction
In response to the increasing demand for automated vehicle monitoring, this ANPR system efficiently recognizes number plates through live camera feeds, manual captures, or uploaded images. It processes these inputs using **YOLOv8** for plate detection and **EasyOCR & Tesseract OCR** for character recognition, storing the extracted data in **MongoDB** for retrieval and analytics.

## 🚀 Tech Stack
### Frontend:
- **React.js** - Component-based architecture for a responsive UI.
- **Tailwind CSS** - Utility-first framework for rapid UI design.

### Backend:
- **Python** - Handles backend logic and model integration.
- **Streamlit** - Provides an interactive dashboard for ANPR visualization.

### Object Detection:
- **YOLOv8** - Real-time object detection model for license plate recognition.

### Optical Character Recognition (OCR):
- **EasyOCR & Tesseract OCR** - Extracts alphanumeric characters from detected plates.

### Database:
- **MongoDB** - Stores recognized license plate data for efficient querying and retrieval.

## 🏗️ How to Run the Project
### 1️⃣ Clone the Repository
```bash
  git clone https://github.com/your-username/anpr-system.git
  cd anpr-system
```

### 2️⃣ Install Dependencies
#### Frontend
```bash
  cd frontend
  npm install
  npm start
```
#### Backend
```bash
  cd backend
  pip install -r requirements.txt
  streamlit run app.py
```

### 3️⃣ Start MongoDB Server
Ensure MongoDB is running locally or use a cloud database service.

### 4️⃣ Access the Application
- **Frontend:** Runs on `http://localhost:3000/`
- **Backend:** Accessible via Streamlit UI

## 🎯 Key Features
- 📷 **Live Camera Mode:** Captures video feed and processes number plates in real-time.
- 🖼️ **Camera Mode:** Allows users to manually capture images for processing.
- 📁 **Upload Mode:** Supports batch processing of pre-captured images.
- 🏎 **Fast & Accurate Detection:** Uses YOLOv8 for precise number plate localization.
- 🔡 **Reliable OCR Processing:** EasyOCR & Tesseract OCR for character recognition.
- 📊 **Database Integration:** Stores extracted license plate data in MongoDB for future analysis.
- 📡 **Scalability:** Designed to handle large-scale data efficiently.

## 📌 Conclusion
The **ANPR system** revolutionizes vehicle identification by automating the detection and recognition of license plates. It enhances security, optimizes traffic management, and improves overall operational efficiency. With a user-friendly interface and robust backend, it is a scalable solution for various industries, including security, law enforcement, parking management, and transportation.

🚀 **Future Enhancements:**
- Integration with cloud-based AI services.
- Enhanced OCR accuracy with deep learning models.
- Multi-language number plate recognition.

## 📜 License
This project is open-source under the MIT License. Contributions are welcome! 😊

---
✨ **Developed with passion and innovation!**


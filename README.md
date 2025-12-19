# 🥗 AllergyAware

AllergyAware is a full-stack AI-based application that detects food ingredients from images and alerts users about potential allergens.

## 🚀 Features
- Upload food images for ingredient recognition
- CNN-based model using ResNet18
- Allergy detection and alert system
- Flask REST API backend
- React frontend for user interaction

## 🧠 Tech Stack
- **Frontend:** React
- **Backend:** Flask
- **ML/DL:** PyTorch, CNN, ResNet18
- **Deployment Ready:** AWS / Cloud compatible

## 📁 Project Structure
frontend/ → React application
backend/ → Flask API
ml/ → Model training and datasets

## ⚙️ How It Works
1. User uploads food image
2. Image sent to Flask API
3. CNN model predicts ingredients
4. Allergens are identified
5. Results displayed on frontend

## 🛠️ Installation

### Backend
```bash
cd backend
pip install -r requirements.txt
python app.py

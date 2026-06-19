# 🎨 AI-Powered Skin Tone Classification & Fashion Color Recommendation System

An intelligent machine learning system that analyzes skin tone shades and recommends personalized clothing color palettes using color theory and data-driven classification.

Built for fashion personalization, e-commerce recommendations, and AI-powered styling experiences. 👗✨

---
## ScreenShots
<img width="1272" height="733" alt="WhatsApp Image 2026-06-19 at 11 02 01 PM" src="https://github.com/user-attachments/assets/25a15a95-b198-4ed1-a9bf-ab9cbfbd0be3" />
<img width="1278" height="738" alt="WhatsApp Image 2026-06-19 at 11 02 24 PM" src="https://github.com/user-attachments/assets/ab6b1dff-8458-4a71-8418-c4eb590abe9b" />
<img width="1303" height="695" alt="WhatsApp Image 2026-06-19 at 11 02 52 PM" src="https://github.com/user-attachments/assets/bbe54c81-2286-4107-b63a-6f218e46d546" />


## 📌 Project Overview

Choosing the right clothing colors can enhance personal style and confidence.

This project uses **Machine Learning + Color Analysis** to:

- Identify skin tone categories
- Classify similar skin shades using clustering techniques
- Recommend suitable clothing colors
- Provide fashion suggestions using HEX color codes

The system can be integrated into:

- 🛍️ Fashion E-commerce Platforms
- 👗 Virtual Styling Applications
- 📱 Personalized Wardrobe Apps
- 🧑‍🎨 AI Fashion Assistants

---

# 🚀 Features

✅ Skin tone classification using Machine Learning  
✅ HEX color processing and RGB conversion  
✅ KMeans clustering-based tone grouping  
✅ Personalized fashion color recommendations  
✅ Data-driven color matching  
✅ CSV-based recommendation export  
✅ Ready for API & Web App integration  

---

# 🧠 Machine Learning Workflow
Input Skin Shade HEX
    ↓
HEX → RGB Conversion
    ↓
Color Feature Extraction

    ↓
KMeans Clustering
    ↓
Skin Tone Category Detection
    ↓
Fashion Color Recommendation
    ↓
Personalized Palette Output

---

# 🏗️ Project Architecture

Skin-Tone-Classification
│
├── data/
│ ├── skin_shades_india.csv
│ └── fashion_color_palette.csv
│
├── output/
│ └── final_recommendations.csv
│
├── models/
│ └── trained clustering model
│
├── skin_tone_mapping.py
│
├── requirements.txt
│
└── README.md


---

# 📊 Dataset

### Skin Tone Dataset

Contains:

- Skin shade identifier
- HEX color values
- RGB representations

Example:
Shade ID: Shade 1
HEX: #F5E0D8
RGB: (245,224,216)


---

### Fashion Color Palette Dataset

Contains:

- Skin tone category
- Recommended clothing colors
- Color HEX codes

Example:

| Category | Recommended Colors |
|---|---|
| Warm Tone | Coral, Mustard, Olive |
| Cool Tone | Navy, Emerald, Lavender |

---

# ⚙️ Technologies Used

## Programming

🐍 Python

## Machine Learning

- Scikit-learn
- KMeans Clustering
- Feature Processing

## Data Processing

- Pandas
- NumPy

## Visualization

- Matplotlib

---

# 📦 Installation

## Clone the repository:

git clone https://github.com/yourusername/skin-tone-based-color-recommender.git

## Create Venv 
python -m venv venv
.\venv\Scripts\activate

## Install Dependencies
pip install -r requirements.txt

## To Run the project:
python -m uvicorn main:app --reload 

## 🔮 Future Improvements
AI Enhancements
CNN-based skin tone detection from images
Deep learning based fashion recommendation model
Real-time camera-based analysis
Application Development
🌐 REST API using FastAPI
🎨 Web application using Django
📱 Mobile application integration
Fashion Intelligence
Virtual try-on integration
Personalized outfit generation
E-commerce recommendation engine


## ⭐ If you like this project, don't forget to ⭐ the repo!`

## 👨‍💻 Author
Himasree Karunakaran

GitHub: https://github.com/HIMASREEK

LinkedIn: https://www.linkedin.com/in/himasree28/



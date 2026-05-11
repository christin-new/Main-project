# Zyra AI Fashion Assistant

## Overview
Zyra is an AI-powered smart fashion assistant that analyzes user outfits, detects clothing styles, and provides personalized fashion recommendations using Computer Vision, Generative AI, and a modern web interface.

The project combines:
- YOLO-based outfit detection
- Gemini AI outfit analysis
- Smart fashion recommendation engine
- AI chatbot for fashion queries
- Flask web application
- Outfit image generation support
- Indian and Western dress awareness

---

# Features

## AI Outfit Detection
- Detects clothing items using YOLO
- Identifies:
  - Shirt
  - T-shirt
  - Pants
  - Jeans
  - Traditional wear
  - Dresses
  - Accessories
- Supports multiple outfit categories

## Fashion Analysis
- Uses Gemini AI for:
  - Outfit understanding
  - Fashion scoring
  - Color analysis
  - Style suggestions
  - Occasion suitability

## Personalized Recommendations
- Generates:
  - Matching outfit suggestions
  - Accessory recommendations
  - Styling tips
  - Occasion-based fashion advice

## AI Fashion Chatbot
- Answers fashion-related questions
- Provides:
  - Styling help
  - Outfit suggestions
  - Color matching ideas
  - Seasonal recommendations

## Outfit Generation
- Generates outfit inspiration images
- Supports:
  - Indian traditional fashion
  - Casual wear
  - Formal wear
  - Western fashion

## Modern Web UI
- Responsive Flask-based frontend
- Interactive interface
- Image upload support
- Real-time analysis results

---

# Technologies Used

## Programming Language
- Python

## Frameworks & Libraries
- Flask
- OpenCV
- Ultralytics YOLO
- NumPy
- Pillow (PIL)
- Requests
- Torch

## AI Models & APIs
- YOLO Object Detection
- Google Gemini API

## Frontend
- HTML
- CSS
- JavaScript

---

# Project Workflow

1. User uploads outfit image
2. YOLO model detects clothing items
3. Gemini AI analyzes outfit
4. Fashion recommendation engine generates suggestions
5. Results are displayed in the web UI
6. User can interact with AI chatbot for additional help

---

# Folder Structure

```bash
Zyra/
│
├── app.py
├── templates/
├── static/
├── uploads/
├── generated_outfits/
├── models/
├── requirements.txt
└── README.md
```

---

# Installation

## Step 1: Clone Repository

```bash
git clone <repository-link>
cd Zyra
```

## Step 2: Create Virtual Environment

```bash
python -m venv venv
```

Activate environment:

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

---

# Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install flask opencv-python pillow ultralytics torch numpy requests
```

---

# API Configuration

Add your Gemini API key in the configuration section:

```python
GEMINI_API_KEY = "YOUR_API_KEY"
```

---

# Running the Project

## Run Flask Server

```bash
python app.py
```

Open browser:

```bash
http://127.0.0.1:5000
```

---

# Modules in the Notebook

| Cell | Module |
|------|---------|
| Cell 1 | Package Installation |
| Cell 2 | Imports |
| Cell 3 | API Configuration |
| Cell 4 | Constants |
| Cell 5 | YOLO Model Loading |
| Cell 6 | Professional UI |
| Cell 7 | Detection Helper Functions |
| Cell 8 | Gemini Outfit Analysis |
| Cell 9 | Outfit Image Generation |
| Cell 10 | Fashion Recommendation Engine |
| Cell 11 | Chatbot Intent Detection |
| Cell 12 | Chatbot Response Generator |
| Cell 13 | Web Pipeline |
| Cell 14 | Flask Application |
| Cell 15 | Start Server |

---

# Sample Functionalities

## Outfit Detection
- Detect fashion items from uploaded images
- Identify traditional and western clothing

## Smart Recommendations
Example:

```text
Your black shirt pairs well with beige chinos.
Consider adding a silver watch for a smart casual look.
```

## AI Chatbot
Example:

```text
User: Suggest outfit for wedding
Bot: Try a cream kurta with a dark Nehru jacket.
```

---

# Advantages

- AI-powered smart fashion assistant
- Real-time clothing analysis
- Personalized recommendations
- User-friendly interface
- Supports Indian fashion styles
- Scalable web architecture

---

# Future Enhancements

- Voice interaction support
- Virtual try-on system
- Mobile application
- User authentication
- Fashion trend prediction
- Weather-based outfit suggestions
- E-commerce integration

---

# Use Cases

- Smart mirrors
- Fashion recommendation systems
- Personal styling assistants
- E-commerce fashion platforms
- AI wardrobe management

---

# Conclusion

Zyra combines Artificial Intelligence, Computer Vision, and Generative AI to create a smart fashion assistant capable of understanding outfits, generating recommendations, and improving user styling experience.

The system demonstrates practical implementation of:
- Object Detection
- AI-based Fashion Analysis
- Recommendation Systems
- Conversational AI
- Web Application Development

---

# Authors

Developed as an AI-based Fashion Assistant project.

---

# License

This project is intended for educational and research purposes.


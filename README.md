# Grocery Inventory Optimization App

This project is a **smart grocery management application** designed to optimize inventory, recommend recipes, and automate order placement. It uses **Convolutional Neural Networks (CNN)** for image-based inventory tracking, integrates the **Spoonacular API** for intelligent recipe recommendations, and employs the **Twilio API** for an automated order-triggering system.

---

## 🚀 Features

- **Inventory Optimization**:
  - Track inventory using CNN-based image recognition.
  - Detect and quantify items in stock with real-time updates.
  
- **Recipe Recommendations**:
  - Suggest recipes based on available ingredients using the **Spoonacular API**.
  - Offer intelligent meal plans to minimize waste.

- **Automated Order Triggering**:
  - Monitor inventory thresholds and trigger orders automatically via the **Twilio API**.
  - Send SMS or email notifications for low stock levels.

- **User-Friendly Interface**:
  - Mobile-responsive dashboard for managing inventory, recipes, and orders.
  - Intuitive design for seamless user experience.

---

## 📂 Project Structure

```plaintext
├── app/                     # Main application folder
│   ├── templates/           # HTML templates for the web app
│   ├── static/              # CSS, JavaScript, and image files
│   ├── views.py             # Application logic and routing
│   ├── models.py            # Database models
│   ├── forms.py             # Forms for user inputs
├── cnn_model/               # CNN model for inventory recognition
│   ├── model.py             # Model architecture and training script
│   ├── preprocess.py        # Preprocessing utilities for image data
│   ├── predict.py           # Prediction script for inventory detection
├── integrations/            # API integrations
│   ├── spoonacular.py       # Wrapper for Spoonacular API calls
│   ├── twilio_api.py        # Wrapper for Twilio API calls
├── requirements.txt         # Python dependencies
├── manage.py                # Django management script
├── db.sqlite3               # SQLite database (default)
├── README.md                # Project documentation
└── LICENSE                  # License information

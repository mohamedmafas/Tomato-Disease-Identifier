# Tomato Leaf Disease Identifier 🍅

## Project Overview
The Tomato Leaf Disease Identifier is a web-based application designed to help farmers and agricultural enthusiasts identify diseases in tomato plants using Machine Learning. By simply uploading an image of a tomato leaf, the system uses a trained Convolutional Neural Network (CNN) to predict the disease and provides recommended treatments and prevention methods.

## Features
* **User Authentication:** Secure Registration, Login, and Password Reset features.
* **Disease Prediction:** Upload a tomato leaf image and get instant predictions.
* **Treatment & Prevention:** Detailed information on how to cure and prevent the predicted disease.
* **Chatbot Assistance:** An integrated chatbot to answer agriculture and disease-related queries.
* **Admin Panel:** A dedicated dashboard for administrators to manage user data, disease records, and the chatbot knowledge base.

## Tech Stack
* **Frontend:** React.js, Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose)
* **Machine Learning:** Python, TensorFlow/Keras, OpenCV

## Project Structure
* `/frontend` - Contains the React web application.
* `/backend` - Contains the Node.js REST API and Database models.
* `/ml_model` - Contains the Python scripts for training and exporting the CNN model.

## Installation & Setup (Local Development)

### Prerequisites
* Node.js (v16 or higher)
* Python (v3.8 or higher)
* MongoDB installed locally or MongoDB Atlas URI

### Steps to Run
1. **Clone the repository:**
   ```bash
   git clone <your-github-repo-url>
   cd Tomato-Disease-Identifier

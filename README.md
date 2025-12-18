# E-Commerce Backend with NLP Recommendations

Backend service for an e-commerce application built with Flask.  
Includes an NLP-based recommendation system that suggests products based on the similarity of product descriptions.

---

## Features

- JWT-based user authentication
- Product browsing and management
- NLP-powered product recommendations
- Firebase integration
- Modular Flask Blueprints

---

## Tech Stack

- Python 3
- Flask
- Flask-JWT-Extended
- Flask-CORS
- Firebase Admin SDK
- scikit-learn (NLP)
- Pandas

---

## Running Locally

```bash
# Activate virtual environment
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app
flask --app __init__.py run

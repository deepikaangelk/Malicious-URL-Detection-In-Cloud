# malicious_url_detector
https://phish-shield.onrender.com

# Malicious URL Detection

A web application that detects whether a given URL is malicious or benign using machine learning.

## Features

- **Web Interface:** Enter a URL and get instant feedback on whether it is likely malicious or benign.
- **Feature Extraction:** Uses URL characteristics (length, digits, special characters, suspicious words, brand spoofing, etc.) for detection.
- **Machine Learning:** Trained with a Random Forest classifier on a labeled dataset.
- **Brand Spoofing Detection:** Identifies URLs that mimic popular brands.

## Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/malicious-url-detection.git
   cd malicious-url-detection
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the model:**
   - If `model.pkl` is not present, run:
     ```bash
     python train.py
     ```
   - This will train the model using `dataset.csv` and save it as `model.pkl`.

4. **Run the application:**
   ```bash
   python app.py
   ```
   - The app will be available at [http://127.0.0.1:5000](http://127.0.0.1:5000).

5.Deployed on render cloud 



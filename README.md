# Fuel Theft Detection System

## 📌 Project Overview
This project aims to detect fuel theft in delivery trucks by monitoring real-time fuel levels using GPS and IoT sensors. The system identifies discrepancies between expected and actual fuel usage and raises alerts when theft is detected.

## 🚀 Features
- Real-time monitoring of fuel consumption
- Anomaly detection using statistical and ML-based approaches
- Random Forest classifier for theft detection
- Email alerts for suspected theft events
- Data visualization for fuel consumption patterns

## 🛠️ Technology Stack
- **Programming Language**: Python
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **Visualization**: Matplotlib, Seaborn
- **Alerts**: SMTP for email notifications
- **Jupyter Notebook** for interactive development

## 📂 Project Structure
```
├── data/                 # Sample dataset (replace with real sensor data)
├── notebooks/            # Jupyter Notebook with implementation
├── src/                  # Source code for processing & analysis
│   ├── detect_theft.py   # Theft detection logic
│   ├── train_model.py    # ML model training script
├── README.md             # Project documentation
├── requirements.txt      # Dependencies
```

## 🛠️ Installation & Usage
### 🔹 Prerequisites
- Python 3.8+
- Jupyter Notebook
- SMTP email configuration for alerts

### 🔹 Installation Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/SiddharthF18/fuel-theft-detection.git
   cd fuel-theft-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `Fuel_Theft_Detection.ipynb` and run the cells.

## 📊 Data & Model
- The dataset consists of fuel level readings, GPS location, distance traveled, and speed logs.
- A **Random Forest model** is trained to classify fuel theft cases.
- Threshold-based anomaly detection helps flag suspicious fuel drops.

## 📧 Alerts & Notifications
- When a potential fuel theft is detected, an **email alert** is sent to the fleet manager.
- The alert includes GPS coordinates for further investigation.

## 📌 Future Enhancements
- **Blockchain-based fuel tracking** for secure transactions.
- **Integration with vehicle OBD-II sensors** for enhanced monitoring.
- **AI-powered route optimization** to reduce theft-prone areas.

## 📜 License
This project is open-source and available under the MIT License.

---
🔗 **Author:** Siddharth Firange | 📧 Contact: siddharthfirange18@gmail.com | 🌐 LinkedIn: www.linkedin.com/in/siddharthfirange


# 🌍 AI-Powered Early Warning System for Environmental Hazards

This project is a demonstration of how artificial intelligence can be used to detect and predict environmental hazards using synthetic sensor data. The system uses a machine learning model (Random Forest) to classify environmental conditions as either hazardous or safe based on simulated readings from environmental sensors.

## 📦 Features

- **Synthetic data generation**: Simulates real-world environmental data including temperature, humidity, CO₂, PM2.5, rainfall, and seismic activity.
- **Hazard classification model**: Uses Random Forest classifier for hazard prediction.
- **Streamlit dashboard**: Interactive interface to visualize data, train the model, and make real-time hazard predictions.
- **Visual insights**: Confusion matrix and feature importance chart.
- **Live prediction**: Users can input sensor values to get immediate hazard detection feedback.

---

## 📁 Project Structure

├── app.py # Streamlit dashboard application
├── synthetic_environmental_data.xlsx # Generated sample dataset
├── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/environmental-hazard-warning-system.git
cd environmental-hazard-warning-system
2. Install Dependencies
Make sure you have Python 3.7+ installed, then run:

bash
Copy
Edit
pip install -r requirements.txt
Or manually install:

bash
Copy
Edit
pip install streamlit pandas numpy scikit-learn matplotlib seaborn
3. Run the Streamlit App
bash
Copy
Edit
streamlit run app.py
This will open an interactive dashboard in your web browser.

📊 Dataset Description
The dataset is synthetically generated to simulate environmental sensor readings. It includes:

temperature (°C)

humidity (%)

co2_level (ppm)

pm25 (µg/m³)

rainfall (mm/hr)

seismic_activity (Richter scale)

hazard (0: No Hazard, 1: Hazard)

🧠 Model Logic
A hazard is flagged based on the following thresholds:

temperature > 40°C

humidity < 35%

co2_level > 600 ppm

pm25 > 100 µg/m³

rainfall > 50 mm/hr

seismic_activity > 3.5

The model is trained using a RandomForestClassifier from scikit-learn.

📌 Future Improvements
Integrate real-time sensor APIs (weather, air quality, seismic).

Deploy as a web app with alert systems (email/SMS).

Expand classification into multi-class hazard types.

Use deep learning models for more complex patterns.

📜 License
This project is open-source and available under the MIT License.

👤 Author
Agbozu Ebingiye Nelvin
Email: nelvinebingiye@gmail.com

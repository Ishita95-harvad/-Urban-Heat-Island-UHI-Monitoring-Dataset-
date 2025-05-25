# -Urban-Heat-Island-UHI-Monitoring-Dataset-
# 🌍 Urban Heat Island (UHI) Monitoring Dataset

Welcome to the **Urban Heat Island (UHI) Monitoring Dataset**! This dataset provides critical insights into the Urban Heat Island effect by tracking temperature variations across urban and rural areas over time. It is useful for environmental scientists, urban planners, and climate researchers.

## 📌 Dataset Overview
- 🌡 **Temperature Variations:** Captures urban vs. rural temperature differences  
- 🏙 **City-Level Monitoring:** Data collected from major cities with noticeable UHI effects  
- 📈 **Climate & Seasonal Trends:** Evaluates UHI intensity during different seasons  
- 🌱 **Impact Assessment:** Examines vegetation, building density, and land-use influence  

## 📂 Data Format
The dataset is provided in CSV format with the following key attributes:
- `Timestamp` – Date and time of temperature recording  
- `Location Type` – Urban or rural classification  
- `City` – Name of the monitored city  
- `Temperature (°C)` – Recorded air temperature  
- `Humidity (%)` – Atmospheric moisture levels  
- `Land Cover Type` – Classification (Concrete, Green Space, Water Bodies)  

## 🔧 Installation
Clone the repository to start analyzing UHI trends:
```bash
git clone https://github.com/yourusername/UHI-Monitoring-Dataset.git
cd UHI-Monitoring-Dataset


Load the dataset in Python for visualization:
import pandas as pd
import matplotlib.pyplot as plt

data = pd.read_csv("UHI_Data.csv")
print(data.head())

plt.hist(data["Temperature"], bins=20, alpha=0.7)
plt.title("Urban vs. Rural Temperature Distribution")
plt.xlabel("Temperature (°C)")
plt.ylabel("Frequency")
plt.show()


📊 Applications
- Urban Climate Planning: Helps cities develop heat-mitigation strategies
- Environmental Sustainability Studies: Evaluates long-term impacts on ecosystems
- Public Health & Heat Risk Analysis: Identifies regions at high heat exposure risk
🤝 Contributions
We welcome contributions! If you have additional datasets or improved analysis models, feel free to submit a pull request.
📜 License
This project is licensed under the MIT License. See the LICENSE file for details


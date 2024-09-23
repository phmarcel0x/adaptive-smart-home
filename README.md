# Smart Home Satisfaction Prediction with Random Forest and Real-Time Simulation

This project explores how **machine learning** and **adaptive systems** can be applied to optimize environmental conditions in a smart home environment. The core objective is to predict **occupant satisfaction** based on environmental data and simulate real-time adjustments to improve comfort. This is achieved using a **Random Forest model** and a real-time simulation system.

## Project Overview

This project focuses on leveraging environmental data, such as CO2 levels, indoor temperature, and humidity, to predict how satisfied occupants are in a smart home. The system uses **Random Forest regression** to estimate satisfaction and then applies adjustments like heating or ventilation to optimize comfort based on these predictions.

### Breakdown of the steps:
- **Exploratory Data Analysis (EDA)**:  
  Data is first cleaned and explored to uncover key relationships between environmental factors and occupant satisfaction.
  
- **Predictive Model**:  
  A **Random Forest Regressor** is used to predict satisfaction based on factors like indoor temperature and humidity. The model is saved and used for simulation purposes.
  
- **System Simulation**:  
  A real-time simulation applies control logic to adjust environmental conditions based on the predicted satisfaction. The simulation dynamically responds to environmental changes to maintain comfort.

### Results
The Random Forest model successfully predicts satisfaction based on environmental data. It is used in the simulation to guide real-time adjustments in a smart home, such as:
- Heating adjustments to increase temperature if satisfaction levels drop.
- Ventilation based on CO2 levels to maintain optimal air quality.

The system continuously monitors and optimizes environmental conditions, demonstrating how **adaptive control systems** can improve occupant comfort.

### Predictive Model and Scaling
The **Random Forest model** and **MinMaxScaler** are trained on environmental data to predict satisfaction levels. These models are saved as `random_forest_model.pkl` and `scaler.pkl`, respectively, for reuse in the simulation.

### Execution Overview
- **Exploratory Data Analysis**: Run `exploratoryDA.ipynb` to clean, explore, and visualize the data.
- **Satisfaction Prediction**: Execute `intelligence.ipynb` to build and save the Random Forest model.
- **Real-Time Simulation**: Use `system.ipynb` to simulate the smart home environment. You can also run `simulation.py` for a live visual interface.

### Potential Future Improvements
- Incorporating more environmental factors such as lighting or noise levels.
- Expanding the system to include **energy-efficient decision-making**, optimizing not only comfort but also resource consumption.

---

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=for-the-badge)
![Tkinter](https://img.shields.io/badge/-Tkinter-FFC300?logo=python&logoColor=white&style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?logo=matplotlib&logoColor=white&style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/-Scikit%20Learn-F7931E?logo=scikit-learn&logoColor=white&style=for-the-badge)

---
#### Have a great day :)

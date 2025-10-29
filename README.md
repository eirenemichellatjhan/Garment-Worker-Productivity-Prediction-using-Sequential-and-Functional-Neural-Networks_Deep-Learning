# Garment-Worker-Productivity-Prediction-using-Sequential-and-Functional-Neural-Networks_Deep-Learning

This project analyzed productivity in a garment factory to understand how factors like overtime, idle time, team size, incentives, and style changes influence performance. The dataset included both operational and temporal features such as date, day, quarter, and SMV (Standard Minute Value).

**Tools**: Python, TensorFlow, Keras, NumPy, Pandas, Scikit-learn, Matplotlib

**Approach**: Built and compared four regression models: two Sequential and two Functional (baseline and modified). The baseline models used ReLU activations, while the modified versions tested ELU to improve stability and avoid dead neurons. Models were evaluated using MAE, MSE, and R².

**Results**: The Sequential baseline model achieved the best balance of accuracy and generalization, with higher R² and lower MAE/MSE than other variants. Functional models showed more flexibility but tended to overfit.

**Key Insight**: While ELU improved training stability, ReLU-based Sequential networks performed best overall. The experiment highlighted that simpler architectures can outperform more flexible designs when data is noisy or limited.

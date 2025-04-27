# Predicting Medical Appointment No-Shows Using MLPs

**Course:** Artificial Neural Networks - Winter 2024  
**Institution:** Shahid Beheshti University - Bachelor's Program

---

## Report

### Abstract
This project investigates the application of Multi-Layer Perceptrons (MLPs) to predict patient attendance for medical appointments. Using the Medical Appointment No-Shows dataset, we implemented various MLP architectures with PyTorch and experimented with different activation functions, optimizers, regularization methods, and hyperparameter tuning techniques. Our aim was to enhance prediction accuracy and robustness.

### 1. Introduction
Medical appointment no-shows lead to resource wastage and inefficient healthcare service delivery. Predicting no-shows can help in proactive patient engagement and better scheduling. Artificial Neural Networks (ANNs), especially MLPs, offer a powerful method for such classification problems.

### 2. Dataset Description
The dataset contains information about:
- Patient demographics (age, gender)
- Appointment details (scheduled date, appointment date, neighborhood)
- Special circumstances (scholarship support, SMS reminders)
- Target variable: No-show status (0 = No-show, 1 = Showed up)

Data was collected from over 110,000 medical appointments.

### 3. Methodology

#### Data Preprocessing
- Handled missing values (none found).
- Converted categorical variables to numerical values using encoding techniques.
- Visualized and addressed class imbalance with resampling methods.

#### Model Implementation
- Built a baseline MLP with PyTorch.
- Experimented with different architectures, ranging from shallow to deeper networks.

#### Literature Review
- Studied the effects of deep vs. wide architectures.
- Reviewed techniques like batch normalization, dropout, and advanced activation functions.

#### Experimentation
- Activation Functions: ReLU, Sigmoid, Tanh.
- Optimizers: SGD, Adam.
- Regularization: Dropout layers, L2 weight decay.

#### Hyperparameter Tuning
- Applied grid search for learning rate, batch size, and number of hidden units.

### 4. Results and Evaluation
- Achieved highest accuracy using an MLP with two hidden layers, ReLU activation, Adam optimizer, and dropout regularization.
- Evaluation Metrics:
  - Accuracy: 82%
  - Precision: 80%
  - Recall: 84%
  - F1-Score: 82%
- Cross-validation improved the reliability of results.

### 5. Visualization
- Plotted loss and accuracy curves to monitor training and validation performance.
- Visualized feature importance through sensitivity analysis.

### 6. Conclusion
Implementing and optimizing MLPs for the No-Shows dataset proved effective in predicting patient behavior. Techniques like dropout, adaptive optimizers, and deeper architectures significantly improved performance. Future work could focus on feature engineering, ensemble methods, or attention-based architectures.

### 7. Future Work
- Integrate time-series features (e.g., days until appointment).
- Explore ensemble models combining MLPs and decision trees.
- Apply attention mechanisms for better feature selection.

---

## Files
- `Medical_appointment.csv`: Dataset file.
- `NowruzProject.ipynb`: Implementation notebook.

---

## References
- PyTorch Official Documentation
- Research papers on Deep Learning Architectures
- Tutorials on MLPs, Regularization, and Hyperparameter Optimization

---

**Good Luck, Have Fun, Code a Lot, and Happy Nowruz!** 🌿🎉🥳


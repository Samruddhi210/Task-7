# Task-7
Elevate Labs Internship Task 7
This project applies Support Vector Machine (SVM) algorithms to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin dataset. The dataset was first preprocessed by converting diagnostic labels into binary values and scaling numerical features. Two SVM models were trained using both linear and RBF kernels, and their performance was evaluated using train-test accuracy and 5-fold cross-validation.

To enhance interpretability and visualization, PCA was used to reduce the dataset to 2D, enabling clear decision boundary plots for both kernels. Further, hyperparameter tuning was performed using GridSearchCV to find the optimal values for C and gamma in the RBF model. A comparative evaluation of cross-validation results highlighted the generalization capability of each kernel type.

The project also explored ideas for innovation such as feature selection (RFE), model benchmarking, interactive visualization with Plotly, and potential deployment via Streamlit. This task showcases both the power and flexibility of SVMs in binary classification problems with real-world health data.

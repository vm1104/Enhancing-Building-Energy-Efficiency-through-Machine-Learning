# Enhancing-Building-Energy-Efficiency-through-Machine-Learning

Project Overview: This project aims to predict the energy efficiency of buildings using various machine learning models. The dataset used includes features such as Relative Compactness, Surface Area, Wall Area, Roof Area, Overall Height, Orientation, Glazing Area, and Glazing Area Distribution. The target variables are Heating Load (HL) and Cooling Load (CL).

Data Processing: We performed descriptive statistical analysis to summarize the data, and a correlation matrix was used to identify relationships between the input features and the target variables. Data normalization was applied to improve the model's performance.

Modeling Approaches: Multiple models were developed and compared, including Linear Regression, Perceptron, Support Vector Machine (SVM), Neural Networks, K-Nearest Neighbor (KNN), and Naïve Bayes. The models were trained using significant variables identified through feature selection processes such as VIF (Variance Inflation Factor).

Model Performance:

Perceptron: Achieved the highest accuracy at 98.2%, suggesting the dataset has a linearly separable structure.
Neural Networks: Close performance with 97% accuracy, with a model architecture of 8 inputs, 1 hidden layer with 2 nodes, and 2 outputs.
SVM: Achieved 94% accuracy with selected significant variables.
KNN: High accuracy with 96% for Y1 and 95% for Y2 using significant variables.
Naïve Bayes: Performed poorly with accuracy around 53-54%.
Key Insights:

Increase Relative Compactness (RC) and Surface Area (SA) to reduce Heating Load (HL).
Decrease Wall Area (WA), Overall Height (OH), and Glazing Area (GA) to reduce both Heating Load (HL) and Cooling Load (CL).
Builders should focus on optimizing these factors to improve energy efficiency in building designs.
Conclusion: The project demonstrates the effectiveness of using machine learning to predict and optimize energy efficiency in buildings. The Perceptron and Neural Networks models provided the most accurate predictions, highlighting the importance of model selection based on data characteristics.

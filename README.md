# Stock Prediction Software

This project is a stock prediction software developed using Python, Tkinter, and Scikit libraries. The software utilizes machine learning algorithms to predict future stock prices based on information obtained from the publicly available Yahoo Finance API. The software achieves a peak accuracy of 52% in its predictions.

## Libraries Used

The project incorporates the following libraries:

- **Python**: Python is a widely used programming language known for its simplicity and versatility. It provides a robust foundation for developing various applications, including machine learning projects.

- **Tkinter**: Tkinter is a standard Python library for creating graphical user interfaces (GUI). It provides a set of tools and widgets that allow developers to build interactive applications with ease.

- **Scikit-learn**: Scikit-learn is a powerful machine learning library in Python. It offers a wide range of algorithms and tools for data preprocessing, model selection, and evaluation. In this project, Scikit-learn is employed to implement machine learning algorithms for stock prediction.

## Machine Learning Algorithms

The stock prediction software employs the following machine-learning algorithms to predict future stock prices:

1. **K-Nearest Neighbors (KNN)**: KNN is a non-parametric algorithm that classifies data based on their proximity to other data points. In the context of stock prediction, KNN can be used to find similar historical stock price patterns and make predictions based on the behavior of similar stocks.

2. **Gaussian Naive Bayes**: Naive Bayes is a probabilistic algorithm that makes predictions based on Bayes' theorem. The Gaussian Naive Bayes variant assumes that the features (in this case, stock price patterns) follow a Gaussian distribution. It can be used to classify stocks based on their likelihood of belonging to different price movement categories.

3. **Support Vector Machines (SVM)**: SVM is a powerful algorithm that can be used for both classification and regression tasks. It works by finding an optimal hyperplane that separates data points of different classes or predicts a continuous value. In stock prediction, SVM can be applied to identify decision boundaries that separate stocks with different price movements.

The software incorporates different kernels in the SVM algorithm:

- **Linear Kernel**: The linear kernel assumes a linear decision boundary between classes. It is suitable when the relationship between stock price patterns and their movement is linear.

- **Radial Basis Function (RBF) Kernel**: The RBF kernel is a popular choice for SVM. It can capture complex relationships between stock price patterns and their movement by using a non-linear decision boundary.

- **Polynomial Kernel**: The polynomial kernel can handle non-linear relationships by mapping the data into a higher-dimensional feature space. It is suitable for stock prediction when there are non-linear dependencies between patterns and price movements.

## Additional Data Integration

To further enhance the prediction accuracy, the software incorporates additional data from the U.S. Senate and House of Representatives stock trading records. This data is cross-referenced with historical price data using the Quiver API. By incorporating information about stock trades made by senators and representatives, the software gains additional insights into potential factors that may influence stock prices. This integration leads to an additional 12% improvement in prediction accuracy.

Note: The accuracy, specificity, and sensitivity of the machine learning algorithms and kernels are calculated and visualized within the software.

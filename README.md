# Iris_Flower_Classification_KNN_Model
# <ins>**Background**</ins>
The primary objective of the project was to develop a deep learning model capable of accurately classifying over 200 species of iris flowers. The project successfully achieved an accuracy of over 95% in this classification task, highlighting the effectiveness of the developed model.

To accomplish this goal, a comprehensive iris dataset from the scikit-learn (sklearn) library was utilized. The dataset consisted of samples from three distinct flower classes: Versicolor, Setosa, and Virginica. Each flower class represents a different species of iris. This sklearn iris dataset provided a reliable and well-structured resource for training and evaluating the deep learning model.

The dataset originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Iris). The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.

The deep learning model leveraged the power of neural networks to learn intricate patterns and relationships within the iris dataset. The model was specifically designed to utilize four key features of the iris flowers: 
 - Length of the sepals
  - Width of the sepals
  - Length of the petals
  - Width of the petals

By analyzing these four features, the deep learning model learned to accurately classify specific iris species. The model was trained to recognize subtle differences in sepal and petal dimensions that distinguish one species from another. The inclusion of these key features allowed the model to capture the essence of the iris species' variations and make accurate predictions.

**Software and Libraries**
- Python
- scikit-learn


# <ins>**Future Features**</ins>
**Model Deployment**:
*The trained deep learning model needs to be saved in a format suitable for deployment. This typically involves converting the model into a serialized format, such as a TensorFlow SavedModel or a serialized pickle file.
*The deployed model should include any necessary preprocessing steps, such as feature scaling or encoding, to ensure the input data matches the model's expectations.

**treamlit Web App Development**:
*Streamlit is a Python library that simplifies the development of interactive web apps. It allows developers to create intuitive user interfaces with minimal code.
*Using Streamlit, you can create a new Python script that loads the trained model and defines the app's layout and functionality.
*The Streamlit app can include input fields where users can provide the required features (sepal length, sepal width, petal length, and petal width) for classification.
*The app can also display the predicted iris species based on the user inputs, along with any additional information or visualizations you want to present.

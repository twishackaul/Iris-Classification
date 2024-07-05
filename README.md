# Iris-Classification
#### Developed a traditional Artificial Neural Network model for classificaton of flower specied in Iris Dataset. Confusion Matrix and Heatmap is used for performance evaluation with performance metrics used during training as Accuracy. 
#### The Iris flower data set or Fisher's Iris data set is a multivariate data set.
#### The data set consists of 50 samples from each of three species of Iris:
- Iris setosa
  
![Screenshot 2024-07-05 214041](https://github.com/twishackaul/Iris-Classification/assets/107127632/00e82e65-8249-4474-9634-431d7ba86fb5)

- Iris versicolor
  
![Screenshot 2024-07-05 214127](https://github.com/twishackaul/Iris-Classification/assets/107127632/22cefbf8-173e-4d87-a4fd-1efa4478cb2e)

- Iris virginica
  
![Screenshot 2024-07-05 214206](https://github.com/twishackaul/Iris-Classification/assets/107127632/f4758182-f02b-49c0-847f-b0a796fefba4)

#### Four features were measured from each sample: 
* The length
* The width of
* The sepals and petals
#### Based on the combination of these four features,  a linear discriminant model was developed to distinguish the species from each other. 

## How to use model:
- Importing libraries: Import necessary libraries such as:-
  * Numpy
  * Pandas
  * Matplotlib
  * Seaborn
  * Tensorflow
  * Keras
  * Warnings
  * Models, datasets, layers

- Loading Data: Then load the data using the already present cifar10 dataset in tensorflow. Use the syntax => datasets.cifar100.load_data()

- Training the model: You can train the model using a traditional Artificial Neural Network. Add the required loss and activation functions, performance metrics along with the optimizers.
  
- Testing model: Test the model using unseen data and calculate the testing accuracy.

- Validating model: Validate or evaluate you model using a Confusion Matrix or Heatmap and calculate the accuracy, precision, recall, F1-Score, etc, according to your necessity.

**Since the dataset is not that large and comparatively clean, a simple ANN would work perfectly for getting correct predictions with maximum accuracy.**

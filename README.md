# `Neural_Network_Charity_Analysis` <br/>

## `Project Overview ` <br/>
The purpose of Neural_Network_Charity_Analysisis to use machine learning and neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by nonprofit organization Alphabet Soup. <br/>
In this project, I had  access to CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years to help the foundation predict where to make investments. <br/>
#### Resources <br/>
• Data Source: [Google](https://www.google.com/), [AlphabetSoupCharity_starter_code](https://github.com/Valeriia161/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity_starter_code.ipynb) , [charity_data](https://raw.githubusercontent.com/Valeriia161/Neural_Network_Charity_Analysis/main/charity_data.csv) .<br/> 
• Software: Jupyter Notebook, Python, Pandas, Git Bash, GitHub, TensorFlow , Machine learning and neural networks. <br/>

# `Result ` <br/>
### Deliverable 1: Preprocessing Data for a Neural Network Model <br/>
Using knowledge of Pandas and the Scikit-Learn’s StandardScaler(), I preprocessed the dataset in order to compile, train, and evaluate the neural network model later in Deliverable 2. <br/>

### Deliverable 2: Compile, Train, and Evaluate the Model <br/>
Using knowledge of TensorFlow, I designed a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. <br/>
### Deliverable 3: Optimize the Model <br/>
Deep learning model was able to predict correctly whether or not a applicants will be successful if funded by Alphabet Soup 72.57% of the time. <br/>
![pic1](https://user-images.githubusercontent.com/110998103/207823939-cabb4093-f59e-4d7d-b232-2ce550361f66.png)
Using knowledge of TensorFlow,I tried to optimize my model in order to achieve a target predictive accuracy higher than 75%. <br/>
First, to increase model performance, I added third layer  . That didn't work. <br/>
![adding_3layer](https://user-images.githubusercontent.com/110998103/207823534-8a052597-a891-4d83-97fc-86099134ddb6.png)
The next step I took was to add more neurons to each layer. It slightly increased Accuracy to 72.61% <br/>

![pic4](https://user-images.githubusercontent.com/110998103/207823234-7db3df35-0960-436a-abb5-b3495e6611ea.png)
Ang the last step I did was increasing epoch numbers. Unfortunately, it didn't work either. <br/>
![image](https://user-images.githubusercontent.com/110998103/207825105-a2ea7ca9-62b8-45c0-8f42-bb6c144b383b.png)

##  `Summary` <br/>
Looking at the training metrics of my model, as I increase the number of neurons within the hidden layer, the classification accuracy improves. It been noticeable that adding multiple neurons to my neural network did not yield a perfect classification model. As input data becomes more complex, neural networks will require more and more optimization tweaks to achieve their desired accuracy. <br/>
The most straightforward means of improving neural network performance is tweaking the model design and parameters. <br/>

When it comes to tweaking a neural network model, a little can go a long way. If we tweak too many design aspects and parameters at once, we can cause a model to become less effective without a means of understanding why. To avoid trapping ourselves in endless optimization iterations, we can use characteristics of our input data to determine what parameters should be changed. <br/>

There are a few means of optimizing a neural network: <br/>

-	Check out your input dataset. <br/>
-	Add more neurons to a hidden layer. <br/>
-	Add additional hidden layers. <br/>
-	Use a different activation function for the hidden layers. <br/>
-	Add additional epochs to the training regimen. <br/>

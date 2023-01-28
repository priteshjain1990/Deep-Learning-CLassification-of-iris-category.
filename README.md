# Deep-Learning-CLassification-of-iris-category.
Built a keras Sequential model with 2 hidden layers each with 128 nodes and relu activation function to introduce non-leanearity. 
Output layer with softmax activation function and 3 nodes each for different o/p categories.
Initial preprocessing of data was done using LabelEncoder and StandardScaler methods of sklear.preprocessing library.
to_categorical method of keras.utils library was used to convert target variable as a one-hot-encoding array.
categorical_crossentropy was the loss function used, as it's multiclass classification problem.
93% accuracy is achieved when evaluated against test dataset.

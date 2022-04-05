# Module-19---Neural-Networks

### Overview of the Analysis

The purpose of this analysis was to utilize machine learning and neural networks to predict if applications funded by the company, Alphabet Soup, will be successful. This was carried out by examining a series of features within a dataset. A neural network is then created in order to decipher the positive impact Alphabet Soup may have on its applicants.

### Results

The variables(s) we considered targeting for this model would be the â€œIS_SUCCESSFULâ€ variable, which determines whether the funding sent by Alphabet Soup was utilized successfully. The feature variables of our model are as follows: application type, affiliation, government classification, use of funding, type of organization, business status, income, special considerations, as well as the ask amount for loans. The variables which were removed from our input data were the â€œEINâ€ and â€œNAME columns, as they did not provide sufficient information to be used in our model.

For this model, I used two hidden layers with 20 and 10 neurons each. The reason for this was because the number of neurons used should be relatively equal the input and output layer.

Figure 1 displays the model's target performance:

![image](https://user-images.githubusercontent.com/93355719/161649366-64b9378a-e997-4f63-a217-3df541c0d51a.png)




To try and increase the model’s performance, the number of neurons and the number of hidden layers added were modified. Using a different activation function, in this case, sigmoid was used. 

### Recommendation 

As displayed above, this neural network model was unable to reach the accuracy score of 75% with the provided structure. The structure can be continually altered, by adding to the number of neurons, the hidden layers, or adjusting the activation function(s). It is also recommended that to explore other options, such as trying another algorithm, such as linear regression. The ensemble method can also be used, to combine two or more algorithms to provide a more accurate response.

>>>>>>> a782f34834f311f88a006ac9e0c1388fa58f540b

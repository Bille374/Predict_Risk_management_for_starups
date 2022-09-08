# Risk_management_associate_at_alphabet_soup

## Goal is to create a model whether applicants will become successful if they get funded by alphabet soup

# Imports
![Screenshot 2022-09-07 205612](https://user-images.githubusercontent.com/69637182/189021312-e68ff75d-600e-48c9-ad4f-eadc99d6948b.png)

## Cvs provided from team has more than 43k, file contains information about organisations,  including whether they ultimately become 
## successful

![Screenshot 2022-09-07 205827](https://user-images.githubusercontent.com/69637182/189021727-6f100662-57f5-4ead-a18b-2869cfc5dd69.png)

 Convert categorical variables by using OneHotEncoder:
 ![Screenshot 2022-09-07 205935](https://user-images.githubusercontent.com/69637182/189024988-24a52982-0f7d-4589-a093-96b4f2517ef1.png) 
 ![Screenshot 2022-09-07 210001](https://user-images.githubusercontent.com/69637182/189025030-0fdaacfc-6647-4ba8-a75c-7a92979e237d.png)
 ![Screenshot 2022-09-07 210026](https://user-images.githubusercontent.com/69637182/189025034-2c76ff29-197f-4dd9-9e71-8feb41fb7da2.png)
 
 ## Continue our analysis our data by using Machine Learning and Neural Network, will create a binary classification model, fit model,
 compile and evaluate then optimize the model 
 
 ![Screenshot 2022-09-07 210220](https://user-images.githubusercontent.com/69637182/189025663-aa7f00c0-5ef1-4bf9-9caf-5b57ca665624.png)
 ![Screenshot 2022-09-07 210306](https://user-images.githubusercontent.com/69637182/189025670-73bf7265-5286-4edd-9b62-bf517690efa6.png)
 ![Screenshot 2022-09-07 210420](https://user-images.githubusercontent.com/69637182/189025756-6fe2b627-abf5-4cc1-b94c-16d6e3940bae.png)
 
 # Finally
 
 ### we try to optimize out last result accuracy by creating two alternative Model 1, Model 2. by adding more neurons, hidden layers, changing 
 ## the activation functions ('Linear','softmax'), also loss ("mse") and number of epochs reduced to 20 from 50. 
 ## by evaluate three models we can tell that the first Model has better accuarcy the Model 1, Model 2.
 
 ![Screenshot 2022-09-07 210420](https://user-images.githubusercontent.com/69637182/189026902-120e5b08-73f1-41d1-8fa0-1b7a95611d45.png)

 ## at the end we save our model into json format to keep reusing  our prepared data when we need it.

 


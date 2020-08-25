# Neural-Networks

1.	How many neurons and layers did you select for your neural network model?

I started off with two layers, the first with 12 neurons and the second with 24, following an example from the module. Once I increased the number of layers to three and increased the number of neurons to 50 for each, the accuracy of my model increased. 

2.	Were you able to achieve target performance?

I was not able to achieve target performance, but I did get closer after I changed the number of layers, neurons, and the type of optimizer, activation. 

3.	What steps did you take to try and increase model performance?

I removed the identification columns and other noisy variables from the data. I increased the number of layers and neurons, capping it at three layers with 50 neurons each to not risk overfitting. I also increased the number of epochs from 50 that I originally had to 1000. Lastly, I played around with the optimizer and the activations to see what would work best and found that adam and rmsprop performed the best but chose to go with adam. 

4.	If you were to implement a different model to solve this classification problem, which would you choose and why?

I would choose the random forest classifier because when I predicted the accuracy, it was similar to my deep neural network model and landed between 70% - 75%. 

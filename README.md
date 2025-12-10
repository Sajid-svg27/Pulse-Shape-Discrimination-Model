 ## Project tasks were following 

1.   Explore the datasets and provide some qualitative method to show the differences between the two type of signals. Explain what feature you have found for discrimination if any.

  - What format of the input data are you going to choose ?
  - Write a pytorch dataset to provide the various training samples needed, what are they ? Explain your dataset split choice.

2. Build or choose a classifier model to discriminate between Li6 and Po datasets. To be a success the experiment requires to obtain an accuracy above 80%.
- record at minima the following training metrics : loss function and accuracy.
- Explain when and why you stop training the model

 NOTE : building a complex model that works can take more time than expected. It is advisable to start with a simpler model even if the performace is poor.  

3. In order to compare your model performance to others we need to estimate the epistemic uncertainty of the model. Choose a method to estimate this error and explain your choice.

4. In our experiment it is crucial to limit the contamination of Po signal to 5% level and retain as much Li6 signals as possible. Show how you would use the ouptut probablities of the model to select the right amount of contamination.

5. Run the classifier on the Phys dataset and estimate the total number of Li6 and Po signals it contains.



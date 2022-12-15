10.6.2022 - Researched some data sets and potential project ideas
\
10.9.2022 - Research weather datasets online, order a dataset of New York historical weather data from National Centers of Environmental Information
\
10.10.2022 - Added weather dataset of Seattle for 10 years and another dataset of 30 different US and Canadian cities for 5 years of comprehensive weather data for over 5 years. Both datasets from Kaggle. 
\
10.25.2022 - Created an iPython file and did a some data analysis on the seattle-weather.csv dataset
\
10.27.2022 - Thought about the data and what I can do with it. Debating whether weather prediction was a useful objective and how I would go about it. Considering changing my idea to detecting deforestation in the Amazon Rainforest using a kaggle dataset of sateille images of various locations in the Amazon Rainforest. Crafting a tool for automatic detection of deforestation can be used on sateille images to alert interested parties and authorities early on so that action can be taken.
\
11.1.2022
Downloaded Amazon Rainforest dataset and tried to understand the data and do a bit of preprocessing.
\
11.10.2022
Wrote the abstract and performed some exploratory data analysis
\
11.22.2022
Started building the CNN model and prepared data for training.
\
11.25.2022
Starting training the CNN model, having some trouble loading the data fast enough into the pipeline
\
12.1.2022
Working on improvement the accuracy of the model. Right now only able to load 2,000 of 40,000 images in at a reasonable speed. Working on loading more data later on. Accuracy able to achieve 80% on validation set. Tried a standard multi-layer CNN model with convolutional layers, max pooling, and final dense layer with sigmoid activation for binary classification. Also tried to do transfer learning using ResNet50. Results are worse than my own model. Tried using stratified splitting, but didn't see any accuracy difference between models.
\
12.5.2022
Recorded the project presentation and uploaded
\
12.12.2022
Worked on writing the paper. Gathered sources and write the outline.
\
12.14.2022
Ran model on a larger dataset of 16,000 images of the 40,000 using Jupyter Notebook on a powerful desktop instead of using Google Colab. It was fast enough to be able to run it in a reasonable amount of time (approx. 1 hour 30 mins). We able to achieve higher accuracy then the smaller dataset. Also experimented with transfering learning using EfficientNetB0 and it fit the training data well, but performed really poorly on the validation set. Worked on writing the paper.
\
12.15.2022
Ran grid search for hyperparameter tuning using different learning rates and model architecture. Ultimately none of them outperformed what I already had. If I had more time I would try random search using other parameters like batch size as well and maybe try bayesian optimization. Worked on writing the paper.









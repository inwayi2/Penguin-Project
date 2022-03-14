# 1. Penguin-Project

2. By: Christen Tai, Ryan Voda, Raashi Chaudhari

3. We determined a small set of measurements that are highly predictive of a penguin’s species and made a Python program that uses machine learning (random forest classifier and logistic regression) to predict the species of penguin given three predictor variables from penguin data.

4. Instructions on how to install the package requirements: 

   conda create --name NEWENV --file requirements.txt
   
5. The demo file, PenguinProjectWalkthrough.ipynb, provides a step-by-step walkthrough of what code to run and discussion of what each block of code does.

   It begins with data exploration, where we isolate columns and create visualizations which explain
   why we end up making predictions based on species, culmen length, and culmen depth. For example,

   ![image](https://user-images.githubusercontent.com/97138009/158109283-01360e86-38d4-4e03-ba24-0bfab4d79b59.png)

   shows us that the qualitative feature of a penguin's island is useful in deducing a penguin's species.
   
   After exploring the data, we define class penguinData() which Reads in csv file of penguin data 
   and cleans up for Species Prediction by functions logisticRegression() or randomForestClassifier().
   
   Then, we create two instances of exception handling, the first trying to read our csv file, and the second ensuring that the csv is useable.
   
   Now we define function logisticRegression(), and when ran with our valid csv as shown, the following output is expected:
   
   ![image](https://user-images.githubusercontent.com/97138009/158109892-e5298af7-2649-4e92-afe2-f0d0b0743332.png)
   
   Now we define function randomForestClassifier(), and when ran with our valid csv as shown, the following output is expected:
   
   ![image](https://user-images.githubusercontent.com/97138009/158109953-c60351ee-192a-4f61-8296-3a75de130177.png)
   
   We now create our final clustering model, which should look like:
   
   ![image](https://user-images.githubusercontent.com/97138009/158110031-75819598-0f84-4e62-acfe-a2d061884a33.png)

   We conclude with a discussion of our models.
   
   Like we said earlier, PenguinProjectWalkthrough.ipynb provides a very in-depth walkthrough of our code, this is just a summary of it.

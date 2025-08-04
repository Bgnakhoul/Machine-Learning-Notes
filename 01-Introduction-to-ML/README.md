# 🧠 Introduction to Machine Learning

Machine learning powers some of most important technologies we use today from translation apps to self-driving cars and weather predictions. It offers new ways to solve today's most complex problems, ML systems fall into one or more of the 4 categories below:

- Supervised Learning
- Unsupervised Learning
- Reinforcement Learning
- Generative AI 

## 📌 Supervised Learning
- Supervised Learning is a way that machines learn by using labeled data, this labeled data helps the model know the correct answers and train on them.
- Types of Supervised Learning:
  - Regression: The prediction of a numeric data (eg. The price of a house in $)
  - Classification: The prediction is a likelihood that something belongs to a category (eg. Photo is a cat or dog)
    - Binary Classification: Prediction is one of two classes (eg. Human or not human)
    - Multiclass Classification: Predicting multiple classes (eg. Cat, dog, bird) 

## 📌 Unsupervised Learning
- Unsupervised Learning is an approach where models are given data without labels (correct answers) and the model is responsible to group (cluster) the data based on similar features.
  
## 📌 Reinforcement Learning
- Reinforcement Learning is an approach where a model is penalized or rewarded based on his actions, the model's goal is to create a policy (strategy) to get the most rewards.
  
## 📌 Generative AI
- GenAI is a type of model that creates content based on the type of input it is given.
  - Types of GenAI:
    - Text-to-Image
    - Text-to-Code
    - Image and text-to-video

## 📌 Machine Learning Workflow and Concepts
- Data or Dataset:
  - Data is at the core of ML, a good dataset contains diverse and a large number of examples. Datasets contain features and labels, not all features of a datset are useful for our model.
- Model
  - The model learns iteratively from the data, first the model makes a prediction then this prediction is compared to the true label (ground truth label) then loss is computed and the model uses this loss to gradually update its solution. Sometimes the model is trained multiple times on the data.
- Evaluating or testing
  - To test our ML model, the model is given new data that it has never seen and we ask for its prediction. The model's prediction are ground truth are compared to get the model's accuracy
- Inference
  - Finally, after tunning some hyper-parameters maybe choosing the best features to use and once we are satisfied with the results. We use the model to make inferences (predictions) in the real world.



# AIML_project
Made a model to predict the codeforces rank using decision tree 


## Codeforces Rank Prediction Using Decision Tree
Our project aims to predict the rank category (e.g., Candidate Master, Master, Grandmaster etc) of Codeforces users based on their 10 contest performance data. We use a Decision Tree classifier to build the predictive model, leveraging the model's interpretability and efficiency for this multiclass classification task.

## Dataset Description:
The dataset consists of 1,424 samples, with each row representing a user and their performance across multiple contests. 

The columns are:

userid: Unique identifier for each user.

rank-type: Categorical variable representing the user’s ranking category (e.g., Candidate Master, Master, Grandmaster, etc.).

contest1 to contest10: Numerical scores or ranks obtained by each user across 10 different contests, reflecting their performance over time.

# instructions to run the program
1->Download the Notebook: Download 2.ipynb from this repository.

2->Open in VS Code: Launch VS Code, open 2.ipynb in the editor.

3->Run All Cells: In the top menu, select Run > Run All Cells to execute the code.

To download all the libraries for running the program, run the below command in terminal.

bash Code

pip install -r requirements.txt

## accuracy of our model
98.49548645937813 %

## graphs

Confusion Matrix

1. Learning Curve: This graph shows how the model's performance improves as the training data size increases. It helps to identify if the model is overfitting and if  performing well with the given data or not.

2. Decision Tree Visualization: This graph represents the structure of the decision tree, showing the feature splits at each node, the entropy, sample counts, and the classification outcome at each leaf node. By visualizing this, we can see how the model makes classification decisions .

3. Confusion Matrix: This matrix provides a summary of prediction results, showing the number of correct and incorrect predictions for each class. It’s useful for evaluating model accuracy and identifying any classes the model struggles to predict accurately.
   

   


# Email similarity
In this project, I will be utilizing scikit-learn's Naive Bayes implementation to work with various datasets for text classification. My primary objective is to assess the classifier's accuracy and determine the difficulty level of distinguishing between different categories of text documents. Specifically, I will explore how challenging it is to differentiate between emails related to topics like hockey and soccer or emails about hockey and technology.

**Key Project Objectives:**

1. **Exploring the Data**: I will begin by examining a dataset of emails, each labeled based on its content. I'll investigate the categories represented in the dataset to understand the scope of classification.

2. **Selecting Categories**: My focus will be on evaluating the effectiveness of a Naive Bayes classifier in distinguishing between baseball and hockey-related emails. I will specify the relevant categories for my analysis.

3. **Data Inspection**: I'll take a closer look at one of the emails within the chosen categories to understand the content.

4. **Label Analysis**: To determine whether an email is related to baseball or hockey, I'll inspect the labels associated with the emails and map them to their respective categories.

5. **Creating Training and Test Sets**: I will split the data into training and test sets to facilitate model training and evaluation. This split will ensure consistency across runs by using the `random_state` parameter.

6. **Counting Words**: I will transform the emails into lists of word counts using the `CountVectorizer` class, enabling me to work with numerical data.

7. **Building a Naive Bayes Classifier**: I'll create a Multinomial Naive Bayes classifier and train it using the training data and associated labels.

8. **Model Evaluation**: I will assess the performance of the Naive Bayes Classifier by calculating its accuracy score on the test data. Accuracy measures the percentage of correct classifications made by the classifier.

9. **Testing Other Datasets**: To further explore the classifier's capabilities, I will apply it to different datasets with varying topics and assess its performance. I'll examine scenarios where the topics are distinct to determine the classifier's accuracy.

Throughout this project, I aim to gain insights into the effectiveness of the Multinomial Naive Bayes classifier in classifying text documents and the challenges it may encounter when distinguishing between different categories of content.
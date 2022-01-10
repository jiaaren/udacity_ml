## Summary
1. Historical perspective of machine learning and how it evolved from the fields of statistics, and computer science.
2. Supervised learning is used for many business applications from spam filters to movie recommendations. We looked at the two broad categories of supervised machine learning:
    - Classification
    - Regression Deep learning can be used within supervised machine learning to create techniques that are better at image recognition or identifying when a movie was created based on the video footage.
3. Scikit-learn as a library in Python for machine learning
4. The ethical challenges ahead of us in the field.

### History of machine learning
- Statistician's perspective of understanding data -> field of **mathematics based on questions**, i.e. how do we understand mechanisms that **create** data. From these questions, probability based models were used to model world around us
    - e.g. For example, there's a distribution to model expected scores on a test, number of daily incidence on a stretch of road, or how frequently words show up in a body of text.
    - These were breakthroughs to describe data in every aspect of real life, but are still an oversimplification of complexities of real world.
- Computer scientist's perspective -> divergence to not use so much **if/else statements** explicitly coded by programmers, but have computer make decisions themselves. *This idea of recognizing patterns and data is what is commonly recognized as machine learning.*
  - Currently models outperform human enforced if/else statements and also Distributions known as well-known probability distributions
  - Unfortunately, these often leave the **why** of a prediction **unknown**. We're still not able to explain why the computer is making these decisions.

### Machine Learning Problems
1. The problem ->  Normally, the problem corresponds to **evaluating some data and making predictions**.
2. Tools (algorithms) -> e.g. linear or classification regression or decision trees
3. Evaluation metrics -> which tool works best? Determine after we evaluated a number of algorithms used.  

### Types of Machine Learning
1. Supervised
    - Looks as **labeled** data and make predictions on **unlabeled** data
    - Categories
      - Classification (e.g. predict dog breed)
      - Regression (e.g. predict home price)
2. Unsupervised
3. Reinforcement Learning

### Ethics
- Bias held by users will be ingested by computers since data is generated by humans
- As an example, imagine you want to build a model to predict who the best candidate is for a job based on existing data. If there were biases and historical hiring patterns based on gender, race, age, economic status et cetera, these biases are going to be held by any predictive model you build based on these data.

- Emerging technologies

### Prerequisites
- Understanding Calculus and linear algebra
  - https://betterexplained.com/guides/calculus/
  - https://betterexplained.com/articles/linear-algebra-guide/
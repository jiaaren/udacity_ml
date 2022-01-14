### Overview
1. Learn the basics of clustering data
2. Cluster data with the K-means algorithm

#### Use-cases of K-Means
- Cluster similar books and articles
- Cluster similar Music, movies - to build recommendation clusters in netflix or spotify
- Cluster similar groups of customers / students - so better teaching strategies can be employed

## K-means
### Visualising in 2 dimensions
- '**k**' represents the number of clusters you have in your dataset
- In example below, k value is 2
- **blue** represents travelling to work, and **red** represents visiting families
<img src='1_k_visual.PNG'>

### Visualising in 3
- We can also view in 3-dimensions, but the angle of perspective matters
- refer to `Identifying_Clusters.ipynb`

### K parameter
- What is a good k value?
- In this example 3 is clearly appropriate visually
<img src='1_kparam1.PNG'>

- In this example 2 is clearly better than 3
<img src='1_kparam2.PNG'>

- But, If we have **large observations** and **large features (dimensions)**, how to choose k?
  - It's a balance of art and science
- We can choose k based on **prior knowledge**
  - E.g. udacity groups students to
    - 1. Students new to field
    - 2. Students wanting to skill up in their existing careers
    - 3. Students wanting to change careers
  - So, **k can be 3**
- If no prior knowledge, we can use **decision methods instead**

<img src='1_kparam3.PNG'>

### Decision methods -> elbow method
-  Each time additional centers are considered, the distances between the points and the center will decrease. However, at some point, that decrease is not substantial enough to suggest the need for an additional cluster.

#### [Scree plot](https://www.google.com/search?q=scree+plot&sxsrf=AOaemvIPL4xeEMx0vstGWFYCEUk7JI4fQg:1642148833104&source=lnms&tbm=isch&sa=X&sqi=2&ved=2ahUKEwjXx_WO6bD1AhUZqZUCHU3sAwEQ_AUoAXoECAIQAw&biw=1396&bih=691&dpr=1.38)
- Using a scree plot is a common method for understanding if an additional cluster center is needed. The elbow method used by looking at a scree plot is still pretty subjective, but let's take a look to see how many cluster centers might be indicated.

- refer notebook `Changing K.ipynb`

## TODO
- exercise, why can 5 dimensions translate to 3 visually?
- Kmeans for classification problems, just 2 categories?
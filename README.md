# Netflix-Clustering-Capstone-Project
## AlmaBetter Verfied Project:- <a href="https://www.almabetter.com/"> AlmaBetter School </a>
![Netflix_Logo_PMS](https://user-images.githubusercontent.com/103633582/208310011-ad8a7438-1687-4a83-a588-e01caf89b395.png)

I have clustered Netflix Movies And TV Shows Data with K-Means Clustring and built a recommender system in Google Colab which recommends 5 movies based on input movie  using cosin similarity.

# 💾 Project Files Description

This Project includes 1 colab notebook, 1 technical documentation as well as 1 presentation:

## Executable Files:

* File Name - Includes all functions required for classification operations.
## Output -
* **Google Colab** - All the outputs are visible in the provided colab notebook.
## Data Source:
* **Dataset** - https://www.kaggle.com/shivamb/netflix-shows
# 📖 K-Means And Recommender System
We have used a K Means clustering with an optimal value of k=9 for clustering the Text Based Columns. The value of k was chosen from the elbow method of WCSS score and silhouette score.

I was able to come up with the following clusters and name it accordingly.
1. Cluster 0: Kids, Animation & Anime
2. Cluster 1: Musical International & Indian
3. Cluster 2: Drama, International, Indian
4. Cluster 3: Documentaries, Sports
5. Cluster 4: Drama, American, Adventure
6. Cluster 5: Comedy
7. Cluster 6: Horror
8. Cluster 7: International TV Shows
9. Cluster 8: Family Movies

A simple recommendation system was also made as an additional project on cosine similarity of description column and movie column, it also experimented in the notebook.

# 📋 Execution Instruction
The order of execution of the colab notebook is as follows:
nane of dataset
First, click on the open in colab button present on the top center of the notebook.

2) Kaggle Dataset

Downlaod the dataset from kaggle through provided link.Then, connect to the runtime and execute the cell to mount the drive or upload the data file to the current runtime.

3) Cell Path

Finally, delete the path in the dataset loading cell and replace it with the path of your current data file. Run each cell to see the output below it.

# 📜 Credits
Manas Ranjan Behera | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

# 📚 References

* Kaggle.com 'EDA & Recommend Netflix' [Online].

Available: https://www.kaggle.com/poolkit/eda-recommend-netflix

* Medium.com 'Understanding K-means Clustering in Machine Learning' [Online].

Available: https://towardsdatascience.com/understanding-k-means-clustering-in-machine-learning-6a6e67336aa1

* neo4j.com, 'Cosine Similarity'. [Online].

Available: https://neo4j.com/docs/graph-data-science/current/alpha-algorithms/cosine/#:~:text=Cosine%20similarity%20is%20the%20cosine,'%20lengths%20(or%20magnitudes).



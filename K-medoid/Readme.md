# K-Medoid
The program will take two inputs: a data file containing multiple continuous features which in our case is quality.csv and a value for k. 
This code is implemented for both, k=2 and k=3. 

This code calculates the dissimilarity matrix and then apply the k-medoids algorithm. 

- The clustering process will continue until cluster assignments do not change or maximum 100 iterations have been completed. 
- Then will also calculate average silhouette width for the final clustering solution. 
- A new column is added containing cluster ids (1, 2, 3, …, k) to the original input file and saved it to clusters_k.csv, where k is the number of clusters. 
- The average silhouette width will be displated in the console. 

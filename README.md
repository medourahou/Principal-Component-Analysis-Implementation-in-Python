# Principal-Component-Analysis-Implementation-in-Python

The code implements Principal Component Analysis (PCA), a popular dimensionality reduction technique, in Python. The goal of PCA is to transform high-dimensional data into a lower-dimensional space while retaining as much of the original data's variance as possible. The code performs PCA on a given dataset and provides various insights into the data's structure and patterns.

Key Steps:

**1- Data Preprocessing:**

The input data is a 2D matrix (list of lists) representing a dataset, where rows represent individuals or samples, and columns represent variables or features.
The code calculates the mean and standard deviation for each variable to perform data standardization (mean-centering and scaling).

**2- Covariance Matrix and Correlation Matrix:**

The code calculates the covariance matrix to understand the relationships between different variables and their covariance.
It also constructs the correlation matrix to investigate the linear relationships and correlations between variables.

**3- Eigenvalue Decomposition:**

PCA performs eigenvalue decomposition on the correlation matrix to obtain eigenvectors and eigenvalues.
The eigenvectors represent the principal components, and the eigenvalues indicate the variance explained by each principal component.

**4- Principal Component Scores:**

The code computes the principal component scores for each individual in the dataset, which represent the coordinates of individuals in the new lower-dimensional space.

**5- Principal Component Analysis Results:**

The code presents the results of PCA, including the correlation matrix, eigenvectors, eigenvalues, principal component scores, and percentage of variance explained by each principal component.
Contributions and Cosine Squared for Individuals and Variables:

The code calculates the contributions and cosine squared values for individuals, indicating how much each individual contributes to each principal component and how well they are represented in the reduced space.
It also computes the contributions and cosine squared values for variables, indicating the contribution of each variable to each principal component and the quality of variable representation.

**6- Output and Visualization:**

The results of PCA, along with various intermediate calculations, are printed to the console and saved to a text file named "resultatACP.txt."
Note: The code uses popular Python libraries, such as numpy for numerical computations, and numpy.linalg.eig for eigenvalue decomposition. It is assumed that the correlation matrix variable is defined elsewhere or provided as input to the code. Additionally, the code measures the execution time using the time module to provide insights into the computation time for the PCA process.


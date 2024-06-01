run: pip install -r requirements.txt 
To download used libraries

# Support-Vector-Machine-Python-IRIS-Dataset
Support Vector Machine implementation in Python with IRIS Dataset with 3 kernels i.e; Linear Kernel, Polynomial Kernel, RBF kernel.

Support Vector Machine:
  Support Vector Machine (SVM) is a supervised machine learning algorithm used for both classification and regression. Though we say regression problems as well it’s best suited for classification. The main objective of the SVM algorithm is to find the optimal hyperplane in an N-dimensional space that can separate the data points in different classes in the feature space. The hyperplane tries that the margin between the closest points of different classes should be as maximum as possible. The dimension of the hyperplane depends upon the number of features. If the number of input features is two, then the hyperplane is just a line. If the number of input features is three, then the hyperplane becomes a 2-D plane. It becomes difficult to imagine when the number of features exceeds three. 


Here are some common types of kernels in support vector machine algorithms:
1. Linear Kernel:
  The linear kernel is the simplest and is used when the data is linearly separable.
  It calculates the dot product between the feature vectors.
  <img width="450" alt="Linear Kernel" src="https://github.com/BhaskarMaity00/Support-Vector-Machine-Python-IRIS-Dataset/assets/127765061/10f8920c-22f9-4be4-99ae-74b99a551845">
  
3. Polynomial Kernel:
  The polynomial kernel is effective for non-linear data.
  It computes the similarity between two vectors in terms of the polynomial of the original variables.
<img width="457" alt="image" src="https://github.com/BhaskarMaity00/Support-Vector-Machine-Python-IRIS-Dataset/assets/127765061/e7cfe24d-52d5-454e-8418-80b28d41f850">

5. Radial Basis Function (RBF) Kernel:
   
  The RBF kernel is a common type of Kernel in SVM for handling non-linear decision boundaries.
  It maps the data into an infinite-dimensional space.
  
<img width="466" alt="image" src="https://github.com/BhaskarMaity00/Support-Vector-Machine-Python-IRIS-Dataset/assets/127765061/6ca6e5cd-edc0-4bc8-bad8-599d81b0caff">

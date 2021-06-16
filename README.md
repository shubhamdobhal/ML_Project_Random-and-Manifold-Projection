# ML_Project_Random-and-Manifold-Projection

Code has 9 sections :
  
  **Loading and visualization of original data**
  1. Loading MNIST handwritten digit images.
  2. visualisation of some images.
  
  **Classifier based quality comparision of random and manifold projection based dimensionality reduction techniques.**
  3. forming training and test data from the training and testing images respectively.
  4. Classifier trained on Original training data (without applying any dimensionality reduction techniques).
  5. Classfier trained on Data projected using PCA.
  6. Classifier trained on data projected using Random prokection (linear Projection)
  7. Classifier trained on data mapped using non-linear mapping LLE (manifold learning technique)
  8. Classifier trained on data mapped using another non-linear mapping t-SNE (manifold learning technique)
  
  **Visualizer based quality comparison of linear and non-linear dimensionality reduction techniques
  9. Vizualization of Projected data.


Quality of above dimensionality reduction techniques is measured based on two factors :
    1. Time taken by technique for reducing the dimesions of data.
    2. Order to which information is preserved after reducing dimension of original data.

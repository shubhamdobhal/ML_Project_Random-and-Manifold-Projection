# ML_Project_Random-and-Manifold-Projection

Code has 9 sections :</br>
  
  **Loading and visualization of original data**</br>
  1. Loading MNIST handwritten digit images.</br>
  2. visualisation of some images.</br>
  
  **Classifier based quality comparision of random and manifold projection based dimensionality reduction techniques.**</br>
  &nbsp;&nbsp;&nbsp;&nbsp;3. forming training and test data from the training and testing images respectively.</br>
  &nbsp;&nbsp;&nbsp;&nbsp;4. Classifier trained on Original training data (without applying any dimensionality reduction techniques).</br>
  &nbsp;&nbsp;&nbsp;&nbsp;5. Classfier trained on Data projected using PCA.</br>
  &nbsp;&nbsp;&nbsp;&nbsp;6. Classifier trained on data projected using Random prokection (linear Projection)</br>
  &nbsp;&nbsp;&nbsp;&nbsp;7. Classifier trained on data mapped using non-linear mapping LLE (manifold learning technique)</br>
  &nbsp;&nbsp;&nbsp;&nbsp;8. Classifier trained on data mapped using another non-linear mapping t-SNE (manifold learning technique)</br>
  
  **Visualizer based quality comparison of linear and non-linear dimensionality reduction techniques**</br>
  &nbsp;&nbsp;&nbsp;&nbsp;9. Vizualization of Projected data.</br>


Quality of above dimensionality reduction techniques is measured based on two factors :</br>
 &nbsp;&nbsp;&nbsp;&nbsp;   1. Time taken by technique for reducing the dimesions of data.</br>
 &nbsp;&nbsp;&nbsp;&nbsp;   2. Order to which information is preserved after reducing dimension of original data.</br>

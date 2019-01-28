<h1>Dependency</h1>
<ul>
  <li>
    Tensorflow </br>
    Install: https://www.tensorflow.org/install/
  </li>
  <li>
    Keras </br>
    Install: https://keras.io/#installation
  </li>
  <li>
    Biopython </br>
    Install: https://biopython.org/wiki/Download
  </li>
  <li>
    Jupyter Notebook </br>
    Install: https://jupyter.org/install.html
  </li>
</ul>

<h1>Instruction</h1>

1. The jupyter notebook contains necessary python code to run and text chilenpred.
2. The first to ninth block are for data preprocessing. They will read enhancer and non-enhancer strings from the respective files
3. Block 10-12 is for generating hilbert curve for a given order. 
4. Block 15 is the utility function to convert the strings to images based on hilbert curve
5. Block 16-17 created hilbert curve based images for positive and negative samples respectively
6. Block 18 is the generator funtion to the keras model 
7. Block 19,20,22 is unnecessary at the moment. They were experimental models. 
8. Block 21 is the generator declaration for training,validation and test data. The split can be found from the start and end indices of the respective generator
9 . Block 23 and 26 is the model code. 23 is the declaration and 26 is the compilation section
10. Block 24,25,27 are experimental models and therefore unnecessary
11. Bloc 28 execution will result in the model being trained based on the training and validation split described in block 21.
12. 

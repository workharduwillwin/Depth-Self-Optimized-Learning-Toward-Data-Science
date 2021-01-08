# Depth-Self-Optimized-Learning-Toward-Data-Science(DSOL)
We proposed a two-stage model called Depth Self-Optimized Learning(DSOL). DSOL is used to realize ANN depth self-configuration, self-optimization. Our code is run on juypter notebook, so the experimental results are retained.
# Background
A large number of studies have shown that the performance of ANN is closely related to its depth and width. Although it's possible to develop a universal model based on some theorm such as universal approximation theorem so that could approximate on various datasets, according to the no free lunch(NFL) theorem, no model could fit all kinds of datasets. Even if we design a general model for a variety of different datasets within the allowable error range, we do not need to use more complex methods for those tasks can be completed by simple methods. However, If a model could optimized itself according to specific datasets, maybe it can be adapted to a variety of different datasets. Based on those ideas mentioned above, we decide to develop a model could realize ANN depth self-optimized, self-configuration so as to be able to approximate on more different kinds of datasets.
# Conditions
* Development Environment
  * Juypter notebook
* Language
  * pyhon
* Library
  * Keras
  * tensorflow-gpu
  * matplotlib
  * numpy
* Theoretical Support: Our Paper link will be uploaded soon.
# File
* File List
 * "Depth self-optimized learning toward datascience "  
   * "F-model(First-stage of DSOL) test"  
      * "F-model test.ipynb"  
      * Figures created by "F-model test.ipynb"  
   * "RL-stage(Second-stage of DSOL)&DSOL test"  
      * "second stage of Depth self-optimized learning test& total framework valid"  
      * Figures created by "second stage of Depth self-optimized learning test& total framework valid" & "create figure.ipynb"   
      * Data created by "second stage of Depth self-optimized learning test& total framework valid"    
      * Weights of RL    
   * "info of DSOL Architecture.ipynb"
 
We upload a folder "Depth self-optimized learning toward datascience " consists of three files: "F-model(First-stage of DSOL) test", "RL-stage(Second-stage of DSOL)&DSOL test", "info of DSOL Architecture.ipynb".
* File Introduction  
  * "info of DSOL Architecture.ipynb": 
    * This file is used to show the architecture and parameter of DSOL.  
  * "F-model(First-stage of DSOL) test":This 
    * This file is used to test the first stage of DSOL. 
      * One major experiment is to test the F-model approximation ability on Boston housing dataset. Using training, valid data to train F-model in turn. 
      * Another major experiment is to test the F-model generalized ability on Boston housing, Iris dataset.
  * RL-stage(Second-stage of DSOL)&DSOL test": 
    * This file is used to test second stage of DSOL as well as well trained DSOL.
      * Initialize the ANN by hand, use the RL to optimize ANN depth so that obtain the optimal depth. Then using the optimal depth to train F-model. We visualized the change of         ANN depth, and its loss function accordingly.
      * Another major experiment Using the trained DSOL run on the valid dataset.
PS: most of the figures and data used in the paper could be found in the uploaded files.
      
 
 
 

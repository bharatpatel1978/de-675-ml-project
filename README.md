# de-675-ml-project
ML Project for DS 675 - ML

Report: https://docs.google.com/document/d/1eQEKKsYYbIXy29tR12bsVBT_MJkphzyCEWct_OFB5VQ/edit?usp=sharing

Prerequisites:
Ensure Local Development environment is properly setup and that objectives are clearly stated
Local Development environment:
1.	Github - Source Control – Will be used for storing and sharing documents and the JupyterLab files that will have implemented different algorithms.
2.	Install Git - https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
3.	Install PIP - https://pip.pypa.io/en/stable/installation/
4.	Install Anaconda - https://docs.anaconda.com/anaconda/install/
5.  Install jupyterlab - https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html
6.  Install jupyterlab-github extension - https://github.com/jupyterlab/jupyterlab-github
5.	Ensure we have text editor like notepad or notepad++ or anything specific your OS like TextEdit or BBEdit, Sublime for Mac. We can get VS Code as well as that is available in both Mac and Windows OS’s.
6.	Packages that need to be installed - Pandas, numpy, seaborn, skikit-learn, Kagglehub, Imbalanced Learn. We installed them via anaconda. 

Objectives:
1. Transforming the dataset to make it useful for binary classification by introducing the pass/fail value of let's say 60% - kNN Algorith
2. Transforming the dataset to make it multiclassification by introducing the various grades - kNN Algorith - Classifications [0 to 59.99 - F Grade, 60 to 69.99 - D Grade, 70 to 79.99 - C Grade, 80 to 89.99 - B Grade, 90 and above A Grade]
3. Use the dataset as is for Linear Stochastic regression
4. Multi Classification by Random Forest
5. Prediction by Multilayer Perceptron - MLP Classifier
6. Establish key features

Technical Difficulties:
1. Jupyter Lab failed to launch as Jupyter Server could not start due to port denial. Opened the command prompt in Administrator mode to run the command - net stop winnat. Then ran the command - net start winnat. That seemed to fix the port usage denial issue  

Learnings:





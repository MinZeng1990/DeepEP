# DeepEP

DeepEP is a deep learning framework to automatically predict essential proteins using PPI network and gene expression data.

# Requirements

tensorflow==1.0.0

numpy==1.11.2

networkx==2.0

scikit-learn==0.18

gensim==0.13.3

# Usage

  Please follow the instructions of node2vec ( https://github.com/aditya-grover/node2vec ) to generate the node vectors of PPI network. In our study, we generated 64-dimensional vector for each node. The specific parameters are as follows. Length of walk per source is 20, number of walk per source is 10, window context size for optimization is 10, and the rest parameters remain the default settings. 
  In this GitHub project, we give a demo to show how DeepEP works. 
  
# Citation

# License
This project is licensed under the MIT License - see the LICENSE.txt file for details
